### Nama: Muhammad Ikhsan Revaldi
### NIM: 09011282328060
### Kelas : SK3C

### 1. Eksekusi seluruh profile yang ada : 
A. Edit file profile /etc/profile dan tampilkan pesan sebagai berikut :  
>echo “Profile dari /etc/profile” ![Gambar 1-A](https://github.com/Hiratsuu/Praktikum5_Muhammad-Ikhsan-Revaldi_09011282328060/blob/main/Praktikum%205/1-A.png?raw=true)
>![Gambar 1-A-1](https://github.com/Hiratsuu/Praktikum5_Muhammad-Ikhsan-Revaldi_09011282328060/blob/main/Praktikum%205/1-A-1.png?raw=true)

B. Asumsi nama anda stD02001, maka edit semua profile yang ada yaitu :  
>/home/stD02001/.bash_profile ![Gambar 1-B](https://github.com/Hiratsuu/Praktikum5_Muhammad-Ikhsan-Revaldi_09011282328060/blob/main/Praktikum%205/1-B.png?raw=true)
>/home/. stD02001/.bash_login ![Gambar 1-B-2](https://github.com/Hiratsuu/Praktikum5_Muhammad-Ikhsan-Revaldi_09011282328060/blob/main/Praktikum%205/1-B-2.png?raw=true)
>/home/mahasiswa/.profile  ![Gambar 1-B-1](https://github.com/Hiratsuu/Praktikum5_Muhammad-Ikhsan-Revaldi_09011282328060/blob/main/Praktikum%205/1-B-1.png?raw=true)
>/home/mahasiswa/.bashrc  ![Gambar 1-B-3](https://github.com/Hiratsuu/Praktikum5_Muhammad-Ikhsan-Revaldi_09011282328060/blob/main/Praktikum%205/1-B-3.png?raw=true)

Ganti nama /home/mahasiswa dengan nama anda sendiri. Pada setiap file tersebut, cantumkan instruksi echo. 
misalnya pada /home/ mahasiswa/.bash_profile :  echo “Profile dari .bash_profile”  
Lakukan hal yang sama untuk file lainnya, sesuaikan tampilan dengan nama file yang bersangkutan.
 - memeriksa apakah instruksi yang sudah dibuat sebelumnya sudah ada apa belum

>![Gambar 1-B-4](https://github.com/Hiratsuu/Praktikum5_Muhammad-Ikhsan-Revaldi_09011282328060/blob/main/Praktikum%205/1-B-4.png?raw=true)

C. Jalankan instruksi Subtitute user, kemudian keluar dengan perintah exit sebagai berikut:

>$ su mahasiswa  
>$ exit  

kemudian gunakan opsi – sebagai berikut :  
>$ su – mahasiswa  
>$ exit  

Jelaskan perbedaan kedua utilitas tersebut.

>![Gambar 1-C](https://github.com/Hiratsuu/Praktikum5_Muhammad-Ikhsan-Revaldi_09011282328060/blob/main/Praktikum%205/1-C.png?raw=true)

### 2. Prompt String (PS)  
A. Jalankan instruksi subtitute user, kemudian keluar dengan perintah exit sebagai berikut:  
Edit file .bash_profile, ganti prompt PS1 dengan ‘>’. Instruksi export diperlukan dengan 
parameter nama variable tersebut, agar perubahan variable PS1 dikenal oleh semua shell
  
>PS1=‟> „  
>export PS1
>![Gambar 2-A](https://github.com/Hiratsuu/Praktikum5_Muhammad-Ikhsan-Revaldi_09011282328060/blob/main/Praktikum%205/2-A.png?raw=true)

B. Eksperimen hasil P1:

>$ PS1=“\! > “  
>69 > PS1=”\d > “  
>Mon Sep 23 > PS1=”\t > “  
>10:10:20 > PS1=”Saya=\u > “  
>Saya=mahasiswa > PS1=”\w >”  
>~ > PS1=\h >”
>![Gambar 2-B](https://github.com/Hiratsuu/Praktikum5_Muhammad-Ikhsan-Revaldi_09011282328060/blob/main/Praktikum%205/2-B.png?raw=true)

### 3. Logout  
Edit file .bash_logout, tampilkan pesan dan tahan selama 5 detik, sebelum eksekusi logout  

>Echo “Terima kasih atas sesi yang diberikan”  
>Sleep 5  
>clear
>![Gambar 3](https://github.com/Hiratsuu/Praktikum5_Muhammad-Ikhsan-Revaldi_09011282328060/blob/main/Praktikum%205/3-_-1.png?raw=true)
>
