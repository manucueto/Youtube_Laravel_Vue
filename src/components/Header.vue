<script>

</script>

<template>
  <div class="flex justify-between fixed top-0 left-0 right-0 p-3 gradiente items-center ">
    <h1 class="text-3xl text-white ml-5">Com<span class="font-bold">Tube</span> </h1>
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
        position: fixed; 
        top: 0; 
        right: 0; 
        left: 0; 
        width: 100%; 
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