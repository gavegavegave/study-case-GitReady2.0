# Profile Card

Profile Card adalah halaman kartu profil interaktif untuk tiga anggota tim, dengan fitur pergantian anggota, dark mode, dan like counter, dibuat sebagai study case GitReady 2.0 (Git & GitHub).

---

## Visualisasi

<!-- Ganti dengan screenshot halaman kalian (upload ke repo, misalnya folder /screenshots) -->

![Screenshot](screenshots/preview.png)

Live Demo: [link-demo-jika-ada](#)

---

## Tech Stack

- HTML5
- CSS3
- JavaScript (Vanilla)
- Git & GitHub

---

## Fitur Utama

- [x] Pindah profil antar anggota lewat navbar
- [x] Toggle Dark Mode
- [x] Like Counter interaktif (jumlah like tersimpan terpisah untuk tiap anggota selama halaman terbuka)
- [x] Responsive layout (penyesuaian tampilan untuk layar kecil)

---

## Contribution

| Nama | Role | Kontribusi |
|---|---|---|
| Gavriel Miracle | Project Initiator | Membuat repository, mengatur akses kolaborator, commit `index.html` |
| Eunica Valencia | Styling Engineer | Membuat branch `styling`, menambahkan & menghubungkan `style.css` |
| Jessica Gunawan | Script Engineer | Membuat branch `scripting`, menambahkan & menghubungkan `script.js` |

---

## How to Run

1. Clone repository ini:

   ```bash
   git clone <url-repo-kalian>
   ```

2. Buka folder hasil clone, lalu klik dua kali file `index.html` (atau klik kanan → Open with → Browser).

---

## What I Learned

<!-- Draft awal. Ganti dengan pengalaman kalian sendiri, dan pastikan sesuai dengan yang benar-benar dialami. -->

- Cara kerja alur kolaborasi di Git: membuat branch terpisah, commit, push, lalu menggabungkan lewat Pull Request
- Pentingnya code review sebelum merge ke branch `main`
- Cara mengenali dan menyelesaikan merge conflict, terutama saat beberapa orang mengubah file yang sama (`index.html`)
- Menghubungkan file CSS dan JavaScript ke HTML, serta memanipulasi DOM dengan JavaScript
- Membuat dark mode dengan CSS variables dan class toggle

---

## Feature Improvement

- Menyimpan status like counter ke `localStorage` supaya tidak reset saat halaman dimuat ulang
- Menambahkan animasi transisi saat berpindah profil
- Menyempurnakan tampilan agar responsive penuh di mobile
- Deploy otomatis via GitHub Actions ke GitHub Pages
