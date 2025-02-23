# praktikum-3-sistem-operasi


| Nama        | Tamam Rifky Aqila |
|----------------|------------|
| NIM        | 09030282327016 |
| Program Studi | Teknik Komputer |

</div>
<br>
<div class="item">
<p>1. Lihat peralatan I/O, character device, yang ada pada system komputer.</p>
<img src="https://github.com/user-attachments/assets/f2e384f6-606c-4ce8-9021-693a0acf95a9" width = "300">
<p>Menampilkan daftar perangkat character device pada sistem Linux yang ada di direktori /dev. Perintah ini membantu melihat perangkat seperti keyboard, mouse, dan terminal (/dev/tty), yang beroperasi dengan data berbasis karakter.</p>
<p>2. Buatlah sub direktori januari, februari dan maret sekaligus pada direktori latihan5.
</p>
<img src="https://github.com/user-attachments/assets/3b757e1d-cca9-48fb-9aba-b1532597405c" width = "300">
<p>Membuat tiga subdirektori dalam direktori latihan5 sekaligus, tanpa harus menjalankan perintah mkdir tiga kali. Opsi -p memastikan bahwa jika latihan5 belum ada, maka akan dibuat terlebih dahulu.</p>
<p>3. Buatlah file dataku yang berisi nama, nim dan alamat anda pada sub direktori januari dan copy-kan file tersebut ke sub direktori februari dan maret.</p>
<img src="https://github.com/user-attachments/assets/25658fb8-f6e5-439a-8215-229273d9a542" width = "300">
<img src="https://github.com/user-attachments/assets/6248d246-256a-4471-a24b-18c749456f77" width = "300">
<p>Membuat file dataku di dalam direktori januari yang berisi informasi pribadi. Menyalin file dataku dari januari ke februari dan maret, sehingga ketiga direktori memiliki file yang sama.</p>
<p>4. Ubahlah ijin akses file dataku pada sub direktori januari sehingga group dan others dapat melakukan write.</p>
<img src="https://github.com/user-attachments/assets/4c117360-a6d4-42fc-aef5-41177297ab84" width = "300">
<p>Mengubah izin file dataku sehingga, Memungkinkan semua pengguna (group dan others) untuk mengedit isi file.</p>
<p>5. Ubahlah ijin akses file dataku pada sub direktori pebruari sehingga user dapat melakukan baik write, read maupun execute, tetapi group dan others hanya bisa read dan execute.</p>
<img src="https://github.com/user-attachments/assets/fd2e273d-1026-410a-825d-b4c3e7579cf3" width = "300">
<p>Kegunaan, Hanya pemilik file yang bisa mengedit, tetapi orang lain bisa membaca dan menjalankan file jika diperlukan.</p>
<p>6. Ubahlah ijin akses file dataku pada sub direktori maret sehingga semua dapat melakukan write, read dan execute.</p>
<img src="https://github.com/user-attachments/assets/6bf088b1-1d3e-41e1-87bb-73412ea7f7c3" width = "300">
<p>Semua pengguna dapat membaca, menulis, dan mengeksekusi file, tanpa batasan.</p>
<p>7. Hapuslah direktori maret.</p>
<img src="https://github.com/user-attachments/assets/d09f76fe-0c16-4d0a-9fa8-621e4baaed1e" width = "300">
<p>Menghapus latihan5/maret dan memastikan tidak ada sisa file atau subdirektori di dalamnya.</p>
<p>8. Ubahkan kepemilikan sub direktori februari sehingga user dan group hanya dapat melakukan read, dan cobalah untuk membuat direktori baru haha pada sub direktori februari.</p>
<img src="https://github.com/user-attachments/assets/2314faa9-fdf1-466b-bdf7-14e7c8816ca9" width = "300">
<p>Mencoba membuat subdirektori haha di dalam februari, yang sebenarnya gagal karena tidak ada izin menulis.Namun, jika ingin membuat haha, izin harus diubah menggunakan chmod 750 agar pemilik bisa menulis.</p>
<P>9. Modifikasi umask dari file dataku pada sub direktori januari menjadi 027 dan berapakan nilai default-nya?</P>
<img src="https://github.com/user-attachments/assets/621ab52e-e12f-41ba-b478-a63ef8bb5f3b" width = "300">
<p>Mengatur izin default untuk file baru agar lebih ketat dalam keamanan. Setelah membuat file baru (dataku_baru), perintah ls -l digunakan untuk mengecek apakah izin yang diberikan sesuai dengan umask.</p>
<p>10. Buatlah link dari file dataku ke file dataku.ini dan file dataku.juga dan dengan perintah list perhatikan berapa link yang terjadi?</p>
<img src="https://github.com/user-attachments/assets/13193b62-b4c0-4477-935e-8f99227d3b57" width = "300">
<p>Hard link adalah file yang merujuk ke inode yang sama di sistem file. setelah membuat dua hard link, perintah ls -l akan menunjukkan bahwa file dataku, dataku.ini, dan dataku.juga memiliki jumlah link yang meningkat. Memastikan bahwa semua hard link merujuk ke file yang sama dan berbagi konten yang sama.</p>

## KESIMPULAN
Melalui serangkaian tugas ini, saya telah menunjukkan pemahaman yang baik tentang dasar-dasar sistem file di Linux, termasuk interaksi dengan perangkat I/O, manajemen direktori, dan manipulasi file. Penguasaan konsep-konsep ini merupakan fondasi penting bagi pengelolaan sistem operasi dan administrasi sistem yang lebih lanjut.
</div>
<br>






