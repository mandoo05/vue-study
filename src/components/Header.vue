<template>
  <nav
    class="flex justify-between gap-6 p-4 bg-gray-200 text-blue-700 font-semibold"
  >
    <RouterLink to="/" custom v-slot="{ navigate }">
      <a @click="navigate" class="inline-block">Home</a>
    </RouterLink>

    <RouterLink to="/about" custom v-slot="{ navigate }">
      <a @click="navigate" class="inline-block">About</a>
    </RouterLink>

    <RouterLink to="/contact" custom v-slot="{ navigate }">
      <a @click="navigate" class="inline-block">Contact</a>
    </RouterLink>
  </nav>
</template>
