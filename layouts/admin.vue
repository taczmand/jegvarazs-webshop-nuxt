<template>
  <div class="flex min-h-screen">
    <aside class="w-64 bg-gray-900 text-white p-4">
      <h2 class="text-xl font-bold mb-4">Admin Panel</h2>
      <ul>
        <li><NuxtLink to="/admin/dashboard">Dashboard</NuxtLink></li>
      </ul>
    </aside>
    <main class="flex-1 p-6 bg-gray-100">
      <NuxtPage />
    </main>
  </div>
</template>
