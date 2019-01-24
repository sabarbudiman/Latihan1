# latihan1

TUTORIAL CARA MENGGUNAKAN GIT

Git adalah pengontrol versi yang bertugas mencatat setiap perubahan pada file proyek yang dikerjakan oleh banyak orang maupun sendiri. Git dikenal juga dengan distributed revision control (VCS terdistribusi), artinya penyimpanan database Git tidak hanya berada dalam satu tempat saja.

Langkah-langkah Install GIT di berbagai jenis sistem

Install GIT di Windows

Menginstall GIT di Windows sangat mudah, cukup dengan mendownload dan menjalankan instalasinya. Ikuti langkah berikut ini untuk meng-install GIT di Windows:

1. Buka website ini dan download installer GIT untuk Windows.
2. Setelah download, buka file tersebut untuk menjalankan proses instalasi. Ikuti semua instruksi, klik Next dan Finish hingga semua  proses instalasi selesai.

PERINTAH DASAR GIT

1. git init, perintah untuk membuat repository local
2. git add, perintah untuk menambahkan file baru, atau perubahan pada file pada staging sebelum proses commit.
3. git commit, perintah untuk menyimpan perubahan kedalam database git.
4. git push -u origin master, perintah untuk mengirim perubahan pada repository local menuju server repository.
5. git clone [url], perintah untuk membuat working directory yang diambil dari repositry sever.
6. git remote add origin [url], perintah untuk menambahkan remote server/reopsitory server pada local repositry (working directory).

Langkah-Langkah Menggunakan Git

1. Klik kanan pada monotir Klik " Git Bash Here"
![klik kanan](https://user-images.githubusercontent.com/46584235/51678735-af59b180-200f-11e9-86f2-377378e3ddbd.jpeg)

2. Maka akan ada tampilan command prompt seperti dibawah ini                                     
![commond front](https://user-images.githubusercontent.com/46584235/51678746-b7195600-200f-11e9-908c-050b95711a54.jpeg)

3. Buka Drive yang ingin dipakai semisal Drive D dengan perintah cd /d                       
![drive d](https://user-images.githubusercontent.com/46584235/51678761-c1d3eb00-200f-11e9-8a81-0dd9ed5e7429.jpeg)

4. Buat directory dengan printah "mkdir" sebagai contoh directory Pemograman1 
![pemog1](https://user-images.githubusercontent.com/46584235/51678781-d31cf780-200f-11e9-824b-7e3b9a389506.jpeg)

5. Buka directory Pemograman1 dengan perintah cd Pemograman1                            
![buka pemog](https://user-images.githubusercontent.com/46584235/51678794-db753280-200f-11e9-9f2d-ede68e191ddd.jpeg)

6. Buat directory latihan1 dan buka directory latihan1.                         
![mkdir latihan](https://user-images.githubusercontent.com/46584235/51678808-e203aa00-200f-11e9-8f02-088734603990.jpeg)

7. Menambahkan file baru pada repository dengan perintah echo "#latihan1" >> README.md
![printah echo](https://user-images.githubusercontent.com/46584235/51678856-f47de380-200f-11e9-9479-df02b09770bc.jpeg)

8. Jalankan perintah git init untuk menjalankan repository local
![printah git init](https://user-images.githubusercontent.com/46584235/51678876-ff387880-200f-11e9-9655-fd106724468f.jpeg)

9. Untuk menambahkan file yang baru saja dibuat tersebut gunakan perintah git add README.md
![git add readme](https://user-images.githubusercontent.com/46584235/51678898-0cedfe00-2010-11e9-8e36-fe43769a7a7e.jpeg)

10. Untuk menyimpan perubahaan yang ada kedalam database repository local, gunakan perintah git commit -m "File pertama saya"     
![17](https://user-images.githubusercontent.com/46584235/51680875-8f2cf100-2015-11e9-8b74-aac226788a78.jpeg)

11. Buat repository server, isi nama repositorynya semisal : latihan1 ,kemudian klik tombol Creat repository
![repo server](https://user-images.githubusercontent.com/46584235/51678919-1a0aed00-2010-11e9-803f-b7c639ad2925.jpeg)

12. Menambahkan remote repository. remote repository merupakan repository server yang akan digunakan untuk menyimpan setiap perubahan  sehingga dapat diakses oleh banyak user.
![remote repo](https://user-images.githubusercontent.com/46584235/51678946-298a3600-2010-11e9-8f32-de6c7dd3c61c.jpeg)

13. Mengirim perubahan ke server dengan perintah git push -u origin master 
![git push](https://user-images.githubusercontent.com/46584235/51678958-3149da80-2010-11e9-8bbc-5737a16d1f7e.jpeg)

14. Melihat hasil pada repository, buka laman github.com arahkan pada repositorynya. Maka perubahan akan terlihat pada laman tersebut   
![hasil 01](https://user-images.githubusercontent.com/46584235/51678981-3f97f680-2010-11e9-99c1-b5199fe5d0a8.jpeg)

15. Buka drive D kemudian klik Pemograman1, klik latihan1
![klik latihan1](https://user-images.githubusercontent.com/46584235/51680812-5a209e80-2015-11e9-915e-26f8aaa380d8.jpeg)

16. Klik kanan pada file Readme.md kemudian pilih aplikasi untuk mengubah file, semisal dibawah ini dengan aplikasi notepad
![notepad](https://user-images.githubusercontent.com/46584235/51679023-60604c00-2010-11e9-8b79-617805ea0c72.jpg)

17. Untuk mengirim perubahan jalan perinta git push -u origin master, kemudian git add README.md dan git commit -m "latihan1"   
![push origin 2](https://user-images.githubusercontent.com/46584235/51679040-6eae6800-2010-11e9-834c-6773b7f17200.jpg)
![git add readme 2](https://user-images.githubusercontent.com/46584235/51679053-753cdf80-2010-11e9-9f76-36e4ac970623.jpg)
![git commit 2](https://user-images.githubusercontent.com/46584235/51679070-7e2db100-2010-11e9-8bd4-fd927dc185c3.jpg)
18. Kemuidan lihat perubahannya pada laman github.com 
![hasil final](https://user-images.githubusercontent.com/46584235/51679084-85ed5580-2010-11e9-9caf-4fe414e97cf8.jpg)

 Sekian dan terima kasih 
