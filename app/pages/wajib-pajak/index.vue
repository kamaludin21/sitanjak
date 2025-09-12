<template>
 <!-- Informasi -->
    <div>
      <h2 class="text-lg font-semibold text-gray-800 mb-4">Informasi</h2>
      <div class="grid grid-cols-1 md:grid-cols-2 gap-4">
        <!-- Provinsi -->
        <div>
          <label class="block text-sm font-medium text-gray-700 mb-1">Provinsi*</label>
          <select class="w-full border rounded-lg px-3 py-2">
            <option>RIAU</option>
          </select>
        </div>

        <!-- Kabupaten/Kota -->
        <div>
          <label class="block text-sm font-medium text-gray-700 mb-1">Kabupaten/Kota*</label>
          <select class="w-full border rounded-lg px-3 py-2">
            <option>Pilih salah satu opsi</option>
          </select>
        </div>

        <!-- Tgl Daftar -->
        <div>
          <label class="block text-sm font-medium text-gray-700 mb-1">Tgl Daftar*</label>
          <input type="text" value="09/12/2025 02:22:24 PM" class="w-full border rounded-lg px-3 py-2" readonly>
        </div>

        <!-- Jenis Wajib Pajak -->
        <div>
          <label class="block text-sm font-medium text-gray-700 mb-1">Jenis Wajib Pajak*</label>
          <select class="w-full border rounded-lg px-3 py-2">
            <option>Pilih salah satu opsi</option>
          </select>
        </div>
      </div>
    </div>

    <!-- Wajib Pajak -->
    <div>
      <h2 class="text-lg font-semibold text-gray-800 mb-4 mt-6">Wajib Pajak</h2>
      <div class="grid grid-cols-1 md:grid-cols-2 gap-4">
        <!-- NIK -->
        <div>
          <label class="block text-sm font-medium text-gray-700 mb-1">NIK*</label>
          <input type="text" placeholder="NIK/Kitas/Kita" class="w-full border rounded-lg px-3 py-2">
        </div>

        <!-- Nama -->
        <div>
          <label class="block text-sm font-medium text-gray-700 mb-1">Nama*</label>
          <input type="text" class="w-full border rounded-lg px-3 py-2">
        </div>

        <!-- No. Hp -->
        <div>
          <label class="block text-sm font-medium text-gray-700 mb-1">No. Hp</label>
          <input type="text" class="w-full border rounded-lg px-3 py-2">
        </div>

        <!-- Email -->
        <div>
          <label class="block text-sm font-medium text-gray-700 mb-1">Email</label>
          <input type="email" class="w-full border rounded-lg px-3 py-2">
        </div>

        <!-- Alamat -->
        <div class="md:col-span-2">
          <label class="block text-sm font-medium text-gray-700 mb-1">Alamat</label>
          <textarea class="w-full border rounded-lg px-3 py-2" rows="3"></textarea>
        </div>

        <!-- Jabatan -->
        <div class="md:col-span-2">
          <label class="block text-sm font-medium text-gray-700 mb-1">Jabatan</label>
          <input type="text" class="w-full border rounded-lg px-3 py-2">
        </div>
      </div>
    </div>

    <!-- Tombol -->
    <div class="flex justify-end mt-6">
      <button type="submit" class="bg-indigo-600 text-white px-5 py-2 rounded-lg shadow hover:bg-indigo-700">
        Simpan
      </button>
    </div>
</template>