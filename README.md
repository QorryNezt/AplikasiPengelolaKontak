# AplikasiPengelolaKontak
 Latihan 3  - Sayyida Qurrata A'yunin (2210010331) <br>
 Aplikasi ini bertujuan untuk mengelola kontak secara sederhana. <br><br> Aplikasi ini memiliki pengelolaan secara dasar yakni: <br>CRUD (Create, Read, Update, dan Delete)<br>
  ---
 Semua button berfungsi dengan baik. Tersedia 2 cara pembersihan textfield yakni dengan meng-highlight textfield Nama atau dengan menekan tombol Clear.
 Setiap anda selesai mencari kontak, saya sarankan untuk meng-highlight textfield Nama atau menekan tombol Clear agar me reload table seperti semula.
 Aplikasi ini memiliki kekurangan seperti apabila ada nama duplikasi tidak dapat terdeteksi, selain dari itu semua fungsi berjalan baik dan semestinya. Pencarian berdasarkan nama saja.
<br>
Saya sarankan untuk memiliki beberapa library ini sebelum menjalankan program ini
### Library Jar yang Harus di Download:<br>
1. SQLite JDBC Jar dengan versi 3.47 atau lebih baru [**Download disini**](http://www.java2s.com/Code/Jar/s/Downloadsqlitejdbc372jar.htm)<br>
2. SLF4J - API Jar dengan versi 2.0.7 atau lebih baru [**Download disini**](https://repo1.maven.org/maven2/org/slf4j/slf4j-api/2.0.7/)<br>
3. SLF4J - Simple Jar dengan versi 2.0.7 atau lebih baru [**Download disini**](https://repo1.maven.org/maven2/org/slf4j/slf4j-simple/2.0.7/)
___
## Berikut beberapa sample poto berjalannya program saya:
1. Tampilan awal yang sudah terisi dengan database bawaan dari saya<br><br>
![App Screenshot](https://github.com/QorryNezt/AplikasiPengelolaKontak/blob/main/sample%20pics/base.png?raw=true) <br><br>
2. Tampilan pencarian (Contoh mencari orang yang bernama "Loki") :<br><br>
![App Screenshot](https://github.com/QorryNezt/AplikasiPengelolaKontak/blob/main/sample%20pics/cari.png?raw=true) <br><br>
3. Tampilan pencarian gagal karena field nama kosong :<br><br>
![App Screenshot](https://github.com/QorryNezt/AplikasiPengelolaKontak/blob/main/sample%20pics/error_search.png?raw=true) <br><br>
4. Tampilan penyimpanan data berhasil notif :<br><br>
![App Screenshot](https://github.com/QorryNezt/AplikasiPengelolaKontak/blob/main/sample%20pics/simpan.png?raw=true) <br><br>
5. Tampilan Edit Data Before dan After nya Hasil tanpa terhalang notif adalah tampilan awal base :<br><br>
Before<br>
![App Screenshot](https://github.com/QorryNezt/AplikasiPengelolaKontak/blob/main/sample%20pics/edit_before.png?raw=true) <br><br>
After<br>
![App Screenshot](https://github.com/QorryNezt/AplikasiPengelolaKontak/blob/main/sample%20pics/edit_after.png?raw=true) <br><br>
6. Warning Notifikasi jika input melebihi batas maksimal atau kurang dari batas minimal angka telepon:<br><br>
![App Screenshot](https://github.com/QorryNezt/AplikasiPengelolaKontak/blob/main/sample%20pics/warn_limit.png?raw=true) <br><br>
7. Warning Notifikasi jika menekan keyboard bukan numerik tekecuali "-" (Strip) :<br><br>
![App Screenshot](https://github.com/QorryNezt/AplikasiPengelolaKontak/blob/main/sample%20pics/warn_num.png?raw=true) <br><br>
