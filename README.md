# Penjadwalan Kuliah dengan Algoritma Genetika (UTS) - Kelompok 6

Proyek Kelompok Algoritma Genetika: optimasi penjadwalan kuliah (University Course
Timetabling Problem). Repositori ini berisi implementasi AG dasar untuk tahap UTS,
dengan data jadwal prodi Teknik Informatika yang disederhanakan
(20 kelas, 8 dosen, 5 ruang, 25 slot waktu).

## Cara menjalankan

1. Buka file `Penjadwalan_Kuliah_UTS_AG.ipynb` di repositori ini, lalu klik tombol
   **Open in Colab**.
2. Di Colab, klik **Runtime > Run all**. Sel pertama otomatis mengambil data dari
   repositori ini, jadi tidak perlu mengunggah file apa pun.
3. Hasil (jadwal terbaik dalam CSV/Excel, grafik konvergensi, ringkasan run)
   disimpan di folder `hasil/`.

## Isi repositori

| File / folder | Keterangan |
|---|---|
| `Penjadwalan_Kuliah_UTS_AG.ipynb` | Kode utama (AG, fitness, operator, eksperimen) |
| `data_penjadwalan.xlsx - matakuliah.csv` | Data mata kuliah |
| `data_penjadwalan.xlsx - dosen.csv` | Data dosen |
| `data_penjadwalan.xlsx - ruang.csv` | Data ruang |
| `data_penjadwalan.xlsx - slot_waktu.csv` | Data slot waktu |
| `konflik_dpna.csv` | Data konflik peserta antar kelas |
| `hasil/` | Keluaran program (jadwal, grafik konvergensi, ringkasan, validasi) |

## Pengaturan AG (default)

Populasi 100, 100 generasi, probabilitas crossover 0,8, probabilitas mutasi 0,05,
elitisme 2 individu, seleksi turnamen, crossover uniform. Pengujian dilakukan
10 kali run dengan seed berbeda.

## Anggota kelompok

| No | Nama | Peran | Tanggung jawab utama |
|---|---|---|---|
| 1 | Meilisa Timbung | Analis Eksperimen | Bagian 4 laporan, pembuatan PPT |
| 2 | Septi Septia | Programmer Fitness & Validasi | Bagian 3 dan 7 laporan, pembuatan PPT |
| 3 | Vira Nairul Azkia | Ketua / Analis Masalah | Bagian 1 dan 2 laporan, implementasi kode, penyusunan data (CSV), pembuatan PPT |
| 4 | Yana Nurlufi Khomariah | Programmer Inti AG | Bagian 5 dan 8 laporan, implementasi kode, penyusunan data (CSV) |
| 5 | Daniel Fransisco | Penulis & Presenter | Bagian 6 laporan |
