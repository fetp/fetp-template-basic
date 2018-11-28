<template>
  <div id="app">
    <HelloFetp :text="text"/>
  </div>
</template>

<script>
import HelloFetp from '@/component/HelloFetp'
export default {
  name: 'app',
  data () {
    return {
      text: 'Hello FETP'
    }
  },
  components: {
    HelloFetp
  }
}
</script>

<style lang="scss">
@import '~@/css/index.scss';

#app {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 350px;
  line-height: 350px;
  color: #fff;
  font-size: 72px;
  font-weight: bold;
  text-align: center;
  background: #000;
}
.logo {
  width: 150px;
  height: 150px;
}
</style>
