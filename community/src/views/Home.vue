<template>
  <div class="home">
    <Header></Header>
    <Content></Content>
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'
import Header from '@/components/layout/Header.vue'
import Content from '@/components/layout/Content.vue'

export default {
  name: 'home',
  components: {
    Header,
    Content
  }
}
</script>
