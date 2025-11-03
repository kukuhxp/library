# TESTING

Testing adalah proses menguji dan memeriksa apakah program berjalan sesuai dengan yang diharapkan. Artinya, apakah kode yang dibuat menghasilkan output yang benar dan bebas dari kesalahan.

Tujuan:

1. Menemukan bug atau error sebelum program digunakan pengguna.
2. Memastikan fungsi berjalan sesuai spesifikasi.
3. Menjaga kualitas kode agar mudah dikembangkan atau diperbarui.
4. Menjamin keamanan dan keandalan software.

Jenis:

1. Unit Testing
Menguji bagian terkecil dari program untuk memastikan masing-masing berfungsi dengan benar. Contohnya, mengecek apakah fungsi tambah(a, b) benar-benar mengembalikan a + b.

2. Integration Testing
Menguji apakah beberapa modul atau fungsi yang berbeda bisa bekerja sama dengan baik. Contohnya, modul login dan modul database dapat berkomunikasi tanpa error.

3. System Testing
Menguji seluruh sistem secara keseluruhan untuk melihat apakah sesuai dengan kebutuhan awal.

4. Acceptance Testing (UAT)
Pengujian oleh pengguna akhir untuk memastikan program sesuai harapan mereka.

5. Regression Testing
Dijalankan setelah ada perubahan kode, untuk memastikan tidak ada fitur lama yang rusak akibat update.

## Feature Flag

Feature flag atau feature toggle adalah mekanisme untuk mengaktifkan atau menonaktifkan fitur aplikasi secara dinamis tanpa perlu mengubah atau redeploy kode. Dengan feature flag, developer bisa mengontrol perilaku aplikasi lewat konfigurasi.

Contoh:

Bayangkan kamu punya aplikasi dan sedang mengembangkan fitur Mode Gelap (Dark Mode). Daripada langsung merilis fitur itu ke semua pengguna, kamu bisa menyembunyikannya di balik feature flag.

Jenis:

1. Release Flag
Untuk mengontrol perilisan fitur baru secara bertahap, hanya beberapa pengguna saja yang dapat melihat fitur baru.

2. Experiment Flag
Untuk menguji versi fitur yang berbeda dan melihat hasil performanya.

3. Ops Flag
Untuk mengaktifkan/menonaktifkan komponen penting saat darurat. Contohnya, mematikan sistem pembayaran saat maintenance, agar pengguna tidak mengalami kerugian saat sistem diperbaiki.

4. Permission Flag
Untuk memberi akses fitur tertentu hanya ke user tertentu.

## Bug

Bug adalah kesalahan, cacat, atau kelemahan dalam kode program yang menyebabkan program tidak berjalan sesuai harapan.

## Debugging

Debugging adalah proses mencari, menemukan, dan memperbaiki kesalahan dalam kode program agar program dapat berjalan dengan benar.

## Remote Debugging

Remote debugging adalah proses men-debug yang berjalan di komputer lain dari jarak jauh, biasanya melalui jaringan lokal atau internet.

## Handling Programs

Handling Program adalah cara program menangani situasi atau kondisi tertentu, terutama errors, input tak terduga, atau peristiwa khusus selama program berjalan.