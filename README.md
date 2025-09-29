# Proyek PiCat: Sistem Prediksi Genre Berbasis AI

Selamat datang di repositori utama untuk Proyek PiCat! Proyek ini adalah sistem cerdas yang mampu memprediksi genre sebuah karya (film, musik, atau buku) berdasarkan judul dan deskripsi menggunakan *Natural Language Processing*.

---

## Anggota Tim & Kontribusi

Proyek ini adalah hasil kolaborasi dari tim yang terdiri dari:

* **Calvin Martin** - UI/UX Designer
* **Lidya Laura Sutanto** - Frontend Developer (Web)
* **Randysta Rasta Putra** - Frontend Developer (Mobile)
* **Rangga Mulia Tohpati** - Backend & AI Developer

---

## Arsitektur & Repositori Proyek

Proyek ini terdiri dari tiga komponen utama yang dikembangkan secara terpisah. Setiap komponen memiliki repositori GitHub-nya masing-masing.

| Komponen | Deskripsi | Link Repositori |
| :--- | :--- | :--- |
| **Frontend Mobile** | Aplikasi mobile Android yang dibangun dengan Flutter. | [**[KLIK DI SINI]**](https://github.com/Randys-alph/picat_app) |
| **Frontend Web** | Aplikasi web responsif yang dibangun dengan React.js. | [**[KLIK DI SINI]**](https://github.com/LidyaLaura/picat-web) |
| **Backend (API)** | Server API dibangun dengan Python, sebagai model AI untuk prediksi genre. | [**[KLIK DI SINI]**](https://github.com/NvmberMan/Picat-Flask) |
| **Model AI** | Notebook berisi proses training dan preprocessing model. | [**[KLIK DI SINI]**](https://github.com/NvmberMan/Picat-Model) |
| **Desain UI/UX** | Wireframe & prototype untuk web maupun aplikasi yang dibuat dengan Figma. | [**[KLIK DI SINI]**](https://www.figma.com/proto/oyps3EWSTeJo8Z261CMDr9/AI?page-id=0%3A1&node-id=6-155&p=f&viewport=77%2C33%2C0.23&t=oMzGNfem3ZJD8CVT-1&scaling=contain&content-scaling=fixed&starting-point-node-id=6%3A155) |

---

## Cara Menjalankan Proyek

Untuk menjalankan proyek ini secara keseluruhan, Anda perlu menjalankan setiap komponen secara terpisah. Pastikan Anda memulai dari Backend terlebih dahulu.

### 1. Backend & Model AI
* **Teknologi:** Python, Flask, Scikit-learn
* **Instruksi:**
    1.  *Clone* repositori backend.
    2.  Instal semua dependensi yang dibutuhkan: `pip install -r requirements.txt`.
    3.  Jalankan server: `python app.py`.
    4.  Server akan berjalan di `http://localhost:5000`.

### 2. Frontend Web
* **Teknologi:** React.js
* **Instruksi:**
    1.  *Clone* repositori frontend web.
    2.  Instal semua dependensi: `npm install`.
    3.  Jalankan aplikasi: `npm start`.
    4.  Aplikasi akan terbuka di `http://localhost:3000`.

### 3. Frontend Mobile
* **Teknologi:** Flutter
* **Instruksi:**
    1.  Pastikan Flutter SDK sudah terinstal.
    2.  *Clone* repositori frontend mobile.
    3.  Unduh semua *package*: `flutter pub get`.
    4.  Jalankan aplikasi di emulator atau perangkat fisik: `flutter run`.

---
