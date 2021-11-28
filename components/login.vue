<template>
    <div class="template">
        <div class="container1">
                <h1>Login</h1>
                <form>
                    <div class="input-field">
                        <label for="name" >Nome:</label>
                        <input type="text" name="name" >
                    </div>
                    <div class="input-field">
                        <label for="password" >Senha:</label>
                        <input type="text" name="password">
                    </div>
                    <div class="center">
                      <nuxt-link to="/inicio">
                        <button>Login</button>
                      </nuxt-link>  
                    </div>
                </form>
        </div>
    </div>
</template>

<script>



</script>

<style scoped>
*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

.template{
   background-image: url("~/static/img/fundologin.jpg");
   background-size: cover;
   display: flex;
   justify-content: center;
   align-items: center;
   height: 100vh;
   width: 205vh;
}
h1{
    font-size: 35px;
    color: white;
    text-align: center;
    margin: 20px;
}

.container1{
    width: 350px;
    background-color: rgba(0, 0, 0, 0.5);
    border-radius: 15%;
    box-shadow: 1px 2px 10px black, 3px 6px 20px black;
    padding: 50px 20px;
}

input{
    width: 100%;
    height: 45px;
    background:transparent;
    border:none;
    outline: none;
    border-bottom: 1px solid white;
    color:white;
}

label{
    color: white;
    font-size: 15px;
}

.input-field{
    position:relative;
    margin-bottom: 20px;
}

input:focus{
    border-bottom: 2px solid #26a96a;
    box-shadow: 0 1px 0 0 #26a96a;
}

button{
    padding: 15px 50px;
    margin: 20px;
    background-color: white;
    color:black;
    border:none;
    border-radius: 12px;
}

button:hover{
    background-color: #26a96a;
    color: black;
}

a{
    color: white;
    text-align: center;
}

.center{
    text-align: center;
}

.error{
    border:3px solid red;
}

.error-color{
    color: red;
}

.type__p{
 font-size: 35px;
 color: red;
 font-family: Arial, Helvetica, sans-serif;
 text-align: center;
}
</style>