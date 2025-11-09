# HAXOR DOS FOR BEGINNER

![Header](https://qu.ax/gUznP.jpeg)

> DDoS Layer 7 merupakan serangan yang menargetkan lapisan aplikasi (layer 7 pada model OSI) dari sebuah server web. Berbeda dengan serangan terhadap bandwidth atau infrastruktur, serangan ini memusatkan sasaran pada aplikasi itu sendiri—umumnya melalui permintaan HTTP yang tampak sah dalam volume besar. Tujuannya adalah mengeksploitasi sumber daya server (CPU, memori, atau koneksi database) hingga aplikasi mengalami penurunan kinerja, tidak responsif, atau sepenuhnya tidak dapat diakses oleh pengguna sah.

---

**Latar Belakang**  
Alat ini dikembangkan sebagai upaya meningkatkan ketahanan website-website di Indonesia, yang menempati peringkat 9 dunia sebagai target serangan DDoS menurut laporan StromWall. Proyek ini menyediakan simulasi serangan DoS dalam skala terbatas guna mengidentifikasi potensi kerentanan, mengingat banyaknya situs sekolah, UMKM, bahkan instansi pemerintah yang kerap menjadi korban DDoS/DoS.

---

**Tentang haxorDos**  
haxorDos adalah utilitas pengujian beban (stress-testing) dan evaluasi firewall yang dikembangkan oleh pelajar asal Jawa Timur, beridentitas samaran REYHAN6610. Aplikasi ini dibangun di atas library [haxor-dos](https://www.npmjs.com/package/haxordos) yang menawarkan antarmuka lebih ringkas dan ringan dibandingkan solusi sejenis seperti k6.

---

**Instalasi & Penggunaan**

1. Clone repositori  
   ```bash
   git clone https://github.com/REYHAN6610/haxorDos.git
   cd haxorDos
   ```

2. Instal dependensi  
   
```bash
   yarn install   # atau npm install
   ```

3. Jalankan aplikasi  
   
```bash
   npm start
   ```

Setelah langkah-langkah di atas selesai, alat siap digunakan untuk keperluan pengujian.
