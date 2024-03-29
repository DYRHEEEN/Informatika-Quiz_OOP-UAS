# Informatika-Quiz

## Anggota Kelompok 7
|      Nama Anggota      |      NIM      |
| ---------------------- | ------------- |
|    Danang Nurcahyo     |   312210004   |
|    Ihsan Hadimulya     |   312210047   |
|  Ferdyana Eka Prasetya |   312210121   |
|   Rhendy Diki Nugraha  |   312210150   |
|    M Fauzan Ghifari    |   312210428   |

## Penjelasan
Website Informatika Quiz ini merupakan website yang menyediakan platform bagi Mahasiswa untuk mengasah pengetahuan dalam bidang Informatika. Yang mana didalamnya terdapat berbagai materi dalam bidang Informatika, yang berisi pertanyaan - pertanyaan yang sudah disesuaikan dan jawabannya yang sudah terbukti kebenarannya dan tentunya relevan. Website ini dibuat menggunakan framework python yaitu Django, yang databasenya menggunakan db.sqlite3. 

### Admin
- Dapat melihat daftar Mahasiswa yang mendaftar
- Menambah materi dan pertanyaan untuk ujian atau quiz
- Melihat Materi dan pertanyaan yang sudah dibuat

### Mahasiswa
- Dapat melihat total jumlah quiz yang ada
- Mengerjakan soal quiznya
- Melihat hasil nilai yang didapatkan

## Cara Menggunakan
- Install python versi 3.8.0
- Clone terlebih dahulu repository ini, lalu buat akun superuser atau admin, dengan cara mengetikkan code berikut:
  ```
  py manage.py createsuperuser
  ```
- Jika sudah di clone, buka direktori maka akan ada file requirements.txt. Buka foldernya di CMD, lalu jalankan code berikut:
  ```
  python -m pip install -r requirements.txt
   ```
- Jika penginstall sudah berhasil, untuk menjalankan program, jalankan code berikut :
  ```
  py manage.py migrate
  py manage.py runserver
  ```
- Akan didapatkan sebuah URL yang dapat dibuka di browser, seperti ini :
  ```
  http://127.0.0.1:8000/
  ```
Maka akan tampil dari project Django yang sudah di clone dari repository ini. 

# SELESAI
