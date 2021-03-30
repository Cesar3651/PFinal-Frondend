<template>
<div>
      <!-- <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/materialize/1.0.0/css/materialize.min.css"> -->
    
    <main class="contenedor">
        <div class="contenedor-tarjetas">
            <div class="tarjeta">

                <img src="../assets/cursos/front.png" alt="">

                <div class="contenedor-links">
                    <div class="tarjeta-titulo">
                        <h1>Desarrollo Front-End</h1>
                    </div>

                    <div class="tarjeta-links">
                        <button>Agregar al Carrito</button>
                        <h2>Ver mas</h2>
                    </div>
                </div>
            </div>

            <div class="tarjeta">

                <img src="../assets/cursos/back.png" alt="">

                <div class="contenedor-links">
                    <div class="tarjeta-titulo">
                        <h1>Desarrollo Back-End</h1>
                    </div>

                    <div class="tarjeta-links">
                        <button>Agregar al Carrito</button>
                        <h2>Ver mas</h2>
                    </div>
                </div>
            </div>

            <div class="tarjeta">

                <img src="../assets/cursos/mobile.png" alt="">

                <div class="contenedor-links">
                    <div class="tarjeta-titulo">
                        <h1>Desarrollo de Aplicativos Moviles</h1>
                    </div>

                    <div class="tarjeta-links">
                        <button>Agregar al Carrito</button>
                        <h2>Ver mas</h2>
                    </div>
                </div>
            </div>

            <div class="tarjeta">

                <img src="../assets/cursos/ux.png" alt="">

                <div class="contenedor-links">
                    <div class="tarjeta-titulo">
                        <h1>Disenio de Experiencia de Usuario</h1>
                    </div>

                    <div class="tarjeta-links">
                        <button>Agregar al Carrito</button>
                        <h2>Ver mas</h2>
                    </div>
                </div>
            </div>

            <div class="tarjeta">

                <img src="../assets/cursos/juegos.png" alt="">

                <div class="contenedor-links">
                    <div class="tarjeta-titulo">
                        <h1>Desarrollo de Videojuegos</h1>
                    </div>

                    <div class="tarjeta-links">
                        <button>Agregar al Carrito</button>
                        <h2>Ver mas</h2>
                    </div>
                </div>
            </div>

            <div class="tarjeta">

                <img src="../assets/cursos/digital.png" alt="">

                <div class="contenedor-links">
                    <div class="tarjeta-titulo">
                        <h1>Marketing Digital</h1>
                    </div>

                    <div class="tarjeta-links">
                        <button>Agregar al Carrito</button>
                        <h2>Ver mas</h2>
                    </div>
                </div>
            </div>

            <div class="tarjeta">

                <img src="../assets/cursos/data.png" alt="">

                <div class="contenedor-links">
                    <div class="tarjeta-titulo">
                        <h1>Data Analytics</h1>
                    </div>

                    <div class="tarjeta-links">
                        <button>Agregar al Carrito</button>
                        <h2>Ver mas</h2>
                    </div>
                </div>
            </div>

            <div class="tarjeta">

                <img src="../assets/cursos/frontA.png" alt="">

                <div class="contenedor-links">
                    <div class="tarjeta-titulo">
                        <h1>Desarrollo Front-End Avanzado</h1>
                    </div>

                    <div class="tarjeta-links">
                        <button>Agregar al Carrito</button>
                        <h2>Ver mas</h2>
                    </div>
                </div>
            </div>

        </div>

    </main>

</div>
</template>

<script>
export default {

}
</script>

<style scoped>

.contenedor-tarjetas{
    
    width: 50%;
    display: flex;
    align-items: center;
    margin-left: 8%;
    margin-top: 50px;
    flex-wrap: wrap;
    
}


.tarjeta{
    /* background-color: black; */
    width: 344px;
    height: 320px;
    display: flex;
    align-items: center;
    justify-content: space-evenly;
    margin-right: 20px;
    margin-bottom: 20px;
    flex-direction: column;
    position: relative;
}

.tarjeta::after {
    content: '';
    position: absolute;
    background: rgb(5,5,5);
    background: linear-gradient(155deg, rgba(5,5,5,0) 0%, rgba(0,11,38,1) 100%);
    border-radius: 10px;
    
    width: 100%;
    height: 100%;
    
}


.contenedor-links{
    position: absolute; 
    margin-top: 150px;
    z-index: 1;
    
}

.tarjeta-titulo{    
    margin: 0 auto;
    width: 260px;
    color: white;
    font-size: .6rem;
    text-align: left;
}

.tarjeta-links{
    width: 260px;
    color: white;
    display: flex;
    justify-content: space-between;
    align-items: center;
    font-size: .6rem;
}

.tarjeta-links button{
    height: 40px;
    background-color: white;
    color: black;
    border: none;
    border-radius: 5px;
}

</style>