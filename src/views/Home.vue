<template>
    <div class="home">
        首页
    </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'home',
  components: {
    HelloWorld
  },
  
}
</script>

<style lang="scss">
    .home{text-align: center;line-height: 500px;font-size: 20px;font-weight: bold}
</style>
