# 09011182328114_TriTusmita_SO_Tugas7

# 1. Hal pertama yang perlu dilakukan sebelum mulai menginstal SSH di Ubuntu adalah memperbarui semua paket apt ke versi terbaru. Untuk melakukan ini, gunakan perintah berikut:
![ssh1](https://github.com/user-attachments/assets/62d9e412-73c9-424a-9dbc-b10f6002f5ba)
![ssh2](https://github.com/user-attachments/assets/812080f8-7e78-472c-a748-b5bbdf9d6070)

# 2. Install SSH terlebih dahulu
![ssh3](https://github.com/user-attachments/assets/3d457e69-ea8a-4615-bb49-687e136e758c)
![ssh4](https://github.com/user-attachments/assets/e179a3b3-66f5-43c1-8a90-8a35a2dd810e)

Pemasangan semua komponen yang diperlukan. Jawab "Ya" untuk semua perintah sistem. 

# 3. Start ssh yang sudah terinstall

Mengaktifkan (enable) sistem SSH setelah terinstal.

![ssh5](https://github.com/user-attachments/assets/62affb86-4392-4ef3-97fa-050ce9ba7bb8)

Untuk memverifikasi bahwa layanan diaktifkan dan berhasil berjalan dengan baik.

![ssh6](https://github.com/user-attachments/assets/c2b048f3-4e28-4b16-a911-f89986c5d210)

Output harus berisi baris Aktif: aktif (berjalan), yang menunjukkan bahwa layanan berhasil berjalan.

Jika ingin menonaktifkan layanan, jalankan: 

![ssh7](https://github.com/user-attachments/assets/1ac64e72-62c8-4a2c-aaaf-740bd1747489)

# 4. Konfigurasikan Firewall

Output harus berisi baris Aktif: aktif (berjalan), yang menunjukkan bahwa layanan berhasil berjalan.

![ssh8](https://github.com/user-attachments/assets/0c6cf986-9dd9-4161-94fb-f9d787bae87d)

Output harus berisi baris Aktif: aktif (berjalan), yang menunjukkan bahwa layanan berhasil berjalan.

![ssh9](https://github.com/user-attachments/assets/16c37ba2-2f66-402f-9153-fcdee522cdb8)

![ssh10](https://github.com/user-attachments/assets/d6735022-b416-403a-94b0-df2e70037727)

# 5. Connect to the server 

![ssh11](https://github.com/user-attachments/assets/2f3a9f0c-6b76-4bf4-9267-7fa56a8168c8)
![ssh12](https://github.com/user-attachments/assets/ecae5bed-ab7a-4f02-82a7-8ac7820c50c4)

masuk ke server teman.

# 6. Configure SSH

Setelah menyelesaikan lima langkah sebelumnya, Anda sudah dapat terhubung ke server dari jarak jauh. Namun, Anda dapat lebih meningkatkan keamanan koneksi dengan mengubah port koneksi default ke port lain atau mengubah otentikasi kata sandi menjadi otentikasi kunci. Perubahan ini dan lainnya memerlukan pengeditan file konfigurasi SSH.

Pengaturan server OpenSSH utama disimpan di file konfigurasi utama sshd_config (lokasi: /etc/ssh). Sebelum mulai mengedit, Anda harus membuat cadangan file ini: 

![ssh13](https://github.com/user-attachments/assets/6fb562bd-52b5-4ac7-9fdc-f141df5a0751)

Setelah membuat cadangan, dapat melanjutkan untuk mengedit file konfigurasi. Untuk melakukan ini, buka menggunakan editor nano:

![ssh18](https://github.com/user-attachments/assets/466eb9af-fa43-48b9-bace-ac0c8d9f3236)

Dalam file, ubah port menjadi yang lebih aman. Yang terbaik adalah mengatur nilai dari rentang dinamis port (49152 - 65535) dan menggunakan nomor yang berbeda untuk keamanan tambahan. Misalnya, mari kita ubah nilai port menjadi 49532. Untuk melakukan ini, kami menghapus komentar baris yang sesuai dalam file dan mengubah port seperti yang ditunjukkan pada tangkapan layar di bawah ini.

![ssh14](https://github.com/user-attachments/assets/49eafa70-5f71-45a3-ba72-5b1122201d0b)

Selain pengaturan ini, sebaiknya ubah mode autentikasi kata sandi ke mode autentikasi kunci yang lebih aman. Untuk melakukan ini, hapus komentar baris yang sesuai dan pastikan nilainya adalah "Ya", seperti yang ditunjukkan pada tangkapan layar.

![ssh16](https://github.com/user-attachments/assets/bfa8fa78-006e-4a88-83ea-829c259733a7)

Sekarang, mari kita larang masuk ke server sebagai superuser dengan mengubah baris yang sesuai seperti yang ditunjukkan pada gambar di bawah ini.

![ssh15](https://github.com/user-attachments/assets/7e1e2b81-7405-4a40-ac78-eb78609e24e0)

![ssh17](https://github.com/user-attachments/assets/4c99e2c6-c822-451c-aa1b-582344d1eb66)


# Menginstall Putty

1. Update repository terlebih dahulu
   
![putty1](https://github.com/user-attachments/assets/cf7dd349-7f8d-4218-9857-ae760a21a39b)

2. Install Putty
   
![putty2](https://github.com/user-attachments/assets/d7444d7f-0769-4c3e-bb2d-22bebaf32e2d)

3. Menampilkan versi Putty
   
![putty3](https://github.com/user-attachments/assets/0ce08a05-62b9-4c72-8c3f-4c702cab1b28)

4. Tampilan saat putty dibuka
   
![putty4](https://github.com/user-attachments/assets/75214608-0b88-4689-b486-28a5a6120364)
