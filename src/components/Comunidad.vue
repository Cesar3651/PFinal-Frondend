<template>
  <div class="contenedor-comunidad">
      <div class="contenedor-info-comunidad">
          <img src="../assets/chica.png" alt="">
          <div class="texto-comunidad">
              <h1>Sé parte de la comunidad</h1>
              <p>Programas semi-presenciales para el desarrollo de habilidades de programación a lo largo 
                de todo el Stack tecnológico.
                <br>
                <br>
                Al finalizar sabrás cómo crear una página web y desarrollar la lógica detrás del 
                funcionamiento de una aplicación, así como formar parte de una gran comunidad de 
                desarrolladores.
                </p>
          </div>
      </div>
  </div>
</template>

<script>
export default {

}
</script>

<style>

.contenedor-comunidad{
    width: 100%;
    height: 200px;
    background-color: #3015FD;
    margin-top: 150px;
    color: white;
}

.contenedor-info-comunidad{
    width: 60%;
    margin-left: 8%;
    display: flex;
    align-items: center;
    
}

.contenedor-info-comunidad img{
    position: absolute;
    left: -120px;
    
}

.texto-comunidad{
    width: 60%;
    text-align: left;
    margin-left: 130px;
    margin-bottom: 0;
    font-size: .9rem;
    margin-top: 10px;
}

</style>