<template>
  <h1 class="border-b-2 pb-2 mb-2 text-lg">Form Pajak Reklame</h1>
  <div class="bg-white p-4 rounded-lg shadow-md">
    <h2 class="text-lg font-semibold mb-4">Objek Pajak</h2>
    <form class="space-y-4">
      <!-- NOPD -->
      <div>
        <label for="nopd" class="block text-sm font-medium text-gray-700">NOPD</label>
        <select class="w-full border rounded-lg px-3 py-2">
          <option>Pilih salah satu opsi</option>
        </select>
      </div>

      <!-- Nama Objek Pajak -->
      <div>
        <label for="nama_objek" class="block text-sm font-medium text-gray-700">Nama Objek Pajak</label>
        <input type="text" id="nama_objek" name="nama_objek" value="Reklame"
          class="mt-1 block w-full rounded-lg border-gray-300 shadow-sm focus:border-blue-500 focus:ring focus:ring-blue-200 px-3 py-2" />
      </div>

      <!-- NPWPD -->
      <div>
        <label for="npwpd" class="block text-sm font-medium text-gray-700">NPWPD</label>
        <input type="text" id="npwpd" name="npwpd" value="10.13.05.01.000034"
          class="mt-1 block w-full rounded-lg border-gray-300 shadow-sm focus:border-blue-500 focus:ring focus:ring-blue-200 px-3 py-2" />
      </div>

      <!-- Nama Wajib Pajak -->
      <div>
        <label for="nama_wp" class="block text-sm font-medium text-gray-700">Nama Wajib Pajak</label>
        <input type="text" id="nama_wp" name="nama_wp" value="ICA PUTRI YULINDA"
          class="mt-1 block w-full rounded-lg border-gray-300 shadow-sm focus:border-blue-500 focus:ring focus:ring-blue-200 px-3 py-2" />
      </div>

      <!-- Sub Jenis Pajak -->
      <div>
        <label for="sub_jenis" class="block text-sm font-medium text-gray-700">Sub Jenis Pajak</label>
        <input type="text" id="sub_jenis" name="sub_jenis" value="Reklame Videotron/Megatron"
          class="mt-1 block w-full rounded-lg border-gray-300 shadow-sm focus:border-blue-500 focus:ring focus:ring-blue-200 px-3 py-2" />
      </div>

      <!-- Alamat -->
      <div>
        <label for="alamat" class="block text-sm font-medium text-gray-700">Alamat</label>
        <textarea id="alamat" name="alamat" rows="2"
          class="mt-1 block w-full rounded-lg border-gray-300 shadow-sm focus:border-blue-500 focus:ring focus:ring-blue-200"></textarea>
      </div>

      <!-- Keterangan -->
      <div>
        <label for="keterangan" class="block text-sm font-medium text-gray-700">Keterangan</label>
        <textarea id="keterangan" name="keterangan" rows="2"
          class="mt-1 block w-full rounded-lg border-gray-300 shadow-sm focus:border-blue-500 focus:ring focus:ring-blue-200"></textarea>
      </div>
    </form>
  </div>

  <div class="bg-white p-4 rounded-lg shadow-md mt-6">
    <h2 class="text-lg font-semibold mb-4">Rincian</h2>
    <form class="space-y-4">

      <!-- Masa Pajak -->
      <div>
        <label for="bulan" class="block text-sm font-medium text-gray-700">Bulan</label>
        <select id="bulan" name="bulan"
          class="mt-1 block w-full rounded-lg border-gray-300 shadow-sm focus:border-blue-500 focus:ring focus:ring-blue-200">
          <option>Pilih salah satu opsi</option>
          <option>Januari</option>
          <option>Februari</option>
          <option>Maret</option>
          <!-- ... dst -->
        </select>
      </div>

      <div>
        <label for="tahun" class="block text-sm font-medium text-gray-700">Tahun</label>
        <input type="text" id="tahun" name="tahun" value="2025"
          class="mt-1 block w-full rounded-lg border-gray-300 shadow-sm focus:border-blue-500 focus:ring focus:ring-blue-200" />
      </div>

      <!-- Posisi Reklames -->
       <div>
        <label for="tahun" class="block text-sm font-medium text-gray-700">Posisi Reklame</label>
        <input type="text" id="tahun" name="tahun" value="Menempel Tanpa Penerangan"
          class="mt-1 block w-full rounded-lg border-gray-300 shadow-sm focus:border-blue-500 focus:ring focus:ring-blue-200" />
      </div>

      <div>
        <label for="kelas" class="block text-sm font-medium text-gray-700">Kelas</label>
        <select id="kelas" name="kelas"
          class="mt-1 block w-full rounded-lg border-gray-300 shadow-sm focus:border-blue-500 focus:ring focus:ring-blue-200">
          <option>Pilih salah satu opsi</option>
        </select>
      </div>

      <div>
        <label for="jalan" class="block text-sm font-medium text-gray-700">Jalan</label>
        <select id="jalan" name="jalan"
          class="mt-1 block w-full rounded-lg border-gray-300 shadow-sm focus:border-blue-500 focus:ring focus:ring-blue-200">
          <option>Pilih salah satu opsi</option>
        </select>
      </div>

      <!-- Luas -->
      <h3 class="text-md font-semibold mt-4">Luas</h3>
      <div class="flex items-center gap-2">
        <div class="flex-1">
          <label for="panjang" class="block text-sm font-medium text-gray-700">Panjang</label>
          <input type="number" id="panjang" name="panjang" placeholder="m"
            class="mt-1 block w-full rounded-lg border-gray-300 shadow-sm focus:border-blue-500 focus:ring focus:ring-blue-200" />
        </div>
        <div class="flex-1">
          <label for="lebar" class="block text-sm font-medium text-gray-700">Lebar</label>
          <input type="number" id="lebar" name="lebar" placeholder="m"
            class="mt-1 block w-full rounded-lg border-gray-300 shadow-sm focus:border-blue-500 focus:ring focus:ring-blue-200" />
        </div>
      </div>

      <div>
        <label for="luas" class="block text-sm font-medium text-gray-700">Luas</label>
        <input type="number" id="luas" name="luas" placeholder="m2"
          class="mt-1 block w-full rounded-lg border-gray-300 shadow-sm focus:border-blue-500 focus:ring focus:ring-blue-200" />
      </div>

      <div>
        <label for="tinggi" class="block text-sm font-medium text-gray-700">Ketinggian Reklame</label>
        <input type="number" id="tinggi" name="tinggi" placeholder="m"
          class="mt-1 block w-full rounded-lg border-gray-300 shadow-sm focus:border-blue-500 focus:ring focus:ring-blue-200" />
      </div>

      <div>
        <label for="jumlah" class="block text-sm font-medium text-gray-700">Jumlah</label>
        <input type="number" id="jumlah" name="jumlah" placeholder="buah"
          class="mt-1 block w-full rounded-lg border-gray-300 shadow-sm focus:border-blue-500 focus:ring focus:ring-blue-200" />
      </div>

      <!-- Dua sisi -->
      <div class="flex items-center gap-2">
        <input id="dua_sisi" name="dua_sisi" type="checkbox"
          class="h-4 w-4 text-blue-600 border-gray-300 rounded focus:ring-blue-500" />
        <label for="dua_sisi" class="text-sm text-gray-700">Dua sisi?</label>
      </div>

      <!-- Masa Berlaku -->
      <h3 class="text-md font-semibold mt-4">Masa Berlaku</h3>

      <div>
        <label for="masa" class="block text-sm font-medium text-gray-700">Waktu penyelenggaraan</label>
        <input type="number" id="masa" name="masa" placeholder="bulan"
          class="mt-1 block w-full rounded-lg border-gray-300 shadow-sm focus:border-blue-500 focus:ring focus:ring-blue-200" />
      </div>

      <div>
        <label for="mulai" class="block text-sm font-medium text-gray-700">Mulai</label>
        <input type="date" id="mulai" name="mulai" value="2025-09-13"
          class="mt-1 block w-full rounded-lg border-gray-300 shadow-sm focus:border-blue-500 focus:ring focus:ring-blue-200" />
      </div>

      <div>
        <label for="hingga" class="block text-sm font-medium text-gray-700">Berlaku hingga</label>
        <input type="date" id="hingga" name="hingga"
          class="mt-1 block w-full rounded-lg border-gray-300 shadow-sm focus:border-blue-500 focus:ring focus:ring-blue-200" />
      </div>

      <!-- Penyelenggara -->
      <div>
        <label for="penyelenggara" class="block text-sm font-medium text-gray-700">Penyelenggara</label>
        <select id="penyelenggara" name="penyelenggara"
          class="mt-1 block w-full rounded-lg border-gray-300 shadow-sm focus:border-blue-500 focus:ring focus:ring-blue-200">
          <option>Profesi</option>
          <option>Usaha</option>
          <option>Panglong Ar/Kilang S</option>
          <option>Sarang Burung Walet</option>
          <option>Produk Khusus</option>
          <option>Produk Rokok</option>
          <option>Indoor</option>
        </select>
      </div>

      <div class="mt-2 space-y-2">
        <p class="text-sm font-medium text-gray-700">Produk Khusus:</p>
        <div class="flex items-center gap-2">
          <input id="rokok" name="produk_khusus" type="checkbox"
            class="h-4 w-4 text-blue-600 border-gray-300 rounded focus:ring-blue-500" />
          <label for="rokok" class="text-sm text-gray-700">Produk Rokok</label>
        </div>
        <div class="flex items-center gap-2">
          <input id="indoor" name="produk_khusus" type="checkbox"
            class="h-4 w-4 text-blue-600 border-gray-300 rounded focus:ring-blue-500" />
          <label for="indoor" class="text-sm text-gray-700">Indoor</label>
        </div>
      </div>
    </form>
  </div>

  <!-- Nilai -->
  <div class="bg-white p-4 rounded-lg shadow-md mt-6">
    <h2 class="text-lg font-semibold mb-4">Nilai</h2>
    <form class="space-y-4">

      <!-- Tarif Pajak -->
      <div>
        <label for="tarif" class="block text-sm font-medium text-gray-700">Tarif Pajak</label>
        <div class="flex items-center gap-2">
          <input type="number" id="tarif" name="tarif" placeholder="0"
            class="mt-1 block w-full rounded-lg border-gray-300 shadow-sm focus:border-blue-500 focus:ring focus:ring-blue-200" />
          <span class="text-gray-600">%</span>
        </div>
      </div>

      <!-- Nilai Pajak -->
      <div>
        <label for="nilai_pajak" class="block text-sm font-medium text-gray-700">Nilai Pajak</label>
        <div class="flex items-center gap-2">
          <span class="text-gray-600">Rp.</span>
          <input type="number" id="nilai_pajak" name="nilai_pajak" placeholder="0"
            class="mt-1 block flex-1 rounded-lg border-gray-300 shadow-sm focus:border-blue-500 focus:ring focus:ring-blue-200" />
        </div>
      </div>

      <!-- Tanggal Penetapan -->
      <div>
        <label for="tanggal_penetapan" class="block text-sm font-medium text-gray-700">Tanggal Penetapan</label>
        <input type="date" id="tanggal_penetapan" name="tanggal_penetapan" value="2025-09-13"
          class="mt-1 block w-full rounded-lg border-gray-300 shadow-sm focus:border-blue-500 focus:ring focus:ring-blue-200" />
      </div>

      <!-- Ditandatangani Oleh -->
      <div>
        <label for="ditandatangani" class="block text-sm font-medium text-gray-700">Ditandatangani Oleh</label>
        <select id="ditandatangani" name="ditandatangani"
          class="mt-1 block w-full rounded-lg border-gray-300 shadow-sm focus:border-blue-500 focus:ring focus:ring-blue-200">
          <option>Pilih salah satu opsi</option>
          <option>Kepala Dinas</option>
          <option>Sekretaris</option>
          <option>Bendahara</option>
        </select>
      </div>
    </form>
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


  <!-- Submit -->
  <div class="pt-2">
    <button type="submit"
      class="w-full rounded-lg bg-blue-600 text-white py-2 hover:bg-blue-700 focus:outline-none focus:ring-2 focus:ring-blue-400">
      Simpan
    </button>
  </div>




</template>