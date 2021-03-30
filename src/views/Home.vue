<template>
  <div>
    <Header />
    <div class="img-header"><img src="../assets/header-img.png" alt="">
    </div>
    
    <div class="texto-header">
      <h1 class="header-titulo">¡Explota todo tu potencial tecnológico!</h1>
      <p class="header-texto">Con nuestros programas de especialización</p>
    </div>

    <div class="contenedor-general-telefono">
      <div class="img-mobile">
        <img src="../assets/mobile.png" alt="">
        <form class="form-celular" action="">
            <p class="text-dscto">Postula y obtén un 10% de descuento en el programa</p>
            <input class="form-datos" type="text" placeholder="NOMBRE">
            <input class="form-datos" type="text" placeholder="CELULAR">
            <input class="form-datos" type="text" placeholder="CORREO">
            <input class="form-datos" type="text" placeholder="PROGRAMA">
            <div class="form-checkbox">
              <input  type="checkbox">
                <p class="text-checkbox">
                  Acepto las politicas de privacidad.
                </p>
            </div>
            <button class="boton-postular">Quiero Postular</button>
        </form>
      </div>

      <div class="whatsapp-icon">
        <img src="../assets/whatsapp.png" alt="">
      </div>

      
    </div>

    <div class="footer-header">
      <img src="../assets/idat.png" alt="">
      <img src="../assets/flecha.png" alt="">
    </div>

    

    <Main />
    <Comunidad />
    <Beneficios />
    <Footer />

    

  </div>
  
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'
import Header from '../components/Header'
import Main from '../components/Main'
import Comunidad from '../components/Comunidad'
import Beneficios from '../components/Beneficios'
import Footer from '../components/Footer'

export default {
  name: 'Home',
  components: {
    Header,
    Main,
    Comunidad,
    Beneficios,
    Footer
    // HelloWorld
  }
}
</script>

<style scoped>


img{
  width: 100%;
  
}

.texto-header{
  
  width: 50%;
  position: absolute;
  top: 260px;
  left: 8%;
  display: flex;
  color: white;
  font-size: 2rem;
  text-align: left;
  flex-direction: column;
  /* background-color: blanchedalmond; */
}

.header-titulo{
  margin: 0;
}

.header-texto{
  font-size: 1.5rem;
  
}


/* FORMULARIO CELULAR */

.img-mobile img{
  width: 470px;
  position: fixed;
  right: 200px;
  top: 100px;
}

.form-celular{
  width: 250px;
  height: 600px;
  position: fixed;
  right: 310px;
  top: 180px;
  display: flex;
  align-items: center;
  justify-content: space-evenly;
  flex-direction: column;
}

.text-dscto{
  font-size: 1.2rem;
  font-weight: 600;
}


.form-datos{
  width: 100%;
  height: 40px;
  font-size: .8rem;
  text-align: center;
  color: rgb(162, 162, 162);
  border: 1px solid rgb(167, 167, 167);
  border-radius: 8px;
  outline: none;
}

.form-checkbox{
  width: 100%;
  /* background-color: blueviolet; */
  display: flex;
  align-items: center;
  justify-content: space-evenly;
  flex-direction: row;
  
  
}

.text-checkbox{
  font-size: .8rem;
}

.boton-postular{
  width: 100%;
  height: 50px;
  background-color: #5640FF;
  border: none;
  color: white;
  border-radius: 10px;
}



.contenedor-general-telefono{
  display: flex;
  align-items: center;
  justify-content: space-evenly;
  /* position: fixed; */
}

.whatsapp-icon{
  position: fixed;
  width: 60px;
  height: 60px;
  right: 100px;
  top: 80%;
  margin-left: 1600px;
}

.whatsapp-icon img{
  width: 60px;
  height: 60px;
  margin: 0;
}

.footer-header{
  width: 40%;
  display: flex;
  justify-content: space-between;
  margin-left: 8%;
  margin-top: 30px;
}

.footer-header img{
  width: 60px;
}

.footer-header img:nth-child(1){
  width: 230px;
}



/* MAIN */

</style>
