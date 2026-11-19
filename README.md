# WargaHubP04 (`id.antasari.p04.wargahub`)

Praktikum 04 — UX, RecyclerView, Fragment, dan Navigasi (Pemrograman Mobile).

## Identitas
- **Nama:** Zakiah Khairani
- **NIM:** 240104040161
- **Kelas:** TI 24 B
- **Mata Kuliah:** Praktikum Pemrograman Mobile (PTI23043)

## Lingkungan & Perangkat Uji
- **Android Studio:** Android Studio Rabbit 2 | 2026.2.2 Patch 1
- **Android Gradle Plugin:** 9.5.1
- **SDK:** `compileSdk = 37`, `targetSdk = 37`, `minSdk = 26`
- **Emulator Utama:** Pixel 8 (Android 14.0, API 34)
- **Emulator TalkBack:** Pixel 8 (Android 17.0, API 37.2)

## Cara Membuka dan Menjalankan (Run)
1. Buka Android Studio lalu pilih **Open** dan arahkan ke folder `WargaHubP04`.
2. Tunggu proses sinkronisasi Gradle selesai (`BUILD SUCCESSFUL`).
3. Pilih perangkat virtual (emulator) pada *Device Manager* lalu klik tombol **Run** (`Shift + F10`).

## Ringkasan Fitur & Batas Data Contoh
- Menggunakan satu *Activity* (`MainActivity`) dan tiga *Fragment* (`HomeFragment`, `ListFragment`, `DetailFragment`) yang dihubungkan melalui Navigation Component (`nav_graph.xml`) dan argumen ID bertipe `Long`.
- Menampilkan 15 laporan latihan menggunakan `RecyclerView`, `ListAdapter`, dan `DiffUtil` dengan dukungan mode daftar kosong serta tombol pemulihan data contoh.
- **Batas data contoh:** Seluruh data berasal dari objek `LaporanContoh` di kode (bukan database, API, atau penyimpanan permanen), sehingga data contoh akan muncul kembali setiap aplikasi dibuka ulang.