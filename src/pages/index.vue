<template>
  <div>
    <HelloWorld  msg=""/>
    <h1 className="text-3xl font-bold underline">
      Hello world!
    </h1>
    <div>{{msg}}</div>
  </div>
</template>
<script setup lang="ts">
import HelloWorld from '../components/HelloWorld.vue'
const msg = ref('123')

</script>





<style scoped>

</style>