**NAMA  : MOCH. DZAKY MUSYADDAD**                                                                                                                                                
**NIM   : 362358302011**                                                                                                                                                       
**KELAS : 2A TRPL**                                                            


**A. KOMPONEN**
1. Button

   <img width="574" alt="image" src="https://github.com/user-attachments/assets/37786ec1-9eab-4ff2-a8fd-7fc6601c6eb1">

   - Keterangan : class ini saya gunakan untuk mempermudah saya dalam membuat button(tombol). Sehingga nanti disaat saya membutuhkan tombol di suatu halaman saya cukup memanggil class ini dan merubah komponen-komponen dalamnya sesuai dengan kebutuhan.

2. Scaffold

   <img width="556" alt="image" src="https://github.com/user-attachments/assets/5f01316f-b54f-4f4b-8f64-98ad66449417">

   - Keterangan : class scaffold ini saya gunakan sebagain template background. Sehingga nanti saya depat memanggil class ini saat saya ingin menggunakannya. Dengan adanya ini pekerjaan kita akan sedikit berkurang karena tidak mengulang saat membuat scaffold di beberapa halaman yang ingin dibuat.

3. Warna

     <img width="311" alt="image" src="https://github.com/user-attachments/assets/d0b6d385-c1be-4f44-afaa-cee723591ec9">

   - Keterangan : class warna ini saya gunakan sebagai template warna. Dimana terdapat beberapa warna yang saya butuhkkan. Agar nantinya saya dapat lebih mudah dalam menentukan warna. Karena sebelumnya sudah saya identifikasikan menjadi beberapa class tertentu. Sehingga disaat saya ingin menggunakan salah satu dari warna tersebut saya cukup memanggil variable warnanya saja.


4. Item

   <img width="644" alt="image" src="https://github.com/user-attachments/assets/9289d8d7-06e1-4d19-8b0e-e1059063ef35">

   - Keterangan : Pada file ini saya membuat class atribut untuk menyimpan data static pada username dan email agar nanti dapat digunakan oleh semua halaman dengan data yang sama. Saya juga membuat class itemprofil yang berisikan subtittle, tittle dan icon. Fungsinya untuk mempermudah saya dalam melakukan modifikasi pada tampilan profil. Sehingga hanya mengganti beberapa nilai pada setiap komponennya sesuai dengan kebutuhan.


5. Library

   <img width="356" alt="image" src="https://github.com/user-attachments/assets/137e14f1-c264-4452-9f9d-78b8bb427525">

   - Keterangan : Saya juga menggunakan beberapa library yang terdapatt di internet. Diantaranya yakni cool_alert dan font_awewome_flutter. Untuk cool_alert sendiri saya gunakan sebagai template dari dialog alert, yang saya terapkan pada halaman daftar. Kemudian untuk font_aweswome_flutter saya gunakan untuk mengambil beberapa dokumentasi icon pada library tersebut yang terapkan pada halaman daftar dan masuk di bagian icon alternatifnya. Diantaranya yaitu icon facebook, icon google, icon twitter, dan icon apple.



      



   
  


**B. TAMPILAN**
1. **Tampilan Utama (Wellcome)**
   
   ![WhatsApp Image 2024-10-24 at 22 44 46_4d811d59](https://github.com/user-attachments/assets/89319e1b-f168-4760-9cdb-49ebf3c65e6e)

- Keterangan : Tampilan awal sebelum memasuki halaman masuk dan daftar. Dimana pada halaman ini tersedia 2 button, yakni masuk(nantinya akan menuju ke halaman masuk dan daftar(nantinya akan menuju ke halaman daftar). Diantara keduanya menggunakan perintah Navigator Push.

2. **Tampilan Sig In(Daftar)**
   
   ![WhatsApp Image 2024-10-24 at 22 44 59_cc0578ee](https://github.com/user-attachments/assets/92cdf583-b01d-43a3-a4b9-7f30dd796577)
   
   ![WhatsApp Image 2024-10-24 at 22 45 05_0a8fec09](https://github.com/user-attachments/assets/385e8345-77cd-414d-ba81-3ddbc784bba1)

- Keterangan : Pada tampilan login ini terdapat beberapa koomponen yakni judul, field kolom, button, dan teks inkwell untuk menuju ke halaman masuk, serta saya menambahkan beberpa atribut seperti checklist, icon platform alternatif, dan inkwell lupa password.


3. **Tampilan Alert Dialog Daftar**

   ![WhatsApp Image 2024-10-24 at 22 45 13_6718966c](https://github.com/user-attachments/assets/4dfd1037-3912-42f7-801b-3e6e7bf6c01d)

- Keterangan : Tampilan alert dialog ini akan muncul setelah menekan tombol daftar. Alert ini sebagai notifikasi bahwasannya proses daftar berhasil dilakukakan. Setelah memencet tombol oke akan otomatis diarahkan ke halman masuk.

4. **Tampilan Login(Masuk)**

   ![WhatsApp Image 2024-10-24 at 22 45 21_a5ace7d4](https://github.com/user-attachments/assets/f39a33dd-8195-44ca-a852-8f12d3b4f13c)

- Keterangan :  Pada tampilan login ini terdapat beberapa komponen yakni judul, field kolom, button, dan teks inkwell untuk menuju ke halaman profil, serta saya menambahkan beberpa atribut seperti checklist, icon platform alternatif, dan inkwell lupa password.


5. **Tampilan Alert Dialog Masuk**

   ![WhatsApp Image 2024-10-24 at 22 45 29_86bb2cf7](https://github.com/user-attachments/assets/ececb748-08dc-4078-83bb-a3c77b5b1c82)

- Keterangan : Tampilan alert dialog otomatis akan muncul setelah menekan tombol masuk. Alert ini digunakan sebagai notifikasi bahwasannya proses masuk berhasil dilakukakan. Setelah memencet tombol lanjutkan akan otomatis diarahkan ke halman profil.

6. **Tampilan Profil**

   ![WhatsApp Image 2024-10-24 at 22 45 43_c21c1ec4](https://github.com/user-attachments/assets/089fa963-4b96-4942-8807-9c4b0ac027c9)

- Keterangan : Tampilan ini berisikan informasi-informasi pengguna/user. Diantaranya yakni nama, email, alamat, dan nomor telepon. Pada tampilan ini juga terdapat beberapa komponen penting yaitu circle avatar yang dugunakan sebagai fot profil pengguna/user, field kolom digunakan sebagai tempat informasi-informasi pengguna, Kemudian tombol keluar yang digunakkan untuk keluar dari aplikasi.

 7. **Tampilan Alert Dialog Keluar**

    ![WhatsApp Image 2024-10-24 at 22 45 53_8d22aa3c](https://github.com/user-attachments/assets/e9c07d6b-7730-458e-8970-bf776f058fbf)

- Keterangan : Tampilan Alert dialog ini akan otomatis setelah memencet tombol keluar. Terdapat 2 opsi diantaranya  batal dan ya. Saat menekan tombol batal akan otomatis kembali ke halaman profil dan jika menekan tombol ya maka akan melakukan proses destroy, dan otomatis akan keluar dari aplikasi.



   




   


