<template>
  <div>
    <van-button type="primary" class="test">hello</van-button>
    <van-icon class="iconfont" class-prefix='icon' name='shuaxin' size="2em" />
    <Tabbar/>
  </div>
</template>

<script>
import Tabbar from '../components/Tabbar'
export default {
  name: 'Home',
  components: {
  Tabbar
  }
}
</script>
<style lang="scss" scoped>
  .test{
    font-size:30px;
    }
</style>
