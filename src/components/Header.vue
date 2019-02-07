<template>
    <header id="header">
        <div class="hdr">
            <img src="../assets/logo.png" class="hdr__logo" alt="Logo da Matchbox">  
            <div class="hdr__whitebox">
            <h1 class="hdr__whitebox__title">ranking</h1>
            </div>
        </div>
    </header>
</template>

<script>
export default {

}
</script>

<style lang="scss">
#header {
    @include mainContainer(342px);
    margin-top: 50px;

  .hdr {
    &__logo {
      margin-bottom: 25px;
      display: block;
    }

    &__whitebox {
      background-color: #fff;
      max-width: 342px;
      height: 52px;
      border-radius: 3px;
      display: flex;
      justify-content: center;
      align-items: center;

      &__title {
        color: #272727;
        font-weight: bold;
        font-size: 28px;
      }
    }
  }
}
</style>
