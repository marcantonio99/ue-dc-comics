<template>
  <header>
    <!-- logo -->
    <img src="../assets/img/dc-logo.png"/>
    <nav>
      <ul>
        <li><a href="#">
           CHARACTERS
        </a></li>
        <li><a href="#">
           COMICS    
        </a></li>
        <li><a href="#">
           MOVIES
        </a></li>
        <li><a href="#">
           TV
        </a></li>
        <li><a href="#">
           GAMES
        </a></li>
        <li><a href="#">
           COLLECTIBLES
        </a></li>
        <li><a href="#">
           VIDEOS
        </a></li>
        <li><a href="#">
           FANS
        </a></li>
        <li><a href="#">
           NEWS
        </a></li>
        <li><a href="#">
           SHOP
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
  padding: 20px;
  margin: 0 auto;
  width: 80%;

  ul{
   display: flex;
   gap: 10px;
  }

  .active{
   border-bottom: 2px solid #0282f9;
  }
}
</style>
