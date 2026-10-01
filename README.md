# 🌏 Nusantara Cerdas

**Nusantara Cerdas** adalah platform edukasi digital yang dirancang untuk mendukung pembelajaran interaktif berbasis teknologi.  
Proyek ini menggunakan **Express.js** dan **TypeScript** sebagai fondasi backend modern dengan arsitektur yang scalable, aman, dan maintainable.

---

## 🚀 Fitur Utama

- 🔐 **Autentikasi & Otorisasi** — login, register, dan validasi token JWT.  
- 👤 **Manajemen Profil Pengguna** — menampilkan dan memperbarui data profil.  
- 📘 **Validasi Data Otomatis** — menggunakan `zod` untuk validasi schema.  
- ⚙️ **Middleware Modular** — rate limiter, helmet, dan cookie parser sudah dikonfigurasi.  
- 🧩 **Struktur Kode Terorganisir** — controller, route, schema, dan middleware dipisah.  
- 🧱 **Dukungan TypeScript Penuh** — aman dari error tipe data dan mudah di-maintain.  
- 📊 **Scalable Architecture** — siap dikembangkan untuk integrasi database, cache, dan analitik.

---

## 🧱 Struktur Folder

```bash
.
├── src/
│   ├── controllers/       # Logic utama setiap endpoint (misalnya userProfile)
│   ├── middlewares/       # Middleware seperti validate(), auth(), limiter, dll.
│   ├── routes/            # Definisi semua route (user, auth, profile, dsb)
│   ├── schemas/           # Validasi Zod untuk request body/params
│   ├── utils/             # Helper dan fungsi pendukung
│   └── index.ts           # Entry point aplikasi Express
│
├── tsconfig.json          # Konfigurasi TypeScript
├── package.json           # Dependency dan script npm
├── .env.example           # Template variabel lingkungan
└── README.md              # Dokumentasi proyek
