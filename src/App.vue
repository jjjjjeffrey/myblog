<template>
  <div id="app">
    <nav-view></nav-view>
    <post-list-view></post-list-view>
  </div>
</template>

<script>
  import NavView from './NavigatorView'
  import PostListView from './PostListView'
  export default {
    components: {
      PostListView,
      NavView},
    name: 'app'
  }
</script>
