# TESTING

## Handling Programs

Handling Program adalah cara program menangani situasi atau kondisi tertentu, terutama kesalahan (error), input tak terduga, atau peristiwa khusus selama program berjalan.

## Unit Testing

Unit Testing adalah proses menguji bagian terkecil dari kode program secara terpisah (biasanya fungsi atau metode) untuk memastikan bahwa fungsi tersebut bekerja sesuai harapan.

## Feature Flag

Feature Flag (atau disebut juga Feature Toggle) adalah mekanisme untuk mengaktifkan atau menonaktifkan fitur aplikasi secara dinamis tanpa perlu mengubah atau redeploy kode. Dengan feature flag, developer bisa mengontrol perilaku aplikasi lewat konfigurasi (biasanya di server atau dashboard).

Bayangkan kamu punya aplikasi dan sedang mengembangkan fitur Mode Gelap (Dark Mode). Daripada langsung merilis fitur itu ke semua pengguna, kamu bisa menyembunyikannya di balik feature flag.

Jenis Feature Flag

1. Release flag
Untuk mengontrol perilisan fitur baru secara bertahap.
Contoh: hanya 10% pengguna yang melihat fitur baru.

2. Experiment flag (A/B testing)
Untuk menguji versi fitur yang berbeda dan melihat hasil performanya.

3. Ops flag (Operational)
Untuk mengaktifkan/menonaktifkan komponen penting saat darurat.
Contoh: mematikan sistem pembayaran saat maintenance.

4. Permission flag
Untuk memberi akses fitur tertentu hanya ke user tertentu.

## Debugging

Debugging adalah proses mencari, menemukan, dan memperbaiki kesalahan (bug) dalam kode program agar program dapat berjalan dengan benar.

## Compiling

Compiling adalah proses mengubah seluruh kode sumber (yang ditulis dalam bahasa pemrograman tingkat tinggi seperti C, C++, atau Java) menjadi kode mesin (bahasa biner) yang bisa dijalankan oleh komputer.