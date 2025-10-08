# ✅ To-Do List App – Aplikasi Manajemen Tugas Berbasis Web  

<img width="1920" height="1080" alt="Screenshot 2025-10-08 200712" src="https://github.com/user-attachments/assets/33edf00d-8cbd-4403-9364-9e34f3e355d5" />

<img width="1920" height="1080" alt="Screenshot 2025-10-08 200656" src="https://github.com/user-attachments/assets/45346d1e-0da0-492a-b545-30e9c63e589c" />


**To-Do List App** adalah aplikasi berbasis web yang membantu pengguna dalam **mengatur dan memantau tugas** secara efisien.  
Aplikasi ini memungkinkan pengguna untuk **menambah, mengedit, menghapus, dan menandai task** sesuai progres pengerjaan, serta **melacak status tugas** menggunakan dropdown status yang interaktif.  

---

## 🎯 Tujuan Aplikasi
- Membantu pengguna mengelola daftar tugas harian secara rapi dan efisien.  
- Memberikan tampilan yang **interaktif, sederhana, dan elegan** agar nyaman digunakan.  
- Menyediakan fitur **autentikasi akun (Register & Login)** untuk keamanan data pengguna.  
- Mengimplementasikan **keamanan input** dari ancaman *SQL Injection* dan *XSS*.  

---

## 🌍 Struktur Halaman & Fitur Utama

### 🔐 **Login & Register Page**
- Pengguna wajib **daftar (register)** terlebih dahulu sebelum bisa menggunakan aplikasi.  
- Sistem login dengan **validasi input** dan proteksi dari SQL Injection.  
- Password pengguna disimpan secara aman (menggunakan hash).  

### 🏠 **Dashboard – To Do List**
Menampilkan seluruh daftar tugas milik user yang telah login.  
Setiap task memiliki informasi:
- 📛 **Judul Task**
- 🗓️ **Due Date**
- 📝 **Deskripsi Task**
- 📊 **Status (Progress)** – dapat diubah melalui dropdown:
  - Not Yet Started  
  - In Progress  
  - Waiting On  
  - Completed  

### ➕ **Add Task**
- Form untuk menambahkan task baru dengan detail:
  - Judul Task  
  - Due Date  
  - Deskripsi  
  - Status Awal  
- Task baru otomatis muncul di list setelah ditambahkan.

### ✏️ **Edit Task**
- Mengubah detail task yang sudah dibuat.  
- Data akan otomatis diperbarui setelah disimpan.

### ✅ **Mark as Done**
- Checkbox untuk menandai task sebagai selesai.  
- Task yang ditandai selesai akan **berpindah ke bagian bawah list**.

### 🗑️ **Delete Task**
- Menghapus task dari daftar dengan **konfirmasi sebelum penghapusan**.

---

## 🧠 Keamanan Aplikasi
Aplikasi ini dirancang dengan perhatian khusus terhadap **keamanan data pengguna**, mencakup:
- 🔒 **Prepared Statements** → Mencegah *SQL Injection*.  
- 🧼 **Input Sanitization** → Melindungi dari *Cross-Site Scripting (XSS)*.  

---

## 🧰 Teknologi & Tools

| Kategori | Teknologi / Tools |
|-----------|------------------|
| 💻 **Bahasa Pemrograman** | HTML, CSS, JavaScript, PHP Native |
| 🗄️ **Database** | MySQL |
| 🎨 **UI Styling** | CSS Bootstrap |
| 💻 **Code Editor** | Visual Studio Code |
| 🔒 **Keamanan** | SQL Injection & XSS Protection |
| 🚀 **Server Local** | Laragon |
| 🔄 **Version Control** | Git & GitHub |

---

## 🧭 Navigasi Utama

| Halaman | Deskripsi |
|----------|------------|
| 🔐 Login / Register | Autentikasi pengguna |
| 🏠 Dashboard | Tampilan utama daftar tugas |
| ➕ Add Task | Tambah tugas baru |
| ✏️ Edit Task | Ubah detail tugas |
| ✅ Mark as Done | Tandai tugas selesai |
| 🗑️ Delete Task | Hapus tugas dari daftar |

---

## 👨‍💻 Tim Pengembang

| No | Nama Lengkap | NIM |
|----|---------------------------|-----------|
| 1  | **Marcellus Eugene Kaparang** | 00000082420 |
| 2  | **Farrelius Kevin** | 00000081783 |
| 3  | **Merhandes Gunawan** | 00000081070 |
| 4  | **Genadi Ikhsan Jaya** | 00000080773 |
| 5  | **Nicholas Terence Siahaan** | 00000075128 |

---

## 🏫 Mata Kuliah

**Pemrograman Web** – `IF330` – *Semester 3*  
**Program Studi Informatika**  
**Fakultas Teknik dan Informatika**  
🏫 **Universitas Multimedia Nusantara (UMN)**
