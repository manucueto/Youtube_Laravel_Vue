<script setup>
    defineProps({
        type: String,
        default: 'text',
        validator: (value) => {
            return ['text', 'email'].includes(value)
        }
    })
</script>

<template>
    <div class="flex items-center justify-center min-h-screen">

        <form action="" class=" space-y-5">
        <div >
            <label for="name">Nombre</label>
            <input class=" mx-3 rounded  border-green-400 border-2" type="text" id="name" name="name" placeholder="Nombre">
        </div>
        <div >
            <label for="lastname">Apellido</label>
            <input type="text" class=" mx-3 rounded  border-green-400 border-2"  id="lastname" name="lastname" placeholder="Apellido">
        </div>

        <div >
            <label for="email">Email</label>
            <input type="email" class=" mx-3 rounded  border-green-400 border-2"  id="email" name="email" placeholder="Email">
        </div>
        <div >
            <label for="password">Contraseña</label>
            <input type="password" class=" mx-3 rounded  border-green-400 border-2"  id="password" name="password" placeholder="Contraseña">
        </div>
        <div >
            <label for="confirm_password">Confirmar Contraseña</label>
            <input type="password" class=" mx-3 rounded  border-green-400 border-2"  id="confirm_password" name="confirm_password" placeholder="Confirmar Contraseña">
        </div>
        </form>
    </div>
    
</template>

<style>

</style>