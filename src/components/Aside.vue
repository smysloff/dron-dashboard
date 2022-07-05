<script setup>
  import { ref } from 'vue'

  let menuVisible = ref(false)

  const toggleMenu = () => menuVisible.value = !menuVisible.value
</script>

<template>
  <aside class="relative flex items-center justify-between px-4 py-2 border-b">
    <div class="flex gap-1">
      <span>Drons</span>
      <span>Dashboard</span>
    </div>

    <nav>
      <div @click="toggleMenu" class="relative z-10 flex items-center justify-center w-8 h-8 bg-white border rounded cursor-pointer">
        <svg v-if="menuVisible" class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12"></path></svg>
        <svg v-else class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16"></path></svg>
      </div>
      <div v-show="menuVisible" class="absolute top-0 right-0 h-screen px-12 bg-white border-l py-14">
        <ul class="flex flex-col gap-2">
          <li>
            <span class="cursor-pointer">Локации</span>
          </li>
          <li>
            <span class="cursor-pointer">Настройки</span>
          </li>
          <li>
            <span class="cursor-pointer">Пользователи</span>
          </li>
        </ul>
      </div>
    </nav>
  </aside>
</template>
