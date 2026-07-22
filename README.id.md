# upwork-skills

<p align="center"><a href="README.md">English</a> · <strong>Bahasa Indonesia</strong></p>

**Skill AI agent untuk freelancer Upwork, diambil dari playbook asli seorang Top Rated Plus.**

*Proyek komunitas. Tidak berafiliasi dengan dan tidak didukung oleh Upwork.*

Lima skill yang mengubah Claude, Cursor, atau agent apa pun yang kompatibel dengan SKILL.md menjadi operator freelance yang benar-benar kerja: menyaring job sebelum kamu buang Connects, menulis proposal yang menonjol di tengah banjir AI, membalas undangan interview dengan cepat, mengaudit profilmu, dan menangani percakapan klien yang sulit.

Setiap skill dibangun dari dua sumber: panduan resmi yang dipublikasikan Upwork (dikutip di dalam setiap skill) dan playbook nyata seorang freelancer Top Rated Plus (top 3%) yang terdokumentasi. Kalau saran resmi dan hasil di lapangan bertentangan, skill-nya bilang terus terang, dan kasih tahu mana yang menang. Tanpa persona bohongan, tanpa statistik karangan.

## Daftar skill

| Skill | Fungsinya | Pakai saat |
|---|---|---|
| [upwork-job-qualifier](upwork-job-qualifier/SKILL.md) | Verdict untuk job post: apply, skip, atau hati-hati. Hitungan riwayat klien, red flag, ekonomi Connects. | "Job ini layak Connects-ku nggak?" |
| [upwork-proposal-writer](upwork-proposal-writer/SKILL.md) | Menulis proposal dengan metode lima langkah; bisa juga me-review draf yang sudah ada. | "Tulisin proposal buat job ini" |
| [upwork-invitation-responder](upwork-invitation-responder/SKILL.md) | Terima, tolak, atau tolak-sambil-referensikan sebuah Invitation to Interview. | "Ada klien ngundang, bantu bales" |
| [upwork-profile-optimizer](upwork-profile-optimizer/SKILL.md) | Audit profil dengan skor dan prioritas perbaikan, termasuk lapisan AI-search (AEO). | "Kenapa aku nggak dapat invite?" |
| [upwork-client-messenger](upwork-client-messenger/SKILL.md) | Pesan di tengah kontrak: kabar delay, scope creep, naik rate, menutup kontrak, minta review. | "Klien nambah scope terus" |

Kelimanya menutup satu siklus penuh: memilih dengan benar, terpilih, mudah ditemukan, dan menjaga hubungan kerja.

## Cara pasang

Dengan [skills CLI](https://skills.sh):

```bash
npx skills add abullaisi/upwork-skills --all
```

Atau manual: salin folder skill mana pun ke direktori skills agent-mu (`.claude/skills/` untuk Claude Code), lalu skill-nya aktif di sesi berikutnya.

## Jalan pintas profil

Setiap skill membaca file opsional `upwork-profile.md` dari direktori kerjamu atau `~/.claude/`: satu baris identitas, niche, link portofolio, dan rate. Simpan sekali, dan skill-nya berhenti nanya berulang-ulang. Contoh:

```markdown
# Profil freelance-ku
- Peran: desainer UI/UX, 5+ tahun, dashboard SaaS
- Rate: rate per jam kamu
- Portofolio: 3-5 link yang benar-benar kamu kirim ke klien
```

## Kenapa pakai ini, bukan sekadar tanya AI

AI bawaan Upwork sekarang menuliskan proposal untuk semua freelancer di platform, gratis. Justru itu masalahnya: output AI generik jadi standar minimum yang di-scroll lewat oleh klien. Skill-skill ini memuat bagian yang tidak akan pernah diberikan tool platform: penilaian job mana yang harus di-skip (platform untung kalau kamu makin sering apply, bukan makin jarang), metode proposal dengan koreksi lapangan yang memenangkan kontrak sungguhan, dan langkah percakapan klien yang teruji di thread nyata. Semua sumber dikutip di setiap file, jadi kamu bisa cek sendiri.

## Kontribusi

Kontribusi terbuka, dan yang kecil pun berarti:

- **Koreksi**: panduan yang sudah basi, mekanik platform yang berubah.
- **Terjemahan**: skill mana pun, bahasa apa pun. Versi Bahasa Indonesia adalah tujuan utama, bukan tambahan.
- **Skill baru**: keterampilan Upwork lainnya (pricing, persiapan portofolio, workflow niche) cocok di sini. Platform lain layak dapat pack sendiri. Buka issue dulu supaya scope-nya disepakati.

Aturan rumahnya: suara manusia yang wajar, tanpa statistik karangan, sumber dikutip, tanpa nama klien atau rate asli di contoh, dan tanpa scraping atau otomasi yang melanggar ketentuan platform mana pun.

## Lisensi dan disclaimer

MIT. Pakai, fork, kembangkan.

Proyek ini tidak berafiliasi dengan dan tidak didukung oleh Upwork. Kata "Upwork" dipakai secara deskriptif, karena memang platform itulah yang dibahas.

Dibangun oleh [Imam Abullaisi](https://github.com/abullaisi) dan komunitas Wargi Freelance (komunitas freelancer Indonesia, 950+ anggota). Repo pelajaran yang jadi asal pack ini menyusul berikutnya.
