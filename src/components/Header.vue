<script>
export default {
  name: 'Header',
}
</script>

<template>
  <div class="container gradiente ">
    <h1 class="">ComTube</h1>
    <div class="separado">
        <a href="#">Login</a>
        <a href="#">Registrarse</a>
    </div>
  </div>  
  
</template>

<style>
    .gradiente{
        /* Permalink - use to edit and share this gradient: https://colorzilla.com/gradient-editor/#ffffff+0,2be5d9+51,55db74+100 */
        background: linear-gradient(to right, #ffffff 0%,#2be5d9 51%,#55db74 100%); /* W3C, IE10+, FF16+, Chrome26+, Opera12+, Safari7+ */
        position: fixed; /* Añade esta línea */
        top: 0; /* Añade esta línea */
        right: 0; /* Añade esta línea */
        left: 0; /* Añade esta línea */
        width: 100%; /* Añade esta línea */
        margin: 0;
        padding: 0.8rem 0.8rem;
        font-weight: 400;    }
    .container{
        display: flex;
        justify-content: space-between;
        align-items: center;
        margin: 0 auto;
    }
    .separado{
        display: flex;
        gap: 1rem;
        margin-right: 2rem; 
    }
    
</style>