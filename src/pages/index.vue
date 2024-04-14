<template>
  <div ref="target" class="green">
    <HelloWorld  msg=""/>
    <h1 className="text-3xl font-bold underline">
      这是首页
    </h1>
    <div>{{msg}}</div>
  </div>
  <div>{{ x}} {{y}} {{isOutside}}</div>
</template>
<script setup lang="ts">
import HelloWorld from '@/components/HelloWorld.vue'
const msg = ref('123')
const target = ref(null)
const { x, y, isOutside } = useMouseInElement(target)

</script>





<style scoped>

</style>