<template>
  <div>
    <div class="beneficios-titulo"><h2>Beneficios</h2></div>
    <div class="contenedor-card">
        <div class="card">
            <img src="../assets/user.png" alt="">
            <div class="card-info">
                <h2>Aprende de Expertos</h2>
                <p>Aprende directamente de expertos del mercado a través del análisis y solución de problemas de programación. Utilizando los frameworks y herramientas de mayor relevancia dentro del mundo del coding.</p>
            </div>
        </div>
        
        <div class="card">
            <img src="../assets/pc.png" alt="">
            <div class="card-info">
                <h2>Clases Virtuales</h2>
                <p>Aprovecha tu tiempo al máximo en nuestras clases virtuales y participa presencialmente de nuestras hackathones semanales para conocer y participar de la comunidad profesional que liderará la transformación tecnológica del Perú.</p>
            </div>
        </div>

        <div class="card">
            <img src="../assets/box.png" alt="">
            <div class="card-info">
                <h2>Empleabilidad</h2>
                <p>Al finalizar el programa y certificarte a nombre de IDAT, podrás acceder a ofertas 
                    laborales especialmente identificadas para la comunidad PachaQTec, a través de 
                    nuestra plataforma de empleabilidad IDAT JOB.</p>
            </div>
        </div>
    </div>

  </div>
</template>

<script>
export default {

}
</script>

<style scoped>
    .beneficios-titulo{
        margin: 0 auto;
        margin-top: 150px;
        width: 90%;
        text-align: left;
        margin-left: 8%;
        /* background-color: blue; */
    }

    .contenedor-card{
        width: 50%;
        /* height: 160px; */
        
        margin-left: 8%;
        display: flex;
        align-items: center;
        justify-content: center;
        flex-direction: column;
        margin-bottom: 50px;
        
    }

    .card img{
        width: 60px;
        height: 60px;
        margin-right: 40px;
    }

    .card-info{
        width: 70%;
    }

    .card{
        background-color: #F2F3F5;
        border-radius: 10px;
        width: 100%;
        height: 160px;
        text-align: left;
        display: flex;
        align-items: center;
        justify-content: center;
        /* background-color: black; */
        margin-bottom: 20px;
    }

    h2{
        font-size: 1rem;
    }
    p{
        font-size: .8rem;
        margin-right: 0;
    }


</style>