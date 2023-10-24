## 1.1 Latar Belakang

Membuat Aplikasi mobile legends

## 1.2. Deksripsi Teknologi Informasi

bla bla bla

## 1.3. Branding

bla bla bla

## 2. User Story

bla | bla | bla | bla
---|---|---|---
bla | bla | bla | ⭐⭐⭐⭐⭐

## 3. Struktur Data

Cara membuat aneka macam bentuk grafik menggunakan mermaid.js bisa lihat di [https://mermaid.js.org/syntax/entityRelationshipDiagram.html](https://mermaid.js.org/syntax/entityRelationshipDiagram.html) 

```mermaid
erDiagram
  PENGGUNA {
    int id_pengguna
    string username
    string email
    string password
    string nama_lengkap
    int poin
    int koin
  }
  MATERI_VIDEO
    string judul_video
    string deskripsi_video
    int waktu_publikasi
    int id_pengguna_pengunggah_video
    mp4 isi materi
    int jumlah_like
    int jumlah_penonton
  }
  PENGGUNA ||--o{ PESAN_DISKUSI : membuat
  PENGGUNA ||--o{ GRUP_DISKUSI : membuat
  PESAN_DISKUSI {
    int id_pesan
    int id_pesan_yang_dibalas
    int id_pengguna 
    int username_pengguna_lain
    string isi_pesan
    string pesan_balasan
    datetime waktu_publikasi_pesan
    datetime waktu_balas_pesan
    jpg isi_pesan_gambar
    int poin
    int jumlah_like
  }
  PENGGUNA ||--o{ PENGIKUT : memiliki
  PENGGUNA ||--o{ PENGIKUT : mengikuti
  PENGIKUT {
    int id_pengguna
    int id_pengguna_yang_mengikuti
  }
  PENGGUNA_LAIN ||--o{ PESAN_DISKUSI : membalas
  PENGGUNA_LAIN ||--o{ GRUP_DISKUSI : bergabung
  PENGGUNA_LAIN {
    int id_pengguna_lain
    int username_pengguna_lain
  }
  GRUP_DISKUSI{
    string nama_grup
    jpg ikon_grup
  }

```

## 4. Arsitektur Sistem

Masih pake mermaid.js juga bisa lihat flowchart di [https://mermaid.js.org/syntax/flowchart.html](https://mermaid.js.org/syntax/flowchart.html)

## 5. Teknologi, Library, dan Framework

bla bla bla

## 6. Desain User Experience dan User Interface

Bisa load image 
![Contoh](https://fastly.picsum.photos/id/318/536/354.jpg?hmac=Ixy-wle80nudIR_cmnF1iY2y6rMUH7_9sk-BP1fTpM8)

## 7. Demonstrasi Video

Link youtube nya

## 8. Bagaimana mesin komputasi dan sistem operasi berperan dalam produk teknologi informasimu ?

Link youtube nya di detik jawaban ini

## 9. Bagaimana algoritma, struktur data, dan bahasa pemrograman berperan dalam produk teknologi informasimu ?

Link youtube nya di detik jawaban ini

## 10. Bagaimana metode pengembangan perangkat lunak / Software Development Life Cycle berperan dalam produk teknologi informasimu ?

Link youtube nya di detik jawaban ini

## 11. Bagaimana database / sistem basis data berperan dalam produk teknologi informasimu ?

Link youtube nya di detik jawaban ini
