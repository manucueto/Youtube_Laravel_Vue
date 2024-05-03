<script>
export default {
  name: 'Header',
}
</script>

<template>
  <div class="flex justify-between fixed top-0 left-0 right-0 gradiante p-3 gradiente items-center ">
    <h1 class="text-3xl text-white ml-5">ComTube</h1>
    <div class="separado">
        <a href="#" class="text-white">Login</a>
        <a href="#" class="text-white">Registrarse</a>
    </div>
  </div>  
  
</template>

<style>
    .gradiente{
        /* Permalink - use to edit and share this gradient: https://colorzilla.com/gradient-editor/#55db74+0,2be5d9+51,55db74+100 */
        background: linear-gradient(to right,  #55db74 0%,#2be5d9 51%,#55db74 100%); /* W3C, IE10+, FF16+, Chrome26+, Opera12+, Safari7+ */

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