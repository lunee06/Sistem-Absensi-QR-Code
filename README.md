
# 📄 Penawaran Aplikasi Web Absensi QR Code Sederhana

## 1. Pendahuluan

Kami menawarkan aplikasi absensi berbasis QR Code yang dirancang secara sederhana namun efektif untuk kebutuhan pencatatan kehadiran karyawan. Sistem ini memungkinkan proses absensi yang cepat, tanpa alat tambahan khusus, dan mudah dikelola oleh admin dan supervisor.

---

## 2. Fitur Utama

### 👥 Login 3 Level

1. **Admin**: Mengelola data karyawan, melakukan scan QR untuk absensi, melihat & ekspor laporan.
2. **Supervisor (SPV)**: Melihat dan memantau laporan kehadiran.
3. **Karyawan**: Melihat QR code pribadi untuk keperluan absensi.

---

### 📲 Absensi Menggunakan QR Code

- QR Code bersifat **unik per karyawan** dan **tetap** (tidak berubah setiap hari).
- **Admin yang melakukan scan** QR saat karyawan hadir dan pulang menggunakan perangkat (HP/laptop) yang terhubung dengan aplikasi.
- Sistem otomatis mencatat waktu **"Masuk"** dan **"Pulang"**, tergantung status terakhir.

---

### 📍 Geolokasi Saat Scan (Untuk Admin)

- Saat admin scan QR, sistem otomatis menyimpan data lokasi (GPS) sebagai validasi tempat absensi.

---

### 📁 Rekap Kehadiran

- Rekap harian, mingguan, dan bulanan.
- Supervisor dan Admin dapat melihat status:
  - Hadir
  - Terlambat
  - Pulang cepat
  - Tidak hadir

---

### 📤 Export Data ke Excel

- Admin dan SPV bisa unduh laporan kehadiran dalam format **.xlsx** sesuai tanggal atau karyawan tertentu.

---

## 3. Tampilan Dasar per Role

### 👨‍💼 Karyawan
- Melihat QR code pribadi.
- Informasi status kehadiran hari ini.

### 🛠️ Admin
- Scan QR dari kamera/webcam untuk proses absensi.
- Melihat dan mengelola data karyawan.
- Mengakses dan ekspor laporan.

### 👨‍✈️ Supervisor
- Melihat rekap kehadiran semua karyawan.
- Filter berdasarkan tanggal dan nama.

---

## 4. Teknologi yang Digunakan

| Komponen     | Teknologi             |
|--------------|------------------------|
| Backend      | Laravel / Node.js      |
| Frontend     | React / Tailwind CSS   |
| Database     | MySQL / PostgreSQL     |
| QR Scanner   | Webcam/Camera support  |
| Export       | XLSX via server-side   |
| Hosting      | Cloud / VPS            |

---

## 5. Keuntungan Sistem Ini

✅ Tidak perlu generate QR setiap hari  
✅ Proses absensi cepat dan efisien  
✅ Admin cukup scan QR dari dashboard  
✅ Data aman dan dapat dicadangkan  
✅ Sistem bisa berjalan di HP, tablet, atau laptop

---

## 6. Estimasi Pengerjaan

| Fase                       | Durasi              |
|----------------------------|---------------------|
| Setup UI/UX dan alur scan  | 3 hari kerja         |
| Pengembangan fungsi utama  | 5 – 7 hari kerja     |
| Testing & revisi ringan    | 2 hari kerja         |
| **Total estimasi**         | **10 – 12 hari kerja**|

---

## 7. Penutup

Sistem absensi QR Code sederhana ini adalah solusi tepat untuk perusahaan yang menginginkan proses kehadiran yang modern, praktis, dan efisien tanpa beban teknis yang rumit.

Kami siap bekerja sama dalam implementasi dan pelatihan singkat agar sistem ini dapat langsung digunakan oleh seluruh tim Anda.
