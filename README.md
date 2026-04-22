# GitHub Repository Finder

Aplikasi web untuk menemukan repositori GitHub secara acak berdasarkan bahasa pemrograman yang dipilih. Dibangun menggunakan HTML, CSS, dan JavaScript murni (Vanilla JS) dengan integrasi GitHub Search API.

---

## 📸 Preview

> Buka `index.html` menggunakan Live Server di VS Code untuk melihat hasilnya.

---

## ✨ Fitur

- Pilih bahasa pemrograman dari dropdown menu
- Menampilkan repositori GitHub secara acak sesuai bahasa yang dipilih
- Informasi repositori yang ditampilkan:
  - Nama repositori (link langsung ke GitHub)
  - Deskripsi repositori
  - Jumlah ⭐ Stars
  - Jumlah 🍴 Forks
  - Jumlah open issues
  - Bahasa pemrograman dengan warna indikator
- Tombol **Refresh** untuk mengambil repositori acak lainnya
- Tombol **Click to retry** saat terjadi error
- Penanganan berbagai UI state: Empty, Loading, Error, dan Success

---

## 🛠️ Teknologi yang Digunakan

- **HTML5** — Struktur halaman
- **CSS3** — Styling dan animasi
- **JavaScript (ES6+)** — Logika aplikasi dan async/await
- **GitHub Search API** — Sumber data repositori
- **Google Fonts (Inter)** — Tipografi

---

## 📁 Struktur Proyek

```
github-repository-finder/
└── index.html
```

---

## 🚀 Cara Menjalankan

1. Clone atau download repositori ini
2. Buka folder proyek di **VS Code**
3. Klik kanan pada file `index.html`
4. Pilih **"Open with Live Server"**
5. Aplikasi akan terbuka otomatis di browser

> Pastikan ekstensi **Live Server** sudah terinstall di VS Code.

---

## 🌐 API yang Digunakan

**GitHub Repository Search API**

```
GET https://api.github.com/search/repositories?q=language:{bahasa}+stars:>500&sort=stars&order=desc&per_page=30&page={halaman_acak}
```

> ⚠️ GitHub API memiliki batas **60 request per jam** tanpa autentikasi. Jika batas tercapai, aplikasi akan menampilkan pesan error yang informatif.

---

## 🗂️ Bahasa Pemrograman yang Tersedia

| Bahasa | Bahasa | Bahasa |
|---|---|---|
| JavaScript | Python | TypeScript |
| Java | C++ | Go |
| Rust | PHP | Ruby |
| Swift | Kotlin | C# |
| HTML | CSS | |

---

## 📌 Catatan

Proyek ini merupakan bagian dari kurikulum **roadmap.sh** untuk Frontend Developer. Tujuan utama proyek ini adalah mempraktikkan:

- Integrasi dengan external API
- Penanganan request asinkron menggunakan `async/await`
- Manajemen berbagai UI state (empty, loading, error, success)
- Pengalaman pengguna yang responsif

---

## 👤 Author

**Alief Ikhsan**  
[github.com/aliefikhsan18-cmd](https://github.com/aliefikhsan18-cmd)





https://roadmap.sh/projects/github-random-repo
