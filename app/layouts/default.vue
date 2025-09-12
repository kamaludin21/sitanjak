<script setup>
import { useRoute, useRouter } from 'vue-router'
import { computed } from 'vue'

const route = useRoute()
const router = useRouter()

// Mapping judul halaman
const titles = {
  index: 'Beranda',
  pelaporan: 'Pelaporan',
  transaksi: 'Transaksi',
  profil: 'Profil'
}

// judul header dinamis
const pageTitle = computed(() => titles[route.name] || 'Sitanjak')

// status aktif navbar
const isActive = (name) => route.name === name

// navigasi halaman
const goTo = (name) => {
  router.push({ name })
}
</script>

<template>
  <div class="min-h-dvh bg-slate-200 flex items-center justify-center bg-gray-100">
    <div class="bg-white shadow-lg w-full h-dvh max-w-sm flex flex-col">
      <header class="bg-blue-600 text-white p-4 shadow-md flex items-center justify-between">
        <h1 class="text-lg font-semibold">{{ pageTitle }}</h1>
      </header>
      <main class="flex-1 overflow-y-auto p-4 bg-gray-50 relative">
        <slot />
      </main>

      <!-- Bottom Navbar -->
      <nav class="bg-white border-t shadow-inner flex justify-around py-2">
        <button class="flex flex-col items-center" :class="isActive('index') ? 'text-blue-600' : 'text-gray-500'"
          @click="goTo('index')">
          <Icon name="material-symbols-light:home" size="1.5em" />
          <span class="text-xs">Beranda</span>
        </button>

        <button class="flex flex-col items-center" :class="isActive('pelaporan') ? 'text-blue-600' : 'text-gray-500'"
          @click="goTo('pelaporan')">
          <Icon name="material-symbols-light:add-notes" size="1.5em" />
          <span class="text-xs">Pelaporan</span>
        </button>

        <button class="flex flex-col items-center" :class="isActive('transaksi') ? 'text-blue-600' : 'text-gray-500'"
          @click="goTo('transaksi')">
          <Icon name="material-symbols-light:receipt-long" size="1.5em" />
          <span class="text-xs">Transaksi</span>
        </button>

        <button class="flex flex-col items-center" :class="isActive('profil') ? 'text-blue-600' : 'text-gray-500'"
          @click="goTo('profil')">
          <Icon name="material-symbols-light:account-circle" size="1.5em" />
          <span class="text-xs">Profil</span>
        </button>
      </nav>
    </div>
  </div>
</template>
