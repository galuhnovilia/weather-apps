<template>
  <div class="home">
    <!-- <img class="homepageLogo" src ="https://www.iosicongallery.com/icons/weather-2017-06-19/512.png"/> -->
    <SearchBar/>
    <DayForecastTab/>
    <Weather/>
  </div>
</template>

<script>
import Weather from '@/components/Weather.vue'
import SearchBar from '@/components/SearchBar.vue'
import DayForecastTab from '@/components/DayForecastTab.vue'

export default {
  name: 'home',
  components: {
    Weather,
    SearchBar,
    DayForecastTab
  },
  mounted(){
  }
}
</script>
<style scoped lang="scss">
.homepageLogo {
  padding-top: 1%;
  width: 20%;
}
</style>

