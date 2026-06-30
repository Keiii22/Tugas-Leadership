# Team Manifesto & Kebijakan Komunikasi - Scrum Team

Dokumen ini disusun sebagai pedoman kerja taktis untuk penyelamatan proyek "Aplikasi Mobile Kantin Pintar Kampus" selama 2 minggu ke depan. Aturan ini dibuat demi mencegah terjadinya miskomunikasi, konflik internal, serta burnout pada anggota tim.

---

## 1. SOP Code Review (Aturan Peninjauan Kode)

Untuk memastikan kualitas kode tetap terjaga tanpa merusak hubungan antar-anggota tim, proses Code Review di GitHub wajib mengikuti panduan komunikasi konstruktif berikut:

### Aturan Umum:
* Kritik harus fokus pada kualitas **kode**, bukan menyerang personal atau kemampuan individu.
* Setiap koreksi wajib disertai dengan alasan teknis yang jelas atau solusi alternatif.
* Gunakan bahasa yang santun, apresiatif, dan profesional.

### Contoh Komunikasi:

| ❌ Kalimat yang DILARANG |  Kalimat yang DIANJURKAN |
| :--- | :--- |
| "Kode kamu berantakan banget, pantesan JSON-nya error terus!" | "Disarankan untuk menyamakan key JSON 'user_id' menjadi camelCase 'userId' sesuai dokumentasi awal agar tidak terjadi crash saat parsing data di frontend. Terima kasih." |
| "Hapus fungsi ini. Gak guna dan bikin lemot." | "Fungsi ini sepertinya bisa dioptimalkan menggunakan query yang lebih sederhana agar tidak membebani performa database. Bagaimana menurutmu?" |
| "Jangan asal merge kode kalau belum beres!" | "Mohon pastikan seluruh unit testing sudah pass terlebih dahulu sebelum mengajukan Pull Request (PR) ya, agar meminimalisir bug di branch utama." |

---

## 2. Protokol Komunikasi & Anti-Burnout

Demi menjaga kesehatan mental tim dan manajemen diri yang baik, aturan komunikasi digital diatur sebagai berikut:

* **Jam Kerja Komunikasi:** Koordinasi aktif, diskusi teknis, dan chat mengenai tugas dilakukan pada hari kerja mulai pukul **08.00 hingga 17.00 WIB**.
* **Batas Akhir Chat (Curfew):** Dilarang keras melakukan chat koordinasi atau membahas progres tugas di atas pukul **21.00 WIB** agar anggota tim dapat beristirahat.
* **Pengecualian (Emergency Protocol):** Aturan jam malam (di atas pukul 21.00 WIB) hanya boleh dilanggar jika terjadi kondisi darurat kritis, seperti server production mati total (*system down*) menjelang deployment.
