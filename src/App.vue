<template>
  <div id="app">
    <Search/>
    <ActiveVideo/>
    <VideoList/>
  </div>
</template>

<script>
import Search from './components/Search'
import ActiveVideo from './components/ActiveVideo'
import VideoList from './components/VideoList'

export default {
  name: 'App',
  components: {
    Search,
    ActiveVideo,
    VideoList
  }
}
</script>
