# Tugas1-GrafikaKomputer
Membuat Program Sederhana dengan WebGL


## Tugas Individu 1 - Membuat Program Sederhana dengan WebGL

Program sederhana yang saya buat adalah sebuah rumah dengan menggunakan dua bentuk yaitu segitiga sebagai atapnya dan segiempat sebagai body rumah dengan latar belakang biru.

Terdapat 3 Source Code yaitu : 

1. index.html : struktur dasar halaman web yang menggunakan WebGL untuk merender grafik.  Di dalam bagian <head>, terdapat tag <title> untuk memberikan judul pada halaman dan tag <link> untuk menyertakan file CSS yang berfungsi untuk styling. Pada bagian <body>, terdapat elemen <canvas> dengan id webgl-canvas yang akan digunakan oleh WebGL untuk menggambar grafik. Tag <script> menyertakan file JavaScript eksternal yang mengandung kode untuk merender grafik menggunakan WebGL.
2. style.css : mengatur elemen body dan html agar tidak memiliki margin atau padding, serta mengatur overflow sehingga tidak ada scrollbar yang muncul.
3. script.js : terdapat fungsi main()  untuk menginisialisasi WebGL dan merender sebuah gambar rumah sederhana pada kanvas HTML. Fungsi ini mulai dengan mendapatkan konteks WebGL dari elemen kanvas. Selanjutnya, dua shader (vertex dan fragment) didefinisikan dalam bentuk sumber kode GLSL, dan fungsi createShader dan createProgram digunakan untuk mengkompilasi dan menghubungkan shader-shader tersebut ke dalam program WebGL. Posisi dan warna vertiks untuk atap (segitiga) dan badan rumah (persegi panjang) ditentukan dalam buffer dan diikat ke atribut shader yang sesuai.

### Hasil Program 
![Screenshot 2024-08-30 204742](https://github.com/user-attachments/assets/5a2d81c0-0c0a-471d-b7ad-fe561cce8d93)
