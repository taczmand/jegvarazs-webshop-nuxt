<template>
  <div>
    <h1 class="text-2xl font-bold mb-4">Admin Login</h1>
    <form class="flex flex-col gap-4">
      <input type="text" placeholder="Username" class="border p-2" />
      <input type="password" placeholder="Password" class="border p-2" />
      <button class="bg-blue-600 text-white p-2">Login</button>
    </form>
  </div>
</template>

<script setup lang="ts">
definePageMeta({
  layout: 'admin',
  ssr: false, // fontos, hogy admin oldalak SPA-k legyenek
})
</script>
