# Markdown to Word Converter Pro

Aplikasi web sederhana namun powerful untuk mengubah teks **Markdown** menjadi dokumen **Microsoft Word (.doc)** secara instan. Dirancang dengan antarmuka modern, responsif, dan hasil ekspor yang sudah terformat rapi.

### Akses Aplikasi
Aplikasi dapat diakses langsung melalui browser di:  
👉 **[https://notsyam.github.io/Markdown-to-Plain.github.io/](https://notsyam.github.io/Markdown-to-Plain.github.io/)**

---

## Fitur Utama
- **Live Preview:** Lihat perubahan dokumen secara real-time saat Anda mengetik.
- **Auto-Formatting Word:** Hasil download secara otomatis menggunakan font **Arial 11pt** dengan margin standar dokumen kantor.
- **Custom Filename:** Anda bisa menentukan nama file sebelum mengunduh.
- **Copy Clean Text:** Fitur untuk menyalin teks bersih hasil render (tanpa simbol markdown) untuk langsung dipaste ke platform lain.
- **Dark Mode Editor:** Editor menggunakan tema gelap (VS Code style) agar nyaman di mata.
- **Fixed Layout:** Header tetap di atas dan area kerja dapat di-scroll secara independen (nyaman untuk dokumen panjang).

---

## Cara Penggunaan

1. **Buka Aplikasi:** Kunjungi [Link Akses](https://notsyam.github.io/Markdown-to-Plain.github.io/).
2. **Input Teks:** Ketik atau tempel (*paste*) teks Markdown Anda pada kolom **Editor Markdown** (sebelah kiri).
3. **Cek Preview:** Hasil render akan muncul secara otomatis di kolom **Preview** (sebelah kanan).
4. **Beri Nama File:** Ubah nama file sesuai keinginan Anda pada kotak input nama file di bagian header.
5. **Simpan Dokumen:**
   - Klik tombol **"Download Word"** untuk mengunduh file dalam format `.doc`.
   - Atau klik tombol **"Copy"** jika Anda hanya ingin menyalin teks bersihnya saja.

---

## Teknologi yang Digunakan
- **HTML5 & CSS3** (Custom Flexbox Layout & Glassmorphism UI)
- **JavaScript (Vanilla)**
- **[Marked.js](https://marked.js.org/)** - Library untuk mengubah Markdown menjadi HTML.

---

## Catatan Teknis
File `.doc` yang dihasilkan menggunakan format HTML-XML yang didukung oleh Microsoft Word. Saat dibuka di Microsoft Word, dokumen akan otomatis menerapkan:
- **Font Family:** Arial
- **Font Size:** 11pt
- **Line Height:** 1.5

---
