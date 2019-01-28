# latihanrafi

langkah-langkah cara penggunaan git hub

Apa itu git Git adalah pengontrol versi yang bertugas mencatat setiap perubahan pada file proyek yang dikerjakan oleh banyak orang maupun sendiri. Git dikenal juga dengan distributed revision control (VCS terdistribusi), artinya penyimpanan database Git tidak hanya berada dalam satu tempat saja.

Langkah-langkah Install GIT di berbagai jenis sistem

Install GIT di Windows

Menginstall GIT di Windows sangat mudah, cukup dengan mendownload dan menjalankan instalasinya. Ikuti langkah berikut ini untuk meng-install GIT di Windows:

1.Buka website ini dan download installer GIT untuk Windows.

2.Setelah download, buka file tersebut untuk menjalankan proses instalasi. Ikuti semua instruksi, klik Next dan Finish hingga semua proses instalasi selesai.

PERINTAH DASAR GIT

1.git init, perintah untuk membuat repository local

2.git add, perintah untuk menambahkan file baru, atau perubahan pada file pada staging sebelum proses commit.

3.git commit, perintah untuk menyimpan perubahan kedalam database git.

4.git push -u origin master, perintah untuk mengirim perubahan pada repository local menuju server repository.

5.git clone [url], perintah untuk membuat working directory yang diambil dari repositry sever

6.git remote add origin [url], perintah untuk menambahkan remote server/reopsitory server pada local repositry (working directory).


Langkah-Langkah Menggunakan Git

1.Buka Git Bash

![langkah 1](https://user-images.githubusercontent.com/46749109/51836174-2fdf2180-2332-11e9-8cd1-8d8307fc44cb.JPG)

2.Buka Drive yang ingin dipakai, semisal Drive D jalankan dengan perintah cd /d

![langkah 2](https://user-images.githubusercontent.com/46749109/51836239-6e74dc00-2332-11e9-83b4-9f8e263f97be.JPG)

3.Buat directory dengan printah "mkdir" sebagai contoh : directory Latihan

![langkah 3](https://user-images.githubusercontent.com/46749109/51836300-a845e280-2332-11e9-8acf-8421f99039f1.JPG)

4.Buka directory Pemograman1 dengan perintah cd Latihan

![langkah 4](https://user-images.githubusercontent.com/46749109/51836362-cf9caf80-2332-11e9-8468-8241fe8a2b2e.JPG)

5.Buat directory latihan1 dan buka directory latihanrafi.

![langkah 5](https://user-images.githubusercontent.com/46749109/51836387-e5aa7000-2332-11e9-912e-9d407935be0d.JPG)

6.Menambahkan file baru pada repository dengan perintah echo "#latihanrafi" >> README.md

![langkah 6](https://user-images.githubusercontent.com/46749109/51836416-fa870380-2332-11e9-8f12-56d45bf619d8.JPG)

7.Jalankan perintah git init untuk menjalankan repository local

![langkah 7](https://user-images.githubusercontent.com/46749109/51836503-2e622900-2333-11e9-8d5f-801600737454.JPG)

8.Untuk menambahkan file yang baru saja dibuat tersebut gunakan perintah git add README.md

![langkah 8](https://user-images.githubusercontent.com/46749109/51836523-3e7a0880-2333-11e9-839c-40e5f3ddefa2.JPG)

9.Untuk menyimpan perubahaan yang ada kedalam database repository local, gunakan perintah git commit -m "File pertama rafi"

![langkah 9](https://user-images.githubusercontent.com/46749109/51836589-581b5000-2333-11e9-9de5-f8b7e15cd8c9.JPG)

10.Buat repository server, isi nama repositorynya semisal : latihanrafi ,kemudian klik tombol Creat repository

![langkah 10](https://user-images.githubusercontent.com/46749109/51836615-6e291080-2333-11e9-8975-71cbe7b96220.JPG)

11.Menambahkan remote repository. remote repository merupakan repository server yang akan digunakan untuk menyimpan setiap perubahan sehingga dapat diakses oleh banyak user.

![langkah 11](https://user-images.githubusercontent.com/46749109/51836662-9f094580-2333-11e9-9e6f-640b95eb83e0.JPG)

12.Mengirim perubahan ke server dengan perintah git push -u origin master

![langkah 12](https://user-images.githubusercontent.com/46749109/51836720-c3fdb880-2333-11e9-83d0-9bd7a665f308.JPG)

13.Melihat hasil pada repository, buka laman github.com arahkan pada repositorynya. Maka perubahan akan terlihat pada laman tersebut

![langkah 13](https://user-images.githubusercontent.com/46749109/51836746-da0b7900-2333-11e9-8fb9-dd9e438d5c07.JPG)

14.Buka drive D kemudian klik latihan, klik latihanrafi Klik kanan pada file Readme.md kemudian pilih aplikasi untuk mengubah file, semisal dibawah ini dengan aplikasi notepad

![langkah 14](https://user-images.githubusercontent.com/46749109/51836808-0de69e80-2334-11e9-9b74-0f61769c55d0.JPG)

15.Untuk mengirim perubahan jalan perinta git push -u origin master, kemudian git add README.md dan git commit -m "latihanrafi"

![langkah 15](https://user-images.githubusercontent.com/46749109/51836890-5a31de80-2334-11e9-89f6-85aea59af93e.JPG)

16.Kemuidan lihat perubahannya pada laman github.com

![hasil](https://user-images.githubusercontent.com/46749109/51836925-6fa70880-2334-11e9-9afc-2ac014d22127.JPG)
