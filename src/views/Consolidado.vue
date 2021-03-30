<template>

    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.2/css/all.min.css">

    <div>
      <Header2 />
        <div class="regresar">
            <img src="../assets/arrow-left.png" alt="">
            <h2 class="">Resumen de compras</h2>
        </div>
      <div class="contenedor-general-carrito">

        
         
        <div class="contenedor-tarjetas-curso">
            <div class="tarjeta">
                <div class="img-tarjeta">
                    <img src="../assets/img-curso-carrito.png" alt="">
                </div>
                <div class="info-tarjeta">
                    <div class="contenedor-tarjetas-info">
                        <div class="contenedor-nombre">
                            <h1>Gestión de Envases, Empaques y Embalajes</h1>
                            <h2>Dscto. 25%</h2>
                        </div>
                        <div class="contenedor-precio">
                            <h3>S/ 269.00</h3>
                        </div>

                        
                    </div>
                    <div class="contenedor-eliminar">
                        <a href="">Eliminar</a>
                    </div>
                </div>
            </div>

            <div class="tarjeta">
                <div class="img-tarjeta">
                    <img src="../assets/img-curso-carrito.png" alt="">
                </div>
                <div class="info-tarjeta">
                    <div class="contenedor-tarjetas-info">
                        <div class="contenedor-nombre">
                            <h1>Gestión de Envases, Empaques y Embalajes</h1>
                            <h2>Dscto. 25%</h2>
                        </div>
                        <div class="contenedor-precio">
                            <h3>S/ 269.00</h3>
                        </div>

                        
                    </div>
                    <div class="contenedor-eliminar">
                        <a href="">Eliminar</a>
                    </div>
                </div>
            </div>

            <div class="tarjeta">
                <div class="img-tarjeta">
                    <img src="../assets/img-curso-carrito.png" alt="">
                </div>
                <div class="info-tarjeta">
                    <div class="contenedor-tarjetas-info">
                        <div class="contenedor-nombre">
                            <h1>Gestión de Envases, Empaques y Embalajes</h1>
                            <h2>Dscto. 25%</h2>
                        </div>
                        <div class="contenedor-precio">
                            <h3>S/ 269.00</h3>
                        </div>

                        
                    </div>
                    <div class="contenedor-eliminar">
                        <a href="">Eliminar</a>
                    </div>
                </div>
            </div>

            
            
        </div>

        <div class="contenedor-precio-total">
            <div class="info-cupon">
                  <div class="compra-finalizada">
                      <h3>¡Compra exitosa!</h3>
                      <h1>La boleta o factura solicitada será enviada a tu correo en unos momentos.</h1>
                  </div>

                  <div class="boton-volver">
                    <router-link class="input" to="/miscompras">VOLVER A MIS CURSOS</router-link> 
                  </div>
                </div>
        </div>
        
       
    </div>
      </div>

        
      
   

  
</template>

<script>

import Header2 from '../components/Header2'

export default {
    name: 'Consolidado',
    
    components:{
        Header2
    }
}
</script>

<style scoped>

  /* ESTILOS TARJETAS CURSO */

  .contenedor-general-carrito{
      width: 85%;
      margin: 0 auto;
      display: flex;
      /* align-items: center; */
      justify-content: space-between;
      

  }

  .regresar{
      margin: 0 auto;
      width: 85%;
      height: 100px;
      display: flex;
      align-items: center;
      justify-content: flex-start;
      
  }

  .regresar img{
      margin-right: 20px;
  }

  .contenedor-tarjetas-curso{
      /* background-color: blanchedalmond; */
      width: 60%;
      
      display: flex;
      align-items: center;
      justify-content: center;
      flex-wrap: wrap;

  }

  .tarjeta{
      /* background-color: black; */
      width: 100%;
      height: 150px;
      
      display: flex;
      align-items: center;
      margin-bottom: 20px;
  }

  .info-tarjeta{
      width: 100%;
  }

  .img-tarjeta img{
      margin-right: 20PX;
  }

  .contenedor-nombre h1{
      font-size: 1.3rem;
      text-align: left;
  }

  .contenedor-nombre h2{
      font-size: 1rem;
      text-align: left;
      color: #5640FF;
  }

  .contenedor-tarjetas-info{
      width: 100%;
      display: flex;
      align-items: center;
      justify-content: space-between;
      /* background-color: blanchedalmond; */
  }

  .contenedor-precio h3{
      font-weight: 800;
      font-size: 1.1rem;
  }




  .contenedor-eliminar{
      width: 100%;
      display: flex;
      justify-content: flex-start;
  }

  .contenedor-eliminar a{
      color: #5640FF;
      
  }






  /* CONTENEDOR PRECIO TOTAL + CUPON */

  .contenedor-precio-total{
      width: 40%;
      height: 350px;
      /* background-color: black; */
      display: flex;
      align-items: center;
      justify-content: center;
      margin: 0;
      position: fixed;
      right: 0;
     
  }

  .info-cupon{
      background-color: white;
      width: 80%;
      height: 80%;
      display: flex;
      align-items: center;
      justify-content: center;
      flex-direction: column;
      border-radius: 20px;
       -webkit-box-shadow: 0px 4px 18px -2px rgba(0,0,0,0.29);
        -moz-box-shadow: 0px 4px 18px -2px rgba(0,0,0,0.29);
        box-shadow: 0px 4px 18px -2px rgba(0,0,0,0.29);
  }

  .boton-volver{
      width: 85%;
      height: 50px;
      /* background-color: black; */
      
  }

  .input-cupon{
      width: 100%;
      margin-bottom: 30px;
  }

  .input-cupon input{
      width: 83%;
      height: 50px;
      
  }

  .boton-volver .input{
      width: 100%;
      height: 50px;
      background-color: #5640FF;
      color: white;
      font-weight: 600;
      border: none;
      border-radius: 10px;
      letter-spacing: .2rem;
      display: flex;
      align-items: center;
      justify-content: center;
      text-decoration: none;
      font-size: .8rem;
  }
  

  .compra-finalizada{
      width: 85%;
      display: flex;
      align-items: flex-start;
      justify-content: space-between;
      color: black;
      margin-bottom: 20px;
      flex-direction: column;
      text-align: left;
  }

  .compra-finalizada h1{
      font-size: 1rem;
      margin: 0;
      font-weight: 400;
  }

  .compra-finalizada h3{
      font-size: 1.5rem;
      margin: 0;
      margin-bottom: 10px;
  }


</style>