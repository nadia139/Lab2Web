# Lab2Web - CSS Styling

Repositori ini berisi pembelajaran tentang styling halaman web menggunakan CSS dengan berbagai teknik implementasi.

---

## 📋 Daftar Isi
- [Setelah Styling (Dengan CSS)](#setelah-styling-dengan-css)
- [Teknik CSS yang Digunakan](#teknik-css-yang-digunakan)
- [Tampilan Visual](#tampilan-visual)

---

## 🎨 Setelah Styling (Dengan CSS)

Tampilan halaman web yang sudah diberi styling CSS dengan perubahan visual sebagai berikut:

### Perubahan Visual:
- **Background**: Biru tosca/teal menutupi sebagian besar halaman
- **Teks "Hello World"**: Sekarang berwarna putih dan lebih kontras
- **Paragraf**: Berwarna putih dan mudah dibaca dengan latar biru
- **Button "Informasi selengkapnya"** berubah menjadi:
  - Background merah
  - Teks putih
  - Bentuk kotak dengan padding yang jelas

---

## 🛠️ Teknik CSS yang Digunakan

### 1. Kemungkinan Besar Menggunakan Kombinasi:
- **CSS Internal**: Di dalam tag `<style>` di HTML untuk styling umum
- **Inline CSS**: Langsung di tag HTML untuk styling spesifik
- **External CSS**: File CSS terpisah untuk styling yang dapat digunakan ulang

### 2. Perubahan yang Diterapkan:
- Perubahan warna background
- Perubahan font color
- Padding dan margin
- Styling button dengan hover effects

---

## 📸 Tampilan Visual

### Tampilan Awal
Di tahap ini, HTML sudah dibuat tapi belum ada internal CSS.

<img width="937" alt="Screenshot Tampilan Awal" src="https://github.com/user-attachments/assets/55af0005-9df8-4285-bcbd-b1b6dd7a8f60" />

**Karakteristik:**
- Teks masih pakai default style browser
- Judul `<h1>` tampil besar dan tebal hitam
- Link `<a>` berwarna biru standar
- Paragraf `<p>` berwarna hitam, font default Times New Roman
- Artinya ini masih tampilan dasar HTML tanpa styling tambahan

---

### Tampilan Kedua
(Setelah ditambahkan CSS internal & inline)

<img width="958" alt="Screenshot Tampilan Kedua" src="https://github.com/user-attachments/assets/5d65b431-083f-431f-aeb3-fd8cee7d9b12" />

Sudah menambahkan internal CSS di `<head>` dengan tag `<style>`.

**Contoh CSS:**
```css
body {
  font-family: 'Open Sans', sans-serif;
}

h1 {
  font-size: 24px;
  color: #0F189F;
  text-align: center;
  padding: 20px 10px;
}

h1 i {
  color: #6d6a6b;
}
```

**Perubahan yang Terlihat:**
- `<h1>` (judul) jadi biru tua dan rata tengah
- `<i>` di dalam `<h1>` (kata Inline CSS) berubah warna abu-abu
- Font keseluruhan berubah dari Times New Roman ke sans-serif
- `<p>` sudah diberi inline CSS → `style="text-align: center; color: #ccd8e4;"` sehingga teks paragraf jadi rata tengah dengan warna abu-abu kebiruan

---

### Tampilan Ketiga - Sebelum Styling (HTML Dasar)

<img width="950" alt="Screenshot Sebelum Styling" src="https://github.com/user-attachments/assets/f0bc0293-36fa-4ce9-a7ff-b6561ef2cefe" />

Tampilan halaman web yang masih sangat sederhana dengan karakteristik:
- Judul "CSS Internal dan Inline CSS" di bagian atas
- Navigasi hijau dengan 3 tombol: "CSS Dasar", "CSS Eksternal", "HTML Dasar"
- Teks "Hello World" berwarna biru tua/navy
- Paragraf penjelasan dengan warna abu-abu terang (hampir tidak terlihat)
- Link "Informasi selengkapnya" berwarna biru standar
- Background putih polos
- Layout minimal tanpa styling khusus

---

### Tampilan Keempat - Setelah Styling Lengkap

<img width="963" alt="Screenshot Setelah Styling" src="https://github.com/user-attachments/assets/4d293257-574e-4ab7-818d-502db293d64b" />

Tampilan halaman web yang sudah diberi styling CSS lengkap dengan perubahan:

**Perubahan Visual:**
- Background biru tosca/teal menutupi sebagian besar halaman
- Teks "Hello World" sekarang berwarna putih dan lebih kontras
- Paragraf sekarang berwarna putih dan mudah dibaca dengan latar biru
- Button "Informasi selengkapnya" berubah menjadi:
  - Background merah
  - Teks putih
  - Bentuk kotak dengan padding yang jelas

**Teknik CSS yang Digunakan:**
- Kemungkinan besar menggunakan kombinasi:
  - **CSS Internal** (di dalam tag `<style>` di HTML) untuk styling umum
  - **Inline CSS** (langsung di tag HTML) untuk styling spesifik
  - Perubahan warna background, font color, padding, dan styling button

---

## 📚 Kesimpulan

Dari pembelajaran ini dapat disimpulkan bahwa:
1. **CSS Internal** cocok untuk styling yang spesifik untuk satu halaman
2. **Inline CSS** berguna untuk styling elemen tertentu yang unik
3. **CSS Eksternal** (jika digunakan) memudahkan maintenance dan reusability
4. Kombinasi ketiga teknik dapat menghasilkan tampilan web yang menarik dan profesional

---

## 👨‍💻 Author
- **Nama**: [Nama Kamu]
- **NIM**: [NIM Kamu]
- **Kelas**: [Kelas Kamu]

---

## 📝 License
Project ini dibuat untuk keperluan pembelajaran Lab Pemrograman Web.

---

**Happy Coding! 🚀**
