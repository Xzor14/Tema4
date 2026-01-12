# 💍 Luxury Gold Digital Wedding Invitation

Undangan pernikahan digital berbasis web dengan desain **Luxury Gold (Black & Gold)** yang elegan dan premium. Dibangun menggunakan HTML, CSS, dan JavaScript modern dengan sentuhan animasi yang halus untuk pengalaman pengguna yang maksimal.



## ✨ Fitur Utama

* **Opening Cover:** Tampilan pembuka dengan fitur "Buka Undangan" dan nama tamu otomatis (via URL parameter).
* **Premium Design:** Tema warna Emas & Hitam dengan efek Glassmorphism.
* **Smooth Animations:** Integrasi **GSAP (GreenSock)** dan **ScrollTrigger** untuk animasi elemen yang memukau.
* **Smooth Scroll:** Menggunakan **Lenis** untuk pengalaman scrolling yang sangat halus.
* **Real-time Countdown:** Hitung mundur waktu menuju acara (JavaScript).
* **Interactive Gallery:** Galeri foto grid dengan efek zoom dan fitur Lightbox (UIkit).
* **Audio Player:** Background music dengan tombol kontrol (Play/Pause) piringan hitam berputar.
* **RSVP to WhatsApp:** Formulir konfirmasi kehadiran yang langsung terhubung ke chat WhatsApp.
* **Responsive:** Tampilan optimal di Mobile, Tablet, dan Desktop.

## 🛠️ Teknologi yang Digunakan

* **HTML5 & CSS3**
* **JavaScript (Vanilla)**
* **[UIkit](https://getuikit.com/)** - Framework CSS & JS (Lightbox, Grid).
* **[GSAP](https://greensock.com/gsap/)** - Library animasi performa tinggi.
* **[Lenis](https://github.com/studio-freight/lenis)** - Smooth scrolling library.
* **[FontAwesome](https://fontawesome.com/)** - Ikon vektor.
* **Google Fonts** - (Cinzel Decorative, Pinyon Script, Cormorant Garamond).

## 🚀 Cara Penggunaan

1.  **Clone Repository**
    ```bash
    git clone [https://github.com/username-kamu/wedding-invitation-luxury.git](https://github.com/username-kamu/wedding-invitation-luxury.git)
    ```
2.  **Buka File**
    Cukup buka file `index.html` di browser kesayangan Anda.

3.  **Fitur Nama Tamu (Parameter URL)**
    Anda bisa membagikan link dengan nama tamu spesifik:
    `index.html?to=Nama+Tamu`
    *Contoh:* `yoursite.com/?to=Budi+Santoso`

## ⚙️ Cara Kustomisasi

Untuk mengubah data undangan, silakan edit file `index.html`:

1.  **Mengubah Tanggal Countdown:**
    Cari bagian script di bawah ``:
    ```javascript
    const targetDate = new Date("Mar 27, 2027 09:00:00").getTime();
    ```
2.  **Mengubah Nomor WhatsApp RSVP:**
    Cari fungsi `sendWA(e)` di bagian paling bawah script:
    ```javascript
    window.open(`https://wa.me/6281234567890?text=Halo ${n} konfirmasi.`);
    ```
    *Ganti `6281234567890` dengan nomor WhatsApp Anda.*
3.  **Mengubah Musik:**
    Ganti link `src` pada tag `<audio>`:
    ```html
    <audio id="bgMusic" loop src="LINK_MP3_KAMU"></audio>
    ```
4.  **Mengubah Foto:**
    Ganti URL gambar pada tag `<img>` di bagian Hero, Couple, dan Gallery.

## 📂 Struktur File

```text
/
├── index.html      # File utama (Semua kode ada di sini untuk kemudahan)
└── README.md       # Dokumentasi ini
