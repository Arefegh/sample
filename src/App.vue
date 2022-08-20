<template>
  <MyHeader/>
  <HelloWorld/>
  <MyFooter/>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import MyHeader from './components/MyHeader.vue'
import MyFooter from './components/MyFooter.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
   MyHeader,
   MyFooter
  }
}
</script>



