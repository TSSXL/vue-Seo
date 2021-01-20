<template>
  <div class="about">
    <h1>This is an about page</h1>
  </div>
</template>
<script>
  export default {
    metaInfo: {
      title: '我是contact头', // set a title
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
    }
  }
</script>
