#LatihanVCS
1. Instal Software GIT terlebih dahulu
![Screenshot (44)](https://user-images.githubusercontent.com/115884834/196135987-2446db13-0328-4431-9ac0-4a482e3185f3.png)


2. Login ke GIT
   Langkah pertama kalian adalah memasukan username dengan menggunakan perintah

   $ git config --global user.name "UsernameAnda"

   lalu kalian tambahkan juga email dengan menggunakan perintah

   $ git config --global user.email "email anda"
![Screenshot (12)](https://user-images.githubusercontent.com/115884834/196137075-f6e44e86-79c5-430a-9c55-61b79adc845a.png)


3. Login Github
   
   Langkah kedua kalian bisa login ke dalam website github, Setelah kalian login akan muncul tampilan dashboard dari github tersebut
![Screenshot (13)](https://user-images.githubusercontent.com/115884834/196137770-6b4f6f8a-9374-4fde-b276-b78619e0d7d1.png)


4. Buat Repository

   Setelah berhasil login ke GitHub, Anda bisa mulai membuat repository. Klik tombol New pada menu Repositories untuk membuat repository baru
![Screenshot (47)](https://user-images.githubusercontent.com/115884834/196139586-aee6716e-ca0e-4318-9716-d25e14e4b87d.png)


   Kemudian kalian akan diarahkan pada halaman untuk membuat repository baru seperti gambar di bawah ini.
![WhatsApp Image 2022-10-17 at 16 25 10](https://user-images.githubusercontent.com/115884834/196141557-cc2716fb-a2ab-42da-9c19-ee5c40a5467e.jpeg)


4. Buat Folder
   Lalu kalian buat folder di localdisk komputer kalian
![Screenshot (21)](https://user-images.githubusercontent.com/115884834/196142215-c73fe3cf-cd84-460c-8564-1cdf34240e68.png)


   Buat folder dengan menggunakan perintah dan buka folder tersebut

   $mkdir latihan1

   $cd latihan1
![Screenshot (22)](https://user-images.githubusercontent.com/115884834/196142375-7113da60-af1b-4952-91ea-fd0230ce8307.png)


   dan tambahkan file README.md dengan menggunakan perintah

   $echo "#LatihanVCS" >> README.md
![Screenshot (23)](https://user-images.githubusercontent.com/115884834/196142710-7e7e8719-36ee-4f2d-8a76-788a67b3d836.png)


   kemudian buat repository lokal menggunakan perintah

   $git init
![Screenshot (24)](https://user-images.githubusercontent.com/115884834/196143067-beeb93cd-d124-4c2d-8b78-2c7475cdf59f.png)


  Untuk menambahkan file yang baru saja dibuat tersebut menggunakan perintah

  $git add README.md
![Screenshot (27)](https://user-images.githubusercontent.com/115884834/196143164-1d48e710-1752-4bfc-a813-e4b6dcfc53a5.png)


  Untuk menambahkan file yang baru saja dibuat tersebut gunakan perintah

  $git add README.md
![Screenshot (27)](https://user-images.githubusercontent.com/115884834/196143332-a42e93c2-06c4-4c80-9c93-bb6b56ceb95a.png)


  Untuk menyimpan perubahan yang ada kedalam database repository local, gunakan perintah

  $git commit -m "first commit"
![Screenshot (31)](https://user-images.githubusercontent.com/115884834/196143466-2960728e-764d-4da9-9b8b-af1a570fbd31.png)


  kemudian gunakan perintah

  $git branch -M main
![Screenshot (33)](https://user-images.githubusercontent.com/115884834/196143728-ad799fde-f4e5-45d4-8fb0-7a5d8618dcc0.png)


  Setelah itu menambahkan remote repository. remote Repository merupakan repository server yang akan digunakan untuk menyimpan setiap perubahan pada local repository,   sehingga dapat diakses oleh banyak user. dengan menggunakan perintah

  $git remote add origin https://github.com/Alifiananda06/LatihanVCS.git
![Screenshot (36)](https://user-images.githubusercontent.com/115884834/196143844-d1e4f614-2d5c-4a94-8128-89eca07f3689.png)


  Dan untuk mengirim perubahan pada local repository ke server gunakan perintah

  $git push -u origin main

  Dan kita bisa cek di repository langsung pada website github
  ![Screenshot (48) ok](https://user-images.githubusercontent.com/115884834/196144662-75bdbbfa-6f83-4774-8a2c-cb03714961ec.png)

