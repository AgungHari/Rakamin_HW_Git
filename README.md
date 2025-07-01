[![banner1](rakaminacademy_cover.jpg)](https://www.rakamin.com/)

# Rakamin Homework : Dasar Version Control & Git

## Deskripsi

Repositori ini berisi rangkaian materi dan homework selama seminggu Bootcamp di Rakamin Academy. Setiap minggu dilengkapi modul pembelajaran (PDF) dan tugas untuk memperkuat pemahaman konsep.

<img src="https://user-images.githubusercontent.com/74038190/212284100-561aa473-3905-4a80-b561-0d28506553ee.gif" width="900">

## Ringkasan Minggu ini (Week 7)
- Memahami git untuk kolaborasi
- Belajar perintah dasar git
- Membuat repository dan melakukan commit

## 🗂️ Struktur Repository

```
/Git-Homework
│
├── git                                            #Modul
├── Git_workflow_management                        #Modul 2
├── git log --online.txt                           #file_tugas
├── file.txt                                       #file_tugas2
└── README.md
```

## ⚠️ Disclaimer

Materi dan tugas dalam repositori ini adalah milik resmi Rakamin Academy. Semua konten digunakan hanya untuk tujuan referensi dan pembelajaran pribadi, bukan untuk klaim kepemilikan.

## Acknowledgements

```
Mantap
```

## Penjelasan Git dan Perintah Dasar

## Apa itu Git dan fungsinya dalam kolaborasi?

Git adalah sistem kontrol versi terdistribusi yang membantu tim melacak riwayat perubahan kode secara efisien. Dengan Git, setiap anggota tim bisa bekerja paralel, membuat cabang (branch) untuk fitur atau perbaikan, dan menggabungkan (merge) perubahan tanpa takut kehilangan data atau menimpa kode satu sama lain.

## Tiga Perintah Dasar Git dan Fungsinya

1. **git init**  
   Menginisialisasi repository Git baru di direktori kerja saat ini.  
   ```
   git init
   ```
2. **git add <file>**
    Memindahkan perubahan (file baru atau file yang diubah) ke staging area
    agar siap di-commit.
    ```
    git add README.md
    ```
3. **git commit -m "pesan commit"**
    Menyimpan snapshot perubahan dari staging area ke dalam riwayat Git
    dengan pesan deskriptif.
    ```
    git commit -m "mantap README.md"
    ```