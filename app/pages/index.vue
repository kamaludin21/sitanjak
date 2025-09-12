<script setup>

</script>

<template>
  <div class="grid gap-4">
    <h1 class=" border-b-2 text-lg font-medium text-slate-600">Data Pajak</h1>
    <div class="grid gap-4">  
      <div class="p-2 bg-slate-200 rounded-lg border border-slate-300 flex justify-between items-center">
        <p class="text-slate-700 font-medium text-base">Wajib Pajak</p>
        <NuxtLink to="/wajib-pajak">
        <button class="bg-orange-600 text-white rounded-full border-white border flex items-center p-0.5">
          <Icon name="material-symbols-light:chevron-right" size="1.6em" />
        </button>
        </NuxtLink>
      </div>
      <div class="p-2 bg-slate-200 rounded-lg border border-slate-300 flex justify-between items-center">
        <p class="text-slate-700 font-medium text-base">Objek Pajak</p>
        <NuxtLink to="/objek-pajak">
          <button @click="goTo('index')"
            class="bg-orange-600 text-white rounded-full border-white border flex items-center p-0.5">
            <Icon name="material-symbols-light:chevron-right" size="1.6em" />
          </button>
        </NuxtLink>
      </div>
    </div>

    <h1 class=" border-b-2 text-lg font-medium text-slate-600">Pelaporan</h1>
    <!-- Sementara 3 Jenis Pajak -->
    <div class="grid gap-4">
      <div class="p-2 bg-slate-200 rounded-lg border border-slate-300  flex justify-between items-center">
        <div>
          <p class="text-slate-700 font-medium text-base">PBJT</p>
          <p class="text-sm font-medium line-clamp-1 text-slate-500">Pajak Barang dan Jasa Tertentu</p>
        </div>
        <button class="bg-orange-600 text-white rounded-full border-white border flex items-center p-0.5">
          <Icon name="material-symbols-light:chevron-right" size="1.6em" />
        </button>
      </div>
      <div class="p-2 bg-slate-200 rounded-lg border border-slate-300  flex justify-between items-center">
        <div>
          <p class="text-slate-700 font-medium text-base">BPHTB</p>
          <p class="text-sm font-medium line-clamp-1 text-slate-500">Bea Perolehan Hak atas Tanah dan Bangunan</p>
        </div>
        <button class="bg-orange-600 text-white rounded-full border-white border flex items-center p-0.5">
          <Icon name="material-symbols-light:chevron-right" size="1.6em" />
        </button>
      </div>
      <div class="p-2 bg-slate-200 rounded-lg border border-slate-300  flex justify-between items-center">
        <div>
          <p class="text-slate-700 font-medium text-base">Pajak Walet</p>
          <p class="text-sm font-medium line-clamp-1 text-slate-500">Pajak Sarang Burung Walet</p>
        </div>
        <button class="bg-orange-600 text-white rounded-full border-white border flex items-center p-0.5">
          <Icon name="material-symbols-light:chevron-right" size="1.6em" />
        </button>
      </div>
    </div>

  </div>
</template>