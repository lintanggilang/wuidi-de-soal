# Persiapan AWS Certified Data Engineer — Associate (DEA-C01)

Materi persiapan sertifikasi **AWS Certified Data Engineer – Associate (DEA-C01)** dalam Bahasa Indonesia, dikemas sebagai situs statis (HTML + CSS, tanpa dependensi/build). Nama layanan, parameter, dan istilah teknis AWS sengaja dipertahankan dalam bahasa aslinya agar sesuai dengan soal ujian.

## Isi

| Halaman | Keterangan |
|---------|------------|
| `index.html` | Halaman utama / daftar navigasi ke seluruh materi |
| `AWS-Certified-Data-Engineer-Associate_Exam-Guide.html` | Panduan ujian resmi — cakupan, domain, dan format ujian |
| `aws-de-belajar.html` | Checklist belajar interaktif: jebakan per layanan + contoh soal, progres tersimpan otomatis di browser |
| `de1.html` – `de6.html` | Ringkasan jawaban latihan soal — total **390 soal** (65 per file) |
| `Exam_Quick_Reference__Cheat_Sheet.pdf` | Lembar contekan referensi cepat |
| `assets/style.css` | Gaya tampilan bersama |
| `favicon.svg` | Favicon tanda petir |

## Struktur tiap soal

Setiap soal pada `de1`–`de6` memuat:

- **Soal** (qtext) dan **Jawaban benar** (answer)
- **Karena** — penjelasan alasan jawaban
- **Tips** — pola hafalan ringkas berformat *"Jika {masalah} maka {jawaban} karena {alasan}"*, sering dilengkapi blok **Ingat:** berisi fakta kunci (angka, limit, port, perbandingan antar-layanan)

Fitur pada halaman soal: pencarian, buka/tutup semua, tandai sudah dibaca, tandai untuk review, dan progres tersimpan otomatis di `localStorage`.

## Cara menjalankan

Cukup buka file HTML langsung di browser, mulai dari `index.html`. Tidak perlu server atau proses build.

Opsional, jalankan lewat server statis lokal:

```bash
# Python
python -m http.server 8000
# lalu buka http://localhost:8000
```

## Catatan

Materi ini untuk tujuan belajar. Selalu rujuk [dokumentasi AWS resmi](https://docs.aws.amazon.com/) untuk angka, limit, dan perilaku layanan terbaru.

---

Dibuat oleh **Lintang Gilang** dengan bantuan **Kiro Agent**.
