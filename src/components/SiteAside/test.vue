<template>
 <div class="test-container">
    <SiteAside  />
 </div>
</template>

<script>

import SiteAside from './index.vue';
import '@/styles/global.less';

export default {
  components: {
    SiteAside,
  },

};
</script>

<style lang="less" scoped>
.test-container{
  width: 250px;
  height: 600px;
  border: 2px solid;
  margin: 0 auto;
}

</style>
