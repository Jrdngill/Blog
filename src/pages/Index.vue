<template>
<!--
  <Layout>

     Learn how to use images here: https://gridsome.org/docs/images 
    <g-image alt="Example image" src="~/favicon.png" width="135" />

    <h1>Hello, world!</h1>

    <p>
      Lorem ipsum dolor sit amet, consectetur adipisicing elit. Pariatur excepturi labore tempore expedita, et iste tenetur suscipit explicabo! Dolores, aperiam non officia eos quod asperiores
    </p>

    <p class="home-links">
      <a href="https://gridsome.org/docs/" target="_blank" rel="noopener">Gridsome Docs</a>
      <a href="https://github.com/gridsome/gridsome" target="_blank" rel="noopener">GitHub</a>
    </p>
    </div>
  </Layout>
  -->
  <div class="soon">  
    <img src="https://media4.giphy.com/media/j0ph697YBTGM8zm3u8/giphy.gif" alt="fox hiding in grass">
    <p>Coming soon'ish, tis a work in progress my friends.</p>
    <a href="https://twitter.com/jrdngill">@jrdngill</a>
  </div>
</template>

<script>
export default {
  metaInfo: {
    title: 'Hello, world!'
  }
}
</script>

<style>
.home-links a {
  margin-right: 1rem;
}
.soon {
  text-align: center;
  padding-top: 100px;
}
.soon a {
  color:#426342;
  
}
</style>
