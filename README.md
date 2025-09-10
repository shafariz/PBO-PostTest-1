# Shafa Rizqi Nur Wahidah - 2409116041

# Manajemen Taman Hiburan

## Deskripsi Program
Program Manajemen Taman Hiburan adalah aplikasi berbasis Java yang dirancang untuk membantu pengelola taman hiburan dalam mencatat dan mengelola daftar wahana yang ada.  Dengan program ini, pengelola dapat menambahkan wahana baru, melihat daftar wahana, mengubah informasi wahana, dan menghapus wahana yang sudah tidak ada.  Semua data disimpan secara sederhana menggunakan ArrayList, sehingga mudah dipahami dan cocok untuk pembelajaran dasar pemrograman Java.

## Penjelasan Alur program

### Input

<img width="362" height="47" alt="image" src="https://github.com/user-attachments/assets/08c5d156-b3fa-4dfc-9a06-6b5c8f95cd21" />

import java.util.ArrayList; Untuk membuat ArrayList (penyimpanan daftar wahana).

import java.util.Scanner; Untuk membaca input pengguna dari keyboard.

<img width="737" height="47" alt="image" src="https://github.com/user-attachments/assets/7c2c974c-ef98-4585-95e6-0fb5021202b6" />

Class Main adalah class utama.

main adalah method yang dijalankan pertama kali.

try (Scanner objekScanner = new Scanner(System.in)) Membuat objek scanner dengan try-with-resources, jadi Scanner akan otomatis tertutup saat program selesai.

<img width="695" height="48" alt="image" src="https://github.com/user-attachments/assets/780e2116-950e-4360-bbb4-e3612e1b2a09" />

ArrayList<String> wahana Tempat untuk menyimpan nama wahana dalam bentuk list.

int pilihan Variabel untuk menampung input pilihan menu dari user.

<img width="862" height="252" alt="image" src="https://github.com/user-attachments/assets/190f18a9-c424-447b-bbaa-fc11e3f1920a" />

do...while Program akan terus menampilkan menu sampai user memilih 5 (Keluar).

Menampilkan menu CRUD.

objekScanner.nextInt() Membaca input angka untuk menu.

objekScanner.nextLine() Menghapus newline biar input berikutnya tidak loncat.

1. Tambah Wahana

   <img width="617" height="166" alt="image" src="https://github.com/user-attachments/assets/e78b548d-9881-4941-bdbc-9046fdf1a5c2" />

   User memasukkan nama wahana baru.

   wahana.add(nama) → Menambahkan nama wahana ke daftar.

2. Lihat Wahana

    <img width="702" height="258" alt="image" src="https://github.com/user-attachments/assets/004047df-2a34-4726-a700-facf0f282d08" />

    Jika ArrayList kosong, tampilkan pesan.

    Jika tidak kosong, tampilkan daftar wahana dengan perulangan for.

3. Ubah Wahana

    <img width="787" height="437" alt="image" src="https://github.com/user-attachments/assets/7e331419-1ac2-4f2e-8804-0633c0449813" />

    User pilih nomor wahana yang mau diubah.

    Lalu sistem mengecek validitas nomor.

    wahana.set(index, namaBaru) Mengganti nama wahana di posisi tertentu.

4. Hapus Wahana

    <img width="816" height="390" alt="image" src="https://github.com/user-attachments/assets/9be3b866-3f2a-4ad5-94c6-4764be7df7c9" />

    Kalau ArrayList kosong, tampilkan pesan.

    Kalau ada, user pilih nomor wahana untuk dihapus.

    wahana.remove(index) Menghapus elemen wahana di daftar.

5. Keluar Program

    <img width="643" height="145" alt="image" src="https://github.com/user-attachments/assets/375ce927-aea1-465a-abe1-1a60341c53d1" />

    Kalau user pilih 5, program berhenti.

    Kalau user salah input, pesan error ditampilkan.

<img width="257" height="26" alt="image" src="https://github.com/user-attachments/assets/472735e7-f63e-4df5-9475-48b8abbe2850" />

Perulangan akan terus berjalan sampai user memilih angka 5.

### Output

Saat program dijalankan, user akan melihat menu ini berulang kali

<img width="355" height="177" alt="image" src="https://github.com/user-attachments/assets/7a73bc00-aac4-49af-9779-def333d36295" />

Saat user memilih 1, user diminta untuk memasukkan nama wahana untuk ditambahkan

<img width="343" height="77" alt="image" src="https://github.com/user-attachments/assets/a8df9f36-9171-4cca-bef4-2f0ae64c9418" />

Saat user memilih 2, program akan menampilkan nama wahana yang tersedia

<img width="161" height="100" alt="image" src="https://github.com/user-attachments/assets/a491353a-12a5-424d-a9cf-d00d5feb892a" />

Saat user memilih 4, user akan diminta untuk memasukkan mana wahana yang ingin diubah dan memasukkan nama baru untuk wahana tersebut

<img width="482" height="106" alt="image" src="https://github.com/user-attachments/assets/8aeaee57-6cb4-473f-a63c-cff6752e7979" />

Saat user memilih 4, user akan diminta untuk menghapus wahana yang diinginkan

<img width="483" height="73" alt="image" src="https://github.com/user-attachments/assets/7a3ca728-d27a-42c1-8282-9d407a71b7c6" />

Pilih nomor 2 lagi untuk melihat apakah wahana yang dihapus telah terhapus

<img width="200" height="63" alt="image" src="https://github.com/user-attachments/assets/091f44ef-16c6-4aa4-beb3-f99957de38d0" />

Jika memilih 5, user akan langsung dikeluarkan dari program

<img width="797" height="381" alt="image" src="https://github.com/user-attachments/assets/71a8777e-5e9f-4db5-94c8-a32309f6f487" />



















    





