<script setup>
definePageMeta({
  layout: false
})
</script>

<template>
  <div class="min-h-dvh bg-slate-200 flex items-center justify-center bg-gray-100">
    <div class="bg-white p-6 shadow-lg w-full h-dvh max-w-sm flex flex-col justify-center gap-6">

      <p class="text-2xl font-semibold text-center text-sky-700">Sign In</p>


      <div class="space-y-4">
        <div>
          <input type="text" class="w-full border rounded-lg border-slate-400 p-2" placeholder="Email">
        </div>
        <div>
          <input type="text" class="w-full border rounded-lg border-slate-400 p-2" placeholder="Password">
        </div>
        <div class="w-full text-left">
          <p class="text-sm font-medium text-right text-sky-700">Lupa Password?</p>
        </div>
        <div>
          <button class="bg-sky-600 w-full py-2 rounded-lg">
            <span class="text-lg font-medium text-sky-50">Login</span>
          </button>
        </div>
        <div>
          <a href="/signup">
            <button class="bg-sky-50 border-sky-600 border w-full py-2 rounded-lg">
              <span class="text-lg font-medium text-sky-700">Daftar</span>
            </button>
          </a>
        </div>
      </div>

    </div>
  </div>
</template>
