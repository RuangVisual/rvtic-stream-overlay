\<div align="center"\>

\<\!-- Ganti link gambar di bawah dengan logo atau icon asli kamu \--\>

\<img src="https://www.google.com/search?q=https://raw.githubusercontent.com/ruangvisual/rvtic-stream-overlay/main/assets/logo.png" alt="RV-Tic Logo" width="150" onerror="this.src='https://www.google.com/search?q=https://via.placeholder.com/150x150/1a1a1a/ffffff%3Ftext%3DRV-Tic'"/\>

# **🎨 RV-Tic Stream Overlay**

**Bawa Kualitas Stream Kamu ke Level Berikutnya\!**

*Tampilan Web-Based Overlay yang Elegan, Ringan, dan Mudah Dikustomisasi untuk OBS & Streamlabs.*

\</div\>

## **📌 Apa itu RV-Tic?**

**RV-Tic Stream Overlay** (by Ruang Visual) adalah paket overlay berbasis web (HTML/CSS/JS) yang dirancang untuk mempercantik tampilan *live streaming* Anda tanpa memberatkan kinerja PC. Sangat cocok untuk streamer game, vtuber, podcast, atau sekadar *just chatting*.

## **✨ Fitur Utama**

* 🚀 **Sangat Ringan:** Dibuat menggunakan kode murni tanpa framework berat, menjamin FPS game Anda tetap stabil.  
* 🎨 **Desain Elegan:** Tampilan minimalis yang tidak menutupi *gameplay* utama Anda.  
* 💬 **Widget Chat Box:** Tampilan chat yang *smooth* dengan animasi masuk/keluar.  
* 🔔 **Alert Dinamis:** Notifikasi interaktif untuk Follower, Subscriber, dan Donasi baru.  
* ⚙️ **Mudah Dikustomisasi:** Ubah warna, font, dan ukuran hanya dengan mengganti beberapa baris di file konfigurasi.  
* 📱 **Responsive & Adaptif:** Mendukung resolusi 1080p (Landscape) maupun Vertical (untuk TikTok/Shorts).

## **📸 Preview**

*(Ganti URL gambar di bawah dengan screenshot overlay aktual kamu jika sudah ada)*

\<div align="center"\>

\<img src="https://www.google.com/search?q=https://via.placeholder.com/800x450/2b2b2b/ffffff%3Ftext%3DScreenshot%2BPreview%2BOverlay" alt="Preview Overlay" width="100%"/\>

\</div\>

## **🛠️ Cara Penggunaan (Instalasi di OBS)**

Karena ini adalah overlay berbasis web, instalasinya sangat mudah di software *broadcasting* mana pun yang mendukung fitur **Browser Source** (seperti OBS Studio, Streamlabs Desktop, Prism Live, dll).

### **Langkah-langkah:**

1. **Download Repository ini** dengan mengklik tombol hijau Code \-\> Download ZIP.  
2. Ekstrak file ZIP tersebut di folder komputer yang aman (jangan dipindah-pindah setelah di-set di OBS).  
3. Buka **OBS Studio**.  
4. Di panel **Sources**, klik tombol \+ lalu pilih **Browser** (Browser Source).  
5. Beri nama (misal: "RV-Tic Overlay") dan klik **OK**.  
6. Centang kotak **"Local file"**.  
7. Klik **Browse** dan cari file index.html (atau file overlay spesifik) di folder yang sudah kamu ekstrak tadi.  
8. Atur resolusi:  
   * **Width:** 1920  
   * **Height:** 1080  
9. *Opsional:* Centang *"Shutdown source when not visible"* agar tidak memakan RAM saat di-hide.  
10. Klik **OK** dan sesuaikan posisinya di layar\!

## **⚙️ Cara Kustomisasi (Ubah Nama / Warna)**

Anda dapat mengubah tampilan overlay agar sesuai dengan tema *channel* Anda\!

1. Buka folder overlay yang sudah di-download.  
2. Cari file config.js atau style.css (tergantung di mana letak pengaturan file kamu).  
3. Buka menggunakan teks editor (seperti Notepad, Notepad++, atau VS Code).  
4. Ubah variabel warna atau teks yang tersedia:  
   /\* Contoh kustomisasi di style.css \*/  
   :root {  
       \--primary-color: \#ff0055; /\* Ubah warna utama di sini \*/  
       \--bg-color: rgba(0, 0, 0, 0.8);  
   }

5. Simpan file (Ctrl \+ S), lalu buka OBS dan klik tombol **"Refresh cache of current page"** di *properties* Browser Source untuk melihat perubahannya.

## **🤝 Kontribusi**

Suka dengan proyek ini? Bantu kami mengembangkannya\!

* Laporkan bug atau *request* fitur melalui tab [Issues](https://www.google.com/search?q=../../issues).  
* Punya modifikasi desain yang keren? Silakan buat [Pull Request](https://www.google.com/search?q=../../pulls).

## **📄 Lisensi & Kredit**

* **Kredit:** Dibuat dengan ❤️ oleh [Ruang Visual](https://www.google.com/search?q=https://github.com/ruangvisual) dan kontributor lainnya.  
* **Lisensi:** Didistribusikan di bawah Lisensi MIT. Lihat file LICENSE untuk informasi lebih lanjut.