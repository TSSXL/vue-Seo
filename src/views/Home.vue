<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'Home',
  metaInfo: {
    title: '首页', // set a title
    meta: [{             // set meta
      name: 'keyWords',
      content: '我是contact关键字'
    },
      {
        name: 'description',
        content: '我是contact描述'
      }],
    link: [{ // set link
      rel: 'asstes',
      href: 'https://assets-cdn.github.com/'
    }]
  },
  components: {
    HelloWorld
  }
}
</script>
