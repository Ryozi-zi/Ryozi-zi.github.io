<template lang="html">
  <h1 class="hello">{{msg}}</h1>
</template>

<script>
export default {
  name: 'Home',
  data () {
    return {
      msg: 'こんにちは。'
    }
  }
}
</script>

<style lang="scss" scoped>
.hello{
  padding-top: 3rem;
  font-size: 5rem;
  -ms-writing-mode: tb-rl;
  writing-mode: vertical-rl;
  position: absolute;
  left: 50%;
}

@media (max-width: 480px){
  .hello{
    height: 550px;
    position: static;
  }
}
</style>
