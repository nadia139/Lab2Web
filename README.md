<img width="937" height="660" alt="Screenshot 2025-09-29 132459" src="https://github.com/user-attachments/assets/55af0005-9df8-4285-bcbd-b1b6dd7a8f60" />



#Tampilan awal
Di tahap ini, HTML sudah dibuat tapi belum ada internal CSS.
Teks masih pakai default style browser:
Judul <h1> tampil besar dan tebal hitam.
Link <a> berwarna biru standar.
Paragraf <p> berwarna hitam, font default Times New Roman.
Artinya ini masih tampilan dasar HTML tanpa styling tambahan




#Tampilan Kedua




<img width="958" height="1078" alt="Screenshot 2025-09-29 141522" src="https://github.com/user-attachments/assets/5d65b431-083f-431f-aeb3-fd8cee7d9b12" />




(setelah ditambahkan CSS internal & inline)
sudah menambahkan internal CSS di <head> dengan tag <style>.
Contohnya:
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


Perubahan yang terlihat:
<h1> (judul) jadi biru tua dan rata tengah.
<i> di dalam <h1> (kata Inline CSS) berubah warna abu-abu.
Font keseluruhan berubah dari Times New Roman ke sans-serif.
<p> sudah diberi inline CSS → style="text-align: center; color: #ccd8e4;" sehingga teks paragraf jadi rata tengah dengan warna abu-abu kebiruan.
