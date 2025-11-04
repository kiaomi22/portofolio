# **Laporan Pengerjaan Tugas Akhir: Website Portofolio Git Workflow**

## **Deskripsi Proyek** 

Website ini merupakan portofolio statis yang dikembangkan menggunakan teknologi HTML5 dan CSS3. Di dalamnya terdapat beberapa bagian utama seperti profil pribadi, daftar kompetensi (skills), proyek unggulan, serta formulir kontak. Proyek ini dibuat sebagai media latihan untuk memahami dan menerapkan dasar-dasar pengembangan web serta penggunaan sistem kontrol versi Git.

Dokumentasi berikut menjelaskan secara bertahap proses pembangunan website ini berdasarkan riwayat commit yang tercatat dalam repository Git.

# Step 1: Inisialisasi dan Commit Bertahap

Proyek ini diawali dengan pembuatan repository Git secara lokal, kemudian dilanjutkan dengan pengembangan website secara bertahap, dimulai dari setiap section. Setelah satu bagian selesai, langsung dilakukan commit agar riwayat perubahan tersusun secara teratur dan mudah dilacak.

1. Langkah awalnya adalah membuka terminal, lalu berpindah ke direktori tempat proyek disimpan.  
   cd d:SEMESTER\\ 5/Praktikum\\ Pemrograman\\ Web/ TA2  
   <img width="552" height="97" alt="image" src="https://github.com/user-attachments/assets/4aad3c78-267e-43aa-b884-9b438355c0b8" />
  
2. Inisialisasi Proyek Repository Git lokal dibuat di dalam folder proyek.  
   git init  
   <img width="777" height="99" alt="image" src="https://github.com/user-attachments/assets/cee60ca6-e8af-4ea8-80c1-570d23ccd789" />
  
3. Commit \#1: Struktur Dasar

   Tahap pertama adalah menyusun kerangka utama website dengan HTML dan CSS. Di sini dibuat struktur dasar halaman, file CSS, serta pengaturan awal seperti variabel warna, font global, dan reset CSS.

   Pesan Commit “Proyek struktur HTML & CSS dasar”

   <img width="752" height="260" alt="image" src="https://github.com/user-attachments/assets/c50cb70b-0b87-4e3b-83a3-506f34464884" />


4. Commit \#2: Header & Navigasi  
   Selanjutnya, ditambahkan elemen \<header\> yang berisi logo serta menu navigasi utama untuk berpindah antar bagian situs.  
   Pesan Commit: Tambah Header dan Navigasi

   <img width="756" height="163" alt="image" src="https://github.com/user-attachments/assets/0b8f1f07-7e98-448b-93d0-c9d43e74c1ea" />


5. Commit \#3: Section Tentang Saya  
   Pada tahap ini, dibuat section Tentang Saya yang berisi foto profil, deskripsi singkat, dan tombol ajakan (call-to-action).  
   Pesan Commit: Tambah Section Tentang Saya  
   <img width="768" height="165" alt="image" src="https://github.com/user-attachments/assets/447d06e2-e2a2-49ee-8b0f-151e4fea652c" />
 
6. Commit \#4: Section Kompetensi  
   Kemudian ditambahkan section Kompetensi yang menampilkan daftar kemampuan berupa bahasa pemrograman dan tools, disusun dalam bentuk kartu agar lebih menarik.  
   Pesan Commit: Tambah Section Kompetensi  
   <img width="750" height="166" alt="image" src="https://github.com/user-attachments/assets/552d2a93-3965-4392-85bc-4cc1847dc0e4" />
  
7. Commit \#5: Section Proyek Unggulan  
   Berikutnya, dibangun section Proyek Unggulan yang berisi portofolio atau hasil karya yang pernah dikerjakan.  
   Pesan Commit: Tambah Section Proyek Unggulan  
   <img width="755" height="162" alt="image" src="https://github.com/user-attachments/assets/005c0256-58e0-4c1c-841d-09d11d53b286" />
  
8. Commit \#6: Section Contact & Footer  
   Sebagai penutup, ditambahkan form kontak agar pengunjung dapat menghubungi, serta elemen \<footer\> di bagian bawah halaman.  
   Pesan Commit: Tambah Section Kontak dan Footer  
   <img width="762" height="160" alt="image" src="https://github.com/user-attachments/assets/e18f37a9-c6c1-44e1-a44f-38e86580f96e" />


# Step 2: Eksperimen Styling (Branch)

Untuk menguji ide desain tanpa mengganggu versi utama, dibuat sebuah branch baru bernama eksperimen-styling menggunakan perintah: git checkout \-b eksperimen-styling  
Di branch ini dilakukan percobaan mengganti skema warna utama (variabel \--primary-color di CSS) dari biru muda menjadi biru tua.  
Pesan Commit: style: Eksperimen styling warna   
<img width="866" height="224" alt="image" src="https://github.com/user-attachments/assets/cedf6a62-6e6b-4481-a185-5789c3215151" />


# Step 3: Penggabungan Branch (Merge)

Setelah percobaan dianggap berhasil, perubahan dari branch eksperimen-styling digabungkan ke branch utama (main). git checkout main, git merge eksperimen-styling  
Setelah merge, tampilan utama situs kini menggunakan skema warna biru yang baru.  
<img width="874" height="210" alt="image" src="https://github.com/user-attachments/assets/a7f2e083-6f26-4b00-bdc2-f8f4818bbd74" />


# Step 4: Publikasi ke GitHub

Tahap akhir adalah mempublikasikan proyek ke GitHub agar dapat diakses secara online.  
 Pertama, hubungkan repository lokal dengan repository remote:  
git remote add origin https://github.com/\[username\]/\[nama-repositori\].git  
Lalu, unggah seluruh commit dari branch main: git push \-u origin main  
<img width="766" height="317" alt="image" src="https://github.com/user-attachments/assets/8eb4c6c9-3289-41c6-ac7d-416bc4fa1cc4" />

# Visualisasi Riwayat Commit (git log)
Berikut adalah bukti visual dari seluruh alur kerja yang dijalankan, diambil dari output<img width="755" height="164" alt="image" src="https://github.com/user-attachments/assets/392d6001-32b4-4777-92ea-756a5f83c541" />

