<template>
  <div>
    <Header />
    <Rank />
  </div>
</template>

<script>
import Header from './components/Header.vue'
import Rank from './components/Rank.vue'

export default {
  components: { Header, Rank }
}
</script>

<style lang="scss">

* {
  margin: 0px;
  padding: 0px;
  font-family: 'Montserrat', sans-serif;
}

html {
  
  display: flex;
  justify-content: center;
}

body {
  background-color: #453995;
  display: flex;
  align-items: center;
  height: 100%;
}

</style>
