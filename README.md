## Laporan Praktikum - #02 Pengenalan ReactJS

|  | Pemrograman Berbasis Framework 2024 |
|--|--|
| NIM |  2141720063|
| Nama |  Maria Fadilla |
| Kelas | TI - 3A |


## Praktikum Membuat Project Pertama ReactJS
---
Membuat folder belajar-react

![Screenshot](assets-report/00.png)

Membuat Project "hello-world"

![Screenshot](assets-report/01.png)

### Jawaban Soal 1

Pada gambar tersebut, yang dimaksud dengan:

- `TypeScript` merupakan superset dari JavaScript — dibuat oleh Microsoft — yang artinya semua kode JavaScript adalah kode TypeScript juga. Typescript adalah bahasa pemrograman superset dari Javascript yang memiliki fitur-fitur seperti Static Typing, OOP, dan Dynamic Typing. Typescript di-compile menjadi Javascript dengan tsc (Typescript Compiler), setelah itu kita bisa jalankan dengan runtime Javascript seperti Nodejs, Deno, Bun, dan Web browser. 

- `ESLint` adalah salah satu tools JavaScript untuk melakukan static analyzes kode kita agar kita tau dengan cepat menemukan masalah atau potensi bug dari kode yang sudah kita buat. ESLint dapat diintegrasikan dengan JavaScript dan TypeScript.

- `Tailwind CSS` Tailwind CSS yaitu kerangka kerja CSS yang berisi sekumpulan utility classes untuk membangun antarmuka kustom dengan cepat. Berbeda dengan kerangka kerja CSS seperti Bootstrap, Bulma, atau Foundation, Tailwind CSS bukan sebuah UI Framework. Pendekatan “utility-first” yang diusung oleh Tailwind memungkinkan pengembang untuk membangun desain dengan cepat menggunakan kelas-kelas kecil dan fleksibel yang mewakili properti CSS tertentu.

- `App Router` App Router (atau sering disebut sebagai aplikasi router) adalah bagian dari framework atau perpustakaan yang mengatur rute (routing) di dalam aplikasi web atau aplikasi berbasis web. Ini memungkinkan navigasi antara halaman-halaman atau tampilan-tampilan yang berbeda dalam aplikasi tanpa harus memuat ulang halaman utama.

- `Import alias` Import alias adalah cara untuk membuat alias atau nama singkat untuk berkas yang diimpor di dalam sebuah skrip JavaScript atau TypeScript. Biasanya, import alias digunakan untuk menghindari konflik nama atau mempersingkat nama yang panjang.

Membuka project degan VS Code

![Screenshot](assets-report/02.png)
![Screenshot](assets-report/03.png)

### Jawaban Soal 2

![Screenshot](assets-report/04.png)

Pada struktur project, berikut kegunaan folder dan file masing-masing tersebut: 

- `node_modules:` Folder yang berisi semua paket dan dependensi yang diperlukan oleh proyek React.

- `public:` Folder untuk file-file statis yang disajikan langsung oleh server web, seperti index.html dan gambar-gambar statis.

- `src:` Folder utama kode sumber aplikasi React. Biasanya berisi file-file JavaScript dan komponen React yang merupakan bagian inti dari aplikasi. 

- `.eslintrc.json:` Berkas konfigurasi untuk ESLint, utilitas linting JavaScript.

- `.gitignore:` Berkas konfigurasi untuk mengabaikan file dan folder dalam operasi Git.

- `next-env.d.ts:` Berkas definisi tipe untuk lingkungan pengembangan Next.js.

- `next.config.mjs:` Berkas konfigurasi untuk Next.js dalam mengatur aplikasi web.

- `package-lock.json:` Berkas untuk memastikan konsistensi versi paket antara lingkungan pengembangan dan produksi.

- `package.json:` Berkas konfigurasi proyek React, termasuk dependensi, skrip, dan informasi proyek lainnya.

- `postcss.config.js:` Berkas konfigurasi untuk PostCSS, alat pengolahan CSS.

- `README.md:` Berkas berisi dokumentasi proyek.

- `tailwind.config.ts:` Berkas konfigurasi untuk Tailwind CSS,  berisi preferensi dan aturan yang digunakan oleh Tailwind CSS saat memproses dan mengonversi kode CSS, seperti aturan penulisan, aturan kualitas, dan aturan lainnya.

- `tsconfig.json:` Berkas konfigurasi untuk TypeScript, berisi preferensi dan aturan yang digunakan oleh TypeScript saat memeriksa dan mengonversi kode JavaScript, seperti aturan penulisan, aturan kualitas, dan aturan lainnya.

