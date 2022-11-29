<template>
  <header>
    <!-- logo -->
    <img src="../assets/img/dc-logo.png"/>
    <nav>
      <ul>
        <li><a href="#">
           Characters
        </a></li>
        <li><a href="#">
           Comics    
        </a></li>
        <li><a href="#">
           Movies 
        </a></li>
        <li><a href="#">
           TV
        </a></li>
        <li><a href="#">
           Games
        </a></li>
        <li><a href="#">
           Collectibles
        </a></li>
        <li><a href="#">
           Videos
        </a></li>
        <li><a href="#">
           Fans
        </a></li>
        <li><a href="#">
           News
        </a></li>
        <li><a href="#">
           Shop
        </a></li>
      </ul>
    </nav>
  </header>
</template>

<script>
export default {
  name: 'HeaderComp',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
header{
  display: flex;
  justify-content: space-between;
  align-items: center;
}
</style>
