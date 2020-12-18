<template>
  <div>
    <div class="side-bar">
      <DownloadInfo></DownloadInfo>
    </div>
    <div class="map-context">
      <MapInfo></MapInfo>
    </div>
  </div>
</template>

<script>
import DownloadInfo from '../components/downloadInfo'
import MapInfo from '../components/mapInfo'
export default {
  name: 'app index page',
  data () {
    return {
    }
  },
  components: {
    DownloadInfo,
    MapInfo
  }
}
</script>

<style scoped>
  div {
   display: flex;
   text-align: center;
  }

 .side-bar {
   width: 20%;
   background-color: #EBEEF5;
   height: 100%;
   /* position: absolute; */
 }
 .map-context {
   height: 100%;
 }
</style>
