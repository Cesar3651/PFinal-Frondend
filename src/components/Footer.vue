<template>
  <div>
      <header >
          <nav class="container">
              <ul >
                  <li><img class="logo" src="../assets/respaldo.png" alt=""></li>

                  <!-- <div class="icons">
                      <li><img src="../assets/carrito.png" alt=""></li>
                  <li><img src="../assets/menu.png" alt=""></li>
                  </div> -->
                  
              </ul>
          </nav>

        
      </header>

      
  </div>
</template>

<script>
export default {

}
</script>

<style scoped>



header{
    margin: 0;
    width: 100%;
    height: 100px;
    background-color: black;
    display: flex;
    align-items: center;
    
}

nav{
    /* width: 100%; */
    display: flex;
    align-items: center;
}

ul{
    width: 100%;
    display: flex;
    align-items: center;
    justify-content: flex-start;
    /* background-color: coral; */
    height: 80px;
    
    /* background-color: black; */
    margin: 0;
}

li{
    list-style: none;
    
}

.icons{
    width: 6%;
    height: 50px;
    display: flex;
    justify-content: space-between;
    align-items: center;
    
    
}

.logo{
    width: 160px;
    margin-top: 10px;
    
}


.container{
    margin: 0 auto;
    width: 90%;
    height: 50px;
    margin-bottom: 0;
    
}

</style>