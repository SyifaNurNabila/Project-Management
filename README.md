# JayaFuture

**Project by:** Syifa Nur Nabila (2023071017)  
**Mata Kuliah:** Project Management IT – Agile Scrum Framework  
**Universitas:** Universitas Pembangunan Jaya  

---

## Deskripsi Proyek

**JayaFuture** adalah platform berbasis web untuk membantu mahasiswa dan alumni UPJ mengakses informasi magang dan mempersiapkan kebutuhan karier secara terintegrasi.  

Fitur utama:  
- Pencarian lowongan magang sesuai jurusan/minat  
- Pengelolaan profil karier  
- Pembuatan CV dan portofolio otomatis  
- Dashboard admin Career Center  

Deliverable: **UI/UX Prototype interaktif** dan dokumentasi proyek (Agile–Scrum).

---

## Struktur Repository
Jaya-Future-main
├── app/
├── bootstrap/
├── config/
├── database/
├── public/
├── resources/
├── routes/
├── tests/
├── docs/ # Dokumentasi PDF & gambar
├── README.md
├── artisan
├── composer.json
├── composer.lock
├── package.json
├── phpunit.xml
└── vite.config.js



> **Catatan:** File desain Figma hanya diakses melalui Notion.

---

## Dokumentasi & Deliverables

- **Project Planning Document (PDF)**: WBS, Gantt, Network Diagram, risiko, timeline, progress log.  
- **UI/UX Prototype**: desain halaman utama, profil, lowongan, dashboard admin (Notion/Figma link).  
- **Source Code Laravel**: struktur kode prototype; backend produksi AI & hosting tidak termasuk.

---

## Instalasi Lokal (Opsional)

```bash
git clone https://github.com/SyifaNurNabila/Project-Management.git
composer install
npm install
cp .env.example .env
php artisan key:generate
php artisan serve

Backend produksi (AI CV Generator & hosting) tidak termasuk.


Struktur Folder Penting

/docs → Dokumentasi proyek (PDF & gambar)

/app, /resources, /routes → Kode Laravel prototype

/tests → Unit & feature tests

Kontribusi

Proyek ini pekerjaan individu untuk mata kuliah Project Management IT. Pertanyaan/feedback via email atau Notion proyek.

Lisensi

Hak cipta © 2025 Syifa Nur Nabila. Semua hak dilindungi. File Figma hanya di Notion; dilarang disalin/distribusi tanpa izin.

Link Terkait

Notion Project: [Link Notion JayaFuture]

GitHub Repository: https://github.com/SyifaNurNabila/Project-Management
