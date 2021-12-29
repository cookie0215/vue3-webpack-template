<template>
  <h1>{{message}}</h1>
  <HelloWorld />
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue' 를 config설정에 맞게 아래처럼 변형함
import HelloWorld from '~/components/HelloWorld'

export default {
  components: {
    HelloWorld
  },
  data() {
    return {
      message: 'Hello Vue!!'
    }
  }
}
</script>

<style>
  h1 {
    font-size: 100px;
  }
</style>