<template>
  <div id="app">
    <Post />
  </div>
</template>

<script>
  import Post from './components/Post'

export default {
  name: 'App',
  components: {
    Post
  }
}
</script>

<style lang="sass">
        body
              margin: 0
              padding: 0
              background:
                    color: #F3F3F3
</style>
