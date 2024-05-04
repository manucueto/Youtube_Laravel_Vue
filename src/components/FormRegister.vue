<script setup>
defineProps({
  type: String,
  default: "text",
  validator: (value) => {
    return ["text", "email"].includes(value);
  },
});
</script>

<template>
  <div class="flex items-center justify-center min-h-screen">
    <form action="" class="space-y-5 w-full max-w-md mx-auto">
      <div>
        <label for="name" class="block ">Nombre</label>
        <input
          class="w-full rounded border-green-400 border-2"
          type="text"
          id="name"
          name="name"
          placeholder="Nombre"
        />
      </div>
      <div>
        <label for="lastname" class="block">Apellido</label>
        <input
          type="text"
          class="w-full rounded border-green-400 border-2"
          id="lastname"
          name="lastname"
          placeholder="Apellido"
        />
      </div>

      <div>
        <label for="email" class="block">Email</label>
        <input
          type="email"
          class="w-full rounded border-green-400 border-2"
          id="email"
          name="email"
          placeholder="Email"
        />
      </div>
      <div>
        <label for="password" class="block">Contraseña</label>
        <input
          type="password"
          class="w-full rounded border-green-400 border-2"
          id="password"
          name="password"
          placeholder="Contraseña"
        />
      </div>
      <div>
        <label for="confirm_password" class="block">Confirmar Contraseña</label>
        <input
          type="password"
          class="w-full rounded border-green-400 border-2"
          id="confirm_password"
          name="confirm_password"
          placeholder="Confirmar Contraseña"
        />
      </div>
      <div>
        <button class="w-full bg-green-400 text-white rounded p-2">
          Registrarse
        </button>
      </div>
    </form>
  </div>
</template>

<style></style>
