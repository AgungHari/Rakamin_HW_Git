# Penjelasan Git dan Perintah Dasar

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