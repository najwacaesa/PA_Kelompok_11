# PA_Pengelollan Data Warga di Kecamatan

**KELOMPOK 11**
**Nama Anggota:**
**1. Harry Chandra ((2209116014)**
**2. Najwa Caesa Pouti Ramadhania Suharizman Poerwo (2209116048)**

Tema pada project kali ini yaitu mengenai “Manajemen Pengelolaan Data Warga di Kecamatan Samarinda Utara”. Pada kecamatan dibutuhkan penyimpanan yang besar guna menyimpan data warga yang ada di kecamatan tersebut. Maka Projek ini kami membuat Aplikasi GUI yang ter connect dengan database MySQL, Sehingga admin dapat mengelola data warga dan menyimpan nya dengan aman dan mudah. 

 **FLOWCHART**
![PA-Halaman-1 drawio (1)](https://github.com/najwacaesa/PA_Kelompok_11/assets/121982112/9c284a07-b70c-4504-9904-1c3e595284ed)
![PA-Halaman-2 drawio (1)](https://github.com/najwacaesa/PA_Kelompok_11/assets/121982112/465f2f28-8a36-449d-8aa9-428a08aab5cc)

**ERD**
![image](https://github.com/najwacaesa/PA_Kelompok_11/assets/121982112/05702fe6-ce2c-48ed-8fe5-61f3c20c5e09)
![image](https://github.com/najwacaesa/PA_Kelompok_11/assets/121982112/514e2c23-e9e5-452a-8b94-7ce4eb4ef169)

**HIERARKI**
![PA-Halaman-3 drawio](https://github.com/najwacaesa/PA_Kelompok_11/assets/121982112/3d6085b4-a9df-400a-b1e4-2f859d8d2b9f)

**PENJELASAN CODING**
![image](https://github.com/najwacaesa/PA_Kelompok_11/assets/121982112/7339f37a-f825-45ca-bc78-3dd7e4d8fd2f)

Berikut Sintaks yang digunakan dalam kode tersebut dapat dijelaskan sebagai berikut:

1. `package cobacobaajasi;`
 Ini adalah pernyataan yang mendefinisikan paket (package) yang digunakan untuk mengorganisasi kelas-kelas Java. Dalam hal ini, paket bernama "cobacobaajasi" digunakan.

2. `import java.sql.*;`
 Ini adalah pernyataan `import` yang digunakan untuk mengimpor seluruh kelas dalam paket `java.sql`, yang diperlukan untuk berinteraksi dengan database SQL.

3. `public class Warga extends Database {`
Ini adalah deklarasi kelas Java dengan nama "Warga" yang didefinisikan sebagai subkelas (extends) dari kelas "Database". Ini berarti kelas "Warga" mewarisi semua properti dan metode yang ada dalam kelas "Database".

4. `private int nik;`
Ini adalah deklarasi variabel instance dengan nama "nik". Variabel ini digunakan untuk menyimpan nomor identifikasi warga.

5. Deklarasi variabel-variabel dengan tipe data `String`
Ini adalah deklarasi variabel instance yang digunakan untuk menyimpan berbagai informasi pribadi warga seperti nama lengkap, alamat, tempat lahir, tanggal lahir, agama, jenis kelamin, status perkawinan, pekerjaan, kewarganegaraan, nomor HP, dan alamat email.

6. `public int getNik() { ... }`
 Ini adalah metode dengan nama "getNik" yang mengembalikan nilai dari variabel "nik". Metode ini digunakan untuk mengambil nilai NIK dari objek "Warga".

7. `public boolean create() { ... }`
 Ini adalah metode yang digunakan untuk membuat data warga baru dalam database. Data warga diambil dari properti-properti kelas "Warga" dan dimasukkan ke dalam tabel "warga" dalam database.

8. `public boolean find(int nik) { ... }`
Ini adalah metode yang digunakan untuk mencari data warga berdasarkan nomor identifikasi (NIK) yang diberikan. Jika data ditemukan, informasi warga tersebut diambil dari database dan diisi ke dalam properti-properti kelas "Warga".

9. `public boolean update() { ... }`
Ini adalah metode yang digunakan untuk memperbarui data warga dalam database berdasarkan NIK. Data yang akan diperbarui diambil dari properti-properti kelas "Warga" dan diperbarui dalam database.

10. `public boolean delete() { ... }`
 Ini adalah metode yang digunakan untuk menghapus data warga dari database berdasarkan NIK.

11. `public static void main(String[] args) { ... }`
Ini adalah metode `main`, yang merupakan titik masuk untuk program Java. Dalam kasus ini, digunakan untuk menguji fungsionalitas kelas "Warga" dengan membuat data warga baru, mencari data warga, dan menghapus data warga dari database.

12. Ada beberapa pemanggilan metode `this.openConnection()`, `this.preparedStatement`, dan lain-lain, yang digunakan untuk mengatur koneksi ke database, mengeksekusi pernyataan SQL, dan menangani pengecualian (exception) jika ada.

Demikian penjelasan mengenai sintaks yang digunakan dalam kode tersebut.. Kode tersebut berfokus pada pengelolaan data warga dalam basis data menggunakan Java.

***OUTPUT**

![image](https://github.com/najwacaesa/PA_Kelompok_11/assets/121982112/eaf87a0a-922b-4a4c-90b7-cff84fe745d4)

ADMIN

![image](https://github.com/najwacaesa/PA_Kelompok_11/assets/121982112/5db85937-1efe-48e8-88e0-d3aeb4bea975)

![image](https://github.com/najwacaesa/PA_Kelompok_11/assets/121982112/44d401a7-1edc-4cd1-973c-5db42291a410)
![image](https://github.com/najwacaesa/PA_Kelompok_11/assets/121982112/ebfc2a76-36d6-49a4-8891-62cbc5191b85)
![image](https://github.com/najwacaesa/PA_Kelompok_11/assets/121982112/601f0665-987e-4f73-8cf8-b7782017884a)
![image](https://github.com/najwacaesa/PA_Kelompok_11/assets/121982112/cbccb525-2be9-4e51-ba0d-7b9443d7e54a)
![image](https://github.com/najwacaesa/PA_Kelompok_11/assets/121982112/2686eb04-cbb9-42fc-a8a2-79e40985195c)



PEGAWAI

![2](https://github.com/najwacaesa/PA_Kelompok_11/assets/121982112/8067bd3a-0243-492e-ba85-f3a507145db0)
![Capture](https://github.com/najwacaesa/PA_Kelompok_11/assets/121982112/f4093c3a-1cec-40b9-bb99-fcc36980dd8e)
![image](https://github.com/najwacaesa/PA_Kelompok_11/assets/121982112/37c927bb-b7ec-4f22-b384-811186d2d9f8)
![image](https://github.com/najwacaesa/PA_Kelompok_11/assets/121982112/d7df8f8b-03d1-4172-b77b-5aa255d4c75e)



