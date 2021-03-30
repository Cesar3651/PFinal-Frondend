<template>
    <div >

        <div class="contenedor-login">
            <!-- <img src="../assets/login.png" alt=""> -->
            <div class="banner">
                <div class="banner-info">
                    <div class="info-logo">
                        <img src="../assets/logop.png" alt="">
                    </div>

                    <div class="info-titulo">
                        <h1>¡Explota todo tu potencial tecnológico!</h1>
                        <h2>Con nuestros programas de especialización</h2>
                    </div>

                    <div class="info-respaldo">
                        <img src="../assets/respaldo.png" alt="">
                    </div>

                </div>
                
            </div>
            <div class="login">
                <div class="login-contenedor">
                    <div class="login-links">
                        <router-link class="log" to="/login">Iniciar Sesion</router-link> 
                        <router-link class="reg" to="/register">Registrarse</router-link> 
                    </div>

                    <div class="login-inputs">
                        <div class="input">
                            <h2>Nombres y Apellidos</h2>
                            <input class="form-datos" type="text" placeholder="Jhon Miguel">
                        </div>

                        <div class="input">
                            <h2>Correo Electronico</h2>
                            <input class="form-datos" type="text" placeholder="example@gmail.com">
                        </div>

                        <div class="input">
                            <h2>Contraseña</h2>
                            <input class="form-datos" type="password" placeholder="Password">
                        </div>

                        <div class="input">
                            <h2>Repite contraseña</h2>
                            <input class="form-datos" type="password" placeholder="Password">
                        </div>

                        
                        <div class="form-checkbox">
                            <input  type="checkbox">
                            <p class="text-checkbox"> Acepto <b><a href="">Terminos y Condiciones</a></b></p>
                        </div>
                        
                    </div>

                    

                    <div class="login-boton">
                        <button class="boton-postular">Ingresar</button>
                        <a href="">¿Olvidaste tu contraseña?</a>
                    </div>
                </div>
            </div>
        </div>
        <!-- <Header2 /> -->
        
    </div>
</template>

<script>



export default {
    name: 'Login',

    components:{
    
    }
}
</script>

<style scoped>

.contenedor-login{
    width: 100%;
    height: 100vh;
    position: relative;
    background-image: url("../assets/login.png");
    background-position: center;
    background-size: cover;
    background-repeat: no-repeat;

    display: flex;
}


.banner{
   
    width: 65%;
    height: 100vh;
   
}

.banner-info{
    padding: 40px;
    width: 90%;
    height: 100%;
}



.info-logo{
    width: 100%;
    height: 10%;
    display: flex;
    justify-content: flex-start;
    

}

.info-logo img{
    
    height: 40px;
}

.info-titulo{
    width: 100%;
    height: 70%;
    display: flex;
    justify-content: center;
    align-items: flex-end;
    flex-direction: column;
    padding: 0;
}

.info-titulo h1{
    width: 70%;
    color: white;
    margin: 0;
    text-align: right;
    margin-bottom: 20px;
    font-size: 2.5rem;
    font-weight: 800;
}
.info-titulo h2{
    width: 30%;
    color: white;
    margin: 0;
    text-align: right;
    font-size: 1rem;
}


.info-respaldo{
    width: 100%;
    height: 10%;
    display: flex;
    justify-content: flex-start;
    align-items: center;
}

.info-respaldo img{
    height: 80px;
}

/* LOGIN */

.login{
    width: 35%;
    height: 100vh;
    background-color: white;
    
}

.login-contenedor{
   
    width: 100%;
    height: 100%;
    background-color: white;
    
}
   

.login-links{
    width: 100%;
    height: 10%;
    display: flex;
    align-items: center;
    justify-content: space-evenly;
    border-bottom: 1px solid rgb(199, 199, 199);

}

.login-links a{
    text-decoration: none;
    font-weight: 800;
    height: 100%;
    width: 200px;
    
    display: flex;
    align-items: center;
    justify-content: center;
    color: black;
    /* background-color: black; */
    
}

.login-links .reg{
    border-bottom: 6px solid black;
}

.login-inputs{
    width: 100%;
    height: 70%;
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
}

.login-inputs input{
    margin-bottom: 20px;
    height: 40px;
}

.login-inputs h2{
    font-size: .8rem;
    margin: 0;
    text-align: left;
    margin-bottom: 10px;
    
}

.input{
    width: 80%;
}

.input input{
    color: rgb(0, 0, 0);
}


.login-boton{
    width: 100%;
    height: 10%;
    display: flex;
    align-items: center;
    justify-content: space-evenly;
    flex-direction: column;
    
}

.login-boton button{
    width: 80%;
    height: 50px;
    background-color: #5640FF;
    border: none;
    color: white;
    border-radius: 10px;
    font-weight: 800;
    margin-bottom: 20px;
    
}

.login-boton a{
    font-size: .8rem;

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
  width: 80%;
 
  /* background-color: blueviolet; */
  display: flex;
  align-items: center;
  
}

.form-checkbox input{
    margin: 0;
    margin-right: 20px;
}

.text-checkbox{
  font-size: .8rem;
  margin: 0;
}

.text-checkbox a {
    margin: 0;
    color: black;
    font-weight: 700;
}

.log .reg{
    color: black;
}
</style>