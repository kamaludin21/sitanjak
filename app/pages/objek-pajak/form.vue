<template>
  <div class="space-y-4">
    <h2 class="text-lg font-semibold text-gray-800">Data Pajak</h2>

    <!-- Jenis Objek Pajak -->
    <div>
      <label class="block text-sm font-medium text-gray-700 mb-1">Jenis Objek Pajak*</label>
      <select class="w-full border rounded-lg px-3 py-2">
        <option>Pilih salah satu opsi</option>
      </select>
    </div>

    <!-- Jenis Pajak -->
    <div>
      <label class="block text-sm font-medium text-gray-700 mb-1">Jenis Pajak*</label>
      <select class="w-full border rounded-lg px-3 py-2">
        <option>Pilih salah satu opsi</option>
      </select>
    </div>

    <!-- Sub Jenis Pajak -->
    <div>
      <label class="block text-sm font-medium text-gray-700 mb-1">Sub Jenis Pajak*</label>
      <select class="w-full border rounded-lg px-3 py-2">
        <option>Pilih salah satu opsi</option>
      </select>
    </div>

    <!-- Rincian -->
    <div>
      <label class="block text-sm font-medium text-gray-700 mb-1">Rincian (Kode Rekening)*</label>
      <select class="w-full border rounded-lg px-3 py-2">
        <option>Pilih salah satu opsi</option>
      </select>
    </div>

    <!-- Informasi -->
    <div>
      <h2 class="text-lg font-semibold text-gray-800 mb-4">Informasi</h2>
      <div class="space-y-4">
        <div>
          <label class="block text-sm font-medium text-gray-700 mb-1">Provinsi*</label>
          <select class="w-full border rounded-lg px-3 py-2">
            <option>RIAU</option>
          </select>
        </div>

        <div>
          <label class="block text-sm font-medium text-gray-700 mb-1">Kabupaten/Kota*</label>
          <select class="w-full border rounded-lg px-3 py-2">
            <option>KAB. KEPULAUAN MERANTI</option>
          </select>
        </div>

        <div>
          <label class="block text-sm font-medium text-gray-700 mb-1">Kecamatan*</label>
          <select class="w-full border rounded-lg px-3 py-2">
            <option>Pilih salah satu opsi</option>
          </select>
        </div>

        <div>
          <label class="block text-sm font-medium text-gray-700 mb-1">Desa/Kelurahan*</label>
          <select class="w-full border rounded-lg px-3 py-2">
            <option>Pilih salah satu opsi</option>
          </select>
        </div>

        <div>
          <label class="block text-sm font-medium text-gray-700 mb-1">Nama Usaha*</label>
          <input type="text" class="w-full border rounded-lg px-3 py-2">
        </div>

        <div>
          <label class="block text-sm font-medium text-gray-700 mb-1">Alamat</label>
          <textarea rows="2" class="w-full border rounded-lg px-3 py-2"></textarea>
        </div>

        <div>
          <label class="block text-sm font-medium text-gray-700 mb-1">NOP PBB</label>
          <input type="text" class="w-full border rounded-lg px-3 py-2">
        </div>

        <div>
          <label class="block text-sm font-medium text-gray-700 mb-1">Penanggung Jawab</label>
          <input type="text" class="w-full border rounded-lg px-3 py-2">
        </div>

        <div>
          <label class="block text-sm font-medium text-gray-700 mb-1">No. Hp Penanggung Jawab</label>
          <input type="text" class="w-full border rounded-lg px-3 py-2">
        </div>
      </div>
    </div>

    <!-- Tombol -->
    <div class="flex justify-end">
      <button type="submit" class="bg-indigo-600 text-white px-5 py-2 rounded-lg shadow hover:bg-indigo-700">
        Simpan
      </button>
    </div>
  </div>

</template>