<template>
  <div class="mx-auto max-w-md space-y-4">
    <!-- Header -->
    <div class="py-4 text-center">
      <h1 class="mb-2 text-2xl font-bold text-gray-900">Informasi Pembayaran</h1>
      <p class="text-sm text-gray-600">Pajak Reklame</p>
    </div>

    <!-- Payment Summary -->
    <div class="rounded-xl bg-white shadow-lg">
      <div class="border-b p-4 pb-3">
        <div class="flex items-center justify-between text-lg">
          <span>Detail Pembayaran</span>
        </div>
      </div>
      <div class="space-y-4 p-4">
        <div class="space-y-2">
          <div class="flex justify-between text-sm">
            <span class="text-gray-600">No. SKPD</span>
            <span class="font-mono">1234567890</span>
          </div>
          <div class="flex justify-between text-sm">
            <span class="text-gray-600">Jatuh Tempo</span>
            <span class="font-medium text-red-600">2025-09-30</span>
          </div>
          <hr class="my-2 border-gray-200" />
          <div class="flex items-center justify-between">
            <span class="text-lg font-semibold">Total Pembayaran</span>
            <span class="text-2xl font-bold text-blue-600">Rp 1.500.000</span>
          </div>
        </div>
      </div>
    </div>

    <!-- Payment Method Selection -->
    <div class="rounded-xl bg-white shadow-lg">
      <div class="border-b p-4 pb-3">
        <div class="text-lg">Pilih Metode Pembayaran</div>
      </div>
      <div class="space-y-3 p-4">
        <div class="grid grid-cols-3 gap-2">
          <button
            class="flex h-16 flex-col gap-1 items-center justify-center rounded-lg border bg-blue-600 p-2 text-white">
            <Icon name="material-symbols-light:qr-code" size="1.2em" />
            <span class="text-xs">QRIS</span>
          </button>
          <button class="flex h-16 flex-col gap-1 items-center justify-center rounded-lg border p-2">
            <Icon name="material-symbols-light:account-balance" size="1.2em" />
            <span class="text-xs">Transfer Bank</span>
          </button>
        </div>
      </div>
    </div>

    <!-- Payment Details (contoh: QR aktif) -->
    <div class="rounded-xl bg-white shadow-lg">
      <div class="p-6">
        <div class="space-y-4 text-center">
          <div class="inline-block rounded-lg bg-white p-4 shadow-sm">
            <img src="https://qrcg-free-editor.qr-code-generator.com/main/assets/images/websiteQRCode_noFrame.png"
              alt="QR Code QRIS" class="mx-auto h-48 w-48 object-contain" />
          </div>
          <div class="space-y-2">
            <p class="text-sm text-gray-600">Scan QR Code dengan aplikasi pembayaran</p>
            <button
              class="h-12 w-full rounded-lg bg-blue-600 text-lg font-semibold text-white hover:bg-blue-700">Download
              QRIS</button>
          </div>
        </div>
      </div>
    </div>

    <!-- Action Button -->

    <!-- Footer Info -->
    <div class="pb-4 text-center text-xs text-gray-500">
      <p>Pembayaran akan diverifikasi dalam 1x24 jam</p>
      <p>Hubungi BAPENDA Kepulauan Meranti untuk bantuan</p>
    </div>
  </div>
</template>
