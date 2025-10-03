# Praktikum 2 - CSS Dasar

## Tujuan
- Memahami dasar penggunaan CSS pada HTML.  
- Mengetahui cara penulisan CSS dengan internal, inline, dan eksternal.  
- Mengenal selector (elemen, class, dan id) sebagai pengontrol tampilan.  
- Menerapkan CSS untuk membuat halaman web sederhana.  

---

## Langkah Praktikum

### 1. Membuat Dokumen HTML Dasar
Pertama membuat file `lab2_css_dasar.html` berisi struktur dasar HTML yang terdiri dari header, navigasi, dan konten.

📸 Screenshot:  
![Step 1](https://raw.githubusercontent.com/MuhammadArkham/Foto/87c21993aa5405365df3b656f81863e6c129b99e/Screenshot%202025-10-03%20143737.png)

---

### 2. Menambahkan CSS Internal
CSS internal ditulis di bagian `<head>` menggunakan tag `<style>`.  
Di sini saya mengatur tampilan body, header, dan h1.

📸 Screenshot:  
![Step 2](https://raw.githubusercontent.com/MuhammadArkham/Foto/87c21993aa5405365df3b656f81863e6c129b99e/Screenshot%202025-10-03%20143843.png)

---

### 3. Menambahkan Inline CSS
Inline CSS ditulis langsung pada elemen HTML melalui atribut `style`.  
Saya menambahkan inline CSS pada paragraf untuk mengatur warna dan posisi teks.

📸 Screenshot:  
![Step 3](ss_step3_inline.png)

---

### 4. Membuat dan Menghubungkan CSS Eksternal
Langkah berikutnya membuat file `style_eksternal.css` kemudian dihubungkan ke file HTML dengan tag `<link>`.  
CSS eksternal ini digunakan untuk mengatur tampilan navigasi.

📸 Screenshot:  
![Step 4](ss_step4_external.png)

---

### 5. Menambahkan ID dan Class Selector
Terakhir, menambahkan selector ID (`#intro`) dan Class (`.button`, `.btn-primary`) untuk memberi style pada bagian konten dan tombol.

📸 Screenshot:  
![Step 5](ss_step5_selector.png)

---

## Pertanyaan dan Jawaban

### 1. Eksperimen CSS
Saya mencoba menambahkan properti CSS lain pada paragraf, misalnya background, border radius, dan padding.  
Hasilnya paragraf memiliki latar belakang kuning, sudut melengkung, dan ada jarak di dalamnya.

---

### 2. Perbedaan `h1 { ... }` dengan `#intro h1 { ... }`
- `h1 { ... }` berlaku untuk semua elemen h1 di halaman.  
- `#intro h1 { ... }` hanya berlaku untuk h1 yang ada di dalam elemen dengan id `intro`.  

---

### 3. Internal, Eksternal, dan Inline CSS
Jika ketiganya digunakan pada elemen yang sama, maka yang ditampilkan adalah **inline CSS**, karena prioritasnya paling tinggi.  

---

### 4. ID dan Class
Jika sebuah elemen memiliki ID dan Class sekaligus, maka CSS ID yang dipakai karena lebih spesifik daripada Class.  

---


---
