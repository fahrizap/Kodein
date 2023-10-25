## 1.1 Latar Belakang

Membuat Aplikasi mobile legends

## 1.2. Deksripsi Teknologi Informasi

bla bla bla

## 1.3. Branding

bla bla bla

## 2. User Story

Pengguna bisa | Tingkat penting
---|---
Mengirim pesan diskusi | ⭐⭐⭐⭐⭐
---|---
Menonton video materi | ⭐⭐⭐⭐⭐
|
Mengikuti satu sama lain | ⭐⭐⭐⭐
|
Membalas pesan | ⭐⭐⭐⭐⭐
|
Mengirim pesan pribadi satu sama lain | ⭐⭐⭐⭐

## 3. Struktur Data
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
  PENGGUNA ||--o{ PESAN_DISKUSI : membuat
  PENGGUNA ||--o{ BERTEMAN : mengikuti
  PENGGUNA ||--o{ PENGGUNA_LAIN : pesan_pribadi
  PENGGUNA ||--o{ GRUP : membuat
  PENGGUNA ||--o{ MATERI_VIDEO : membuat
  PESAN_DISKUSI {
    int id_pesan
    int id_pesan_yang_dibalas
    int id_pengguna 
    string username_pengguna_lain
    string isi_pesan
    string pesan_balasan
    int poin
    string gambar_pesan
    int jumlah_like
    datetime waktu_publikasi
    datetime waktu_pesan_balasan
  }
  PENGGUNA_LAIN {
    int id_pengguna_lain
    int username_pengguna_lain
  }
  PENGGUNA_LAIN ||--o{ PESAN_DISKUSI : membalas
  PENGGUNA_LAIN ||--o{ BERTEMAN : mengikuti
  PENGGUNA_LAIN ||--o{ PENGGUNA : pesan_pribadi
  PENGGUNA_LAIN ||--o{ GRUP : bergabung
  PENGGUNA_LAIN ||--o{ MATERI_VIDEO : menonton
  GRUP {
    int id_grup
    string nama_grup
    string ikon_grup
    datetime waktu_grup_dibuat
  }
  MATERI_VIDEO {
    int id_video
    string judul_video
    string deskripsi_video
    int jumlah_penonton
    int jumlah_like
    string isi_video
    datetime waktu_materi_dipublikasi
  }
```

## 4. Arsitektur Sistem
```mermaid
erDiagram

  Client||--o{TypeScript :oo
  Client||--o{Css : oo
  Client||--o{ReactNative : oo
  Client||--o{Server : oo
  Server||--o{NodeJs : oo
  Server||--o{Database : oo
  Database||--o{MySql : oo
  MySql||--o{Server :oo
```
## 5. Teknologi, Library, dan Framework

bla bla bla

## 6. Desain User Experience dan User Interface

![Contoh](https://github.com/fahrizap/Kodein/blob/main/Screenshot%202023-10-25%20091942.png?raw=true)

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
