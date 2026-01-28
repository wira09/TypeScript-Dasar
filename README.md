Berikut adalah panduan dokumentasi untuk pengenalan TypeScript, instalasi, dan cara menjalankannya:

---

### 1. Pengenalan TypeScript

- **Apa itu TypeScript?**  
  `TypeScript` adalah bahasa pemrograman _open-source_ yang dikembangkan oleh Microsoft. Ini adalah superset dari JavaScript yang menambahkan fitur _optional static typing_ dan beberapa fitur lainnya yang membantu dalam pengembangan aplikasi yang besar dan kompleks.
- **Keunggulan TypeScript:**
  - Memiliki sistem _type checking_ pada saat kompilasi.
  - Dukungan untuk fitur terbaru JavaScript (ES6/ES7).
  - Kemampuan untuk menulis kode yang lebih aman dan mudah dipelihara.
  - Menyediakan alat bantu pengembangan seperti auto-completion dan refactoring.

---

### 2. Instalasi TypeScript

- **Langkah-langkah Instalasi:**
  - Pastikan `Node.js` dan `npm` sudah terinstal di komputer Anda. Anda dapat memeriksanya dengan perintah berikut:
    ```bash
    node -v
    npm -v
    ```
  - Jika belum terinstal, unduh dan instal Node.js dari [https://nodejs.org](https://nodejs.org).
  - Setelah `npm` tersedia, instal TypeScript secara local menggunakan perintah berikut:
    ```bash
    npm install typescript --save-dev
    ```
  - Untuk memverifikasi instalasi, jalankan:
    ```bash
    npx tsc
    ```
  - Kemudian install untuk mempercepat compile, dengan perintah berikut:
    ```bash
    npm install -D tsx
    ```

---

### 3. Cara Menjalankan Project TypeScript

- **Langkah-langkah Menjalankan:**
  - Pastikan Anda memiliki file TypeScript dengan ekstensi [.ts], misalnya `index.ts`.
  - Cara menjankannya menggunakan perintah berikut:
    ```bash
    npx tsx index.ts
    ```
    maka akan menghasilkan sebuah kode yg sudah di tulis

---

### 4. Konfigurasi Tambahan (Optional)

- Anda dapat membuat file konfigurasi `tsconfig.json` untuk mengatur opsi kompilasi TypeScript:
  ```bash
  tsc --init
  ```
  File ini memungkinkan Anda mengatur parameter seperti direktori input/output, target versi JavaScript, dan lainnya.

---

### 5. Sumber Informasi

- [https://www.typescriptlang.org](https://www.typescriptlang.org)
- Dokumentasi resmi dan panduan penggunaan TypeScript.

---
