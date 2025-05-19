## 🧠 BrainHire – Research Assistant Finder Platform

**BrainHire** adalah platform web modern yang menghubungkan peneliti dengan asisten yang kompeten untuk proyek akademik maupun berbasis data. Baik Anda profesor yang mencari annotator, data scientist yang butuh bantuan pelabelan dataset, atau mahasiswa yang ingin pengalaman riset bermakna, BrainHire membuat kolaborasi jadi mudah, transparan, dan efisien.

### 🚀 Fitur Utama

* 🧪 **Posting Proyek Riset** dengan keahlian yang dibutuhkan, timeline, dan kompensasi
* 👩‍💻 **Temukan Asisten Riset** berdasarkan bidang, tools, dan pengalaman sebelumnya
* 💼 **Smart Matching** engine untuk merekomendasikan kandidat terbaik
* 📝 **Workspace Kolaboratif** untuk manajemen tugas, file, dan feedback
* 🔐 **Verifikasi & Kepercayaan** melalui email akademik atau ORCID ID
* 📊 **Multi-domain Support**: AI/ML, ilmu sosial, eksperimen laboratorium, riset iklim, dan lainnya

---

### 🛠️ Teknologi yang Digunakan

| Lapisan          | Teknologi                 |
| ---------------- | ------------------------- |
| Frontend         | Next.js, Tailwind CSS     |
| Backend          | Express.js (Node.js)      |
| Database         | PostgreSQL, Redis         |
| Otentikasi       | Firebase Auth / ORCID     |
| Penyimpanan File | AWS S3 / Firebase Storage |
| Deployment       | Vercel / Railway / Fly.io |

---

### 📂 Struktur Kode

```
brainhire/
├── frontend/          # Next.js client web
│   ├── pages/
│   ├── components/
│   └── utils/
├── backend/           # Express API dengan REST endpoints
│   ├── routes/
│   ├── models/
│   └── controllers/
├── prisma/            # Skema & migrasi DB PostgreSQL
├── public/            # Aset statis
├── scripts/           # Seeder & utilitas
└── README.md
```

---

### 📈 Roadmap

* [x] MVP: Posting proyek & profil asisten
* [x] Otentikasi (email + sosial)
* [ ] Sistem smart match (tf-idf / embeddings)
* [ ] Dashboard manajemen tugas
* [ ] Fitur chat & berbagi file
* [ ] Integrasi akademik (ORCID, pembuat sitasi)

---

### 🤝 Kontribusi

Kami menyambut kontribusi dari peneliti, pengembang, dan penggemar open-source. Silakan cek [CONTRIBUTING.md](./CONTRIBUTING.md) dan jangan ragu buka issue atau pull request.

---

### 📄 Lisensi

MIT License — lihat [LICENSE](./LICENSE) untuk detail.

---

Kalau kamu mau, aku juga bisa bikinkan versi formal atau bilingual (Inggris–Indonesia). Mau lanjut ke bagian *badges* untuk README atau *deployment guide* dengan Next.js, Tailwind, NextAuth, Prisma, dan shadcn?
