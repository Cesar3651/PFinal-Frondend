<template>
  <div>
      <header >
          <nav class="container">
              <ul >
                  <li><img class="logo" src="../assets/logop.png" alt=""></li>

                  <div class="icons">
                      <li><img src="../assets/carrito.png" alt=""></li>
                  <li><img src="../assets/menu.png" alt=""></li>
                  </div>
                  
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
    height: 80px;
    background-color: black;
    
}


ul{
    
    height: 80px;
    display: flex;
    align-items: center;
    justify-content: space-between;
    background-color: black;
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
    
}

</style>