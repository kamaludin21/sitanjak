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

    <!-- Lokasi -->
    <div class="bg-white p-4 rounded-lg shadow-md mt-6">
      <h2 class="text-lg font-semibold mb-4">Lokasi</h2>
      <form class="space-y-4">

        <!-- Map Container -->
        <div>
          <label class="block text-sm font-medium text-gray-700">Location</label>
          <div id="map"
            class="mt-2 w-full h-48 rounded-lg border border-gray-300 bg-gray-100 flex items-center justify-center text-gray-500">
            [Map Container]
          </div>
        </div>

        <!-- Default Lokasi -->
        <div>
          <button type="button"
            class="rounded-lg bg-blue-600 text-white px-4 py-2 hover:bg-blue-700 focus:outline-none focus:ring-2 focus:ring-blue-400">
            Default Lokasi
          </button>
        </div>

        <!-- Latitude -->
        <div>
          <label for="latitude" class="block text-sm font-medium text-gray-700">Latitude</label>
          <input type="text" id="latitude" name="latitude" value="1.0009065773546375"
            class="mt-1 block w-full rounded-lg border-gray-300 shadow-sm focus:border-blue-500 focus:ring focus:ring-blue-200" />
        </div>

        <!-- Longitude -->
        <div>
          <label for="longitude" class="block text-sm font-medium text-gray-700">Longitude</label>
          <input type="text" id="longitude" name="longitude" value="102.72542953491212"
            class="mt-1 block w-full rounded-lg border-gray-300 shadow-sm focus:border-blue-500 focus:ring focus:ring-blue-200" />
        </div>

      </form>
    </div>

    <!-- Lampiran -->
    <div class="bg-white p-4 rounded-lg shadow-md mt-6">
      <h2 class="text-lg font-semibold mb-4">Lampiran</h2>
      <form class="space-y-4">

        <!-- Foto Objek Pajak -->
        <div>
          <label for="foto" class="block text-sm font-medium text-gray-700">
            Foto objek pajak*
          </label>
          <input type="file" id="foto" name="foto" accept="image/*" class="mt-1 block w-full text-sm text-gray-700 file:mr-3 file:py-2 file:px-4
                    file:rounded-lg file:border-0
                    file:text-sm file:font-semibold
                    file:bg-blue-600 file:text-white
                    hover:file:bg-blue-700" />
          <p class="mt-1 text-xs text-gray-500">Ukuran maksimal: 10 MB.</p>
        </div>

        <!-- Submit -->
        <div class="pt-2">
          <button type="submit"
            class="w-full rounded-lg bg-blue-600 text-white py-2 hover:bg-blue-700 focus:outline-none focus:ring-2 focus:ring-blue-400">
            Upload
          </button>
        </div>
      </form>
    </div>



    <!-- Submit -->
    <div class="pt-2">
      <button type="submit"
        class="w-full rounded-lg bg-blue-600 text-white py-2 hover:bg-blue-700 focus:outline-none focus:ring-2 focus:ring-blue-400">
        Simpan
      </button>
    </div>
  </div>

</template>