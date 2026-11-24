# SIRG — HIS JUDGEMENT MEDIA MINISTRI

Website resmi pelayanan media SIRG (HIS JUDGEMENT MEDIA MINISTRI): podcast, video pelajaran Alkitab, ringkasan Sekolah Sabat, materi PPT & PDF, kegiatan pelayanan, rekreasi, dan jadwal.

Dibuat dengan HTML, CSS, dan JavaScript murni tanpa framework. Font dari Google Fonts.

## Struktur
```
index.html        Halaman utama (seluruh tampilan & logika)
assets/hero.jpg   Foto hero
assets/profile.jpg Foto profil (lingkaran)
.nojekyll         Agar GitHub Pages membaca file apa adanya
```

## Publish ke GitHub Pages
1. Buat repository baru di GitHub, misalnya `sirg-website`.
2. Upload semua isi folder ini ke repository (atau `git push` dari komputer Anda).
3. Buka **Settings → Pages**.
4. Di bagian **Build and deployment**, pilih **Source: Deploy from a branch**, lalu **Branch: main** dan folder **/ (root)**. Klik **Save**.
5. Website tersedia di `https://USERNAME.github.io/sirg-website/` dalam beberapa menit.

Untuk domain sendiri (misalnya `sirg.id`): tambahkan file `CNAME` berisi nama domain, lalu atur DNS di penyedia domain sesuai petunjuk GitHub Pages.

## Mengubah konten
- Buka halaman dengan menambahkan `#admin` di akhir alamat, lalu masukkan PIN admin.
- Di dalam panel, ubah Umum & Hero, Pelayanan, Rekreasi, Materi, dan Jadwal, lalu klik **Simpan**.
- Perubahan tersimpan di browser yang dipakai. Untuk membuat perubahan tampil bagi semua pengunjung, salin data dari menu **Backup** dan perbarui nilai default di `index.html`.

## Catatan keamanan
- PIN admin ada di dalam kode `index.html` (variabel `ADMIN_PIN`). Ini hanya pengaman sederhana, bukan login yang aman. Jangan simpan data sensitif di website ini.
- Ganti PIN secara berkala jika repository bersifat publik.

## Kontak
- Email: godsavemeministry@gmail.com
- YouTube: https://www.youtube.com/@grifinsakul
- Instagram: https://www.instagram.com/pstgrifin/
- TikTok: https://www.tiktok.com/@pst.grifins

© SIRG — HIS JUDGEMENT MEDIA MINISTRI. Soli Deo Gloria.
