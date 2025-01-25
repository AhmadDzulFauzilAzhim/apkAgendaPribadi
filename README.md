# Aplikasi Agenda Pribadi
 Aplikasi "apkAgendaPribadi" adalah aplikasi GUI berbasis Java yang dirancang untuk membantu pengguna dalam mengelola agenda pribadi. Dengan aplikasi ini, pengguna dapat menambahkan, mengubah, menghapus, menyimpan, dan memuat agenda ke/dari file teks.

## Fitur Utama
1. **Menambahkan Agenda**
   - Pengguna dapat menambahkan agenda baru dengan mengisi judul dan isi agenda.

2. **Mengubah Agenda**
   - Agenda yang dipilih dapat diperbarui oleh pengguna.

3. **Menghapus Agenda**
   - Agenda yang dipilih dapat dihapus dari daftar agenda.

4. **Membersihkan Form**
   - Form judul dan isi agenda dapat dikosongkan.

5. **Ekspor ke File**
   - Agenda yang dipilih dapat disimpan ke file teks.

6. **Impor dari File**
   - Pengguna dapat memuat agenda dari file teks ke dalam aplikasi.

7. **Keluar**
   - Aplikasi dapat ditutup dengan tombol keluar.

## Struktur Program
- **GUI Komponen**
  - `JList<String> listAgenda`: Untuk menampilkan daftar agenda.
  - `JTextField judulAgenda`: Untuk input judul agenda.
  - `JTextArea areaAgenda`: Untuk input isi agenda.
  - `JButton`: Tombol untuk berbagai aksi seperti Tambah, Edit, Hapus, dll.

- **Model Data**
  - `DefaultListModel<String>`: Untuk mengelola data dalam `JList`.
  - `HashMap<String, String>`: Untuk menyimpan pasangan judul dan isi agenda.

## Cara Menjalankan
1. Pastikan Anda memiliki Java Development Kit (JDK) yang terinstal di komputer Anda.
2. Salin kode program ke dalam file dengan nama `apkAgendaPribadi.java`.
3. Buka terminal atau Command Prompt, arahkan ke direktori tempat file disimpan.
4. Kompilasi file dengan perintah:
   ```
   javac apkAgendaPribadi.java
   ```
5. Jalankan aplikasi dengan perintah:
   ```
   java apkAgendaPribadi
   ```

## Cara Menggunakan
1. **Menambahkan Agenda:**
   - Isi kolom "Judul" dan "Agenda".
   - Klik tombol "Tambah" untuk menambahkan agenda ke daftar.

2. **Mengubah Agenda:**
   - Pilih agenda dari daftar.
   - Edit kolom "Judul" atau "Agenda".
   - Klik tombol "Edit" untuk menyimpan perubahan.

3. **Menghapus Agenda:**
   - Pilih agenda dari daftar.
   - Klik tombol "Hapus" untuk menghapus agenda dari daftar.

4. **Ekspor ke File:**
   - Pilih agenda dari daftar.
   - Klik tombol "Export" dan pilih lokasi untuk menyimpan file teks.

5. **Impor dari File:**
   - Klik tombol "Import" dan pilih file teks yang ingin dimuat.
   - Agenda dari file akan ditambahkan ke daftar jika judulnya unik.

6. **Keluar:**
   - Klik tombol "Keluar" untuk menutup aplikasi.

## Struktur File
- **Judul Agenda**
  Baris pertama dalam file teks menyimpan judul agenda dengan format:
  ```
  Judul: [judul agenda]
  ```
- **Isi Agenda**
  Baris-baris berikutnya menyimpan isi agenda.

## Catatan
1. Jika judul agenda sudah ada, sistem akan menampilkan pesan error.
2. Jika ada kesalahan saat memuat atau menyimpan file, pesan error akan muncul.

## Teknologi yang Digunakan
- Java Swing: Untuk membuat antarmuka pengguna.
- Java I/O: Untuk membaca dan menulis file teks.

## Pembuat Aplikasi
Ahmad Dzul Fauzil Azhim - 2210010389

## Demo

![App Screenshot](https://github.com/AhmadDzulFauzilAzhim/apkAgendaPribadi/blob/main/img/demo%20aplikasi%20Agenda%20Pribadi.gif)

