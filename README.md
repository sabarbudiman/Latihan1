# latihan1

TUTORIAL CARA MENGGUNAKAN GIT

Git adalah pengontrol versi yang bertugas mencatat setiap perubahan pada file proyek yang dikerjakan oleh banyak orang maupun sendiri. Git dikenal juga dengan distributed revision control (VCS terdistribusi), artinya penyimpanan database Git tidak hanya berada dalam satu tempat saja.

Langkah-langkah Install GIT di berbagai jenis sistem

Install GIT di Windows

Menginstall GIT di Windows sangat mudah, cukup dengan mendownload dan menjalankan instalasinya. Ikuti langkah berikut ini untuk meng-install GIT di Windows:

1. Buka website ini dan download installer GIT untuk Windows.
2. Setelah download, buka file tersebut untuk menjalankan proses instalasi. Ikuti semua instruksi, klik Next dan Finish hingga semua  proses instalasi selesai.

Menambahkan global config
• Pada saat pertama kali menggunakan git, perlu dilakukan configurasi user.name dan user.email
• Configurasi ini bisa dilakukan untuk global repository atau individual repository.
• apabila belum dilakukan configurasi, akan mengakibatkan terjadi kegagalan saat menjalankan perintah git commit

• Config Global Repository                                                                                     

$ git config --global uesr.name "nama_user"                                                                
$ git config --global user.email nama_user"


PERINTAH DASAR GIT

1. git init, perintah untuk membuat repository local
2. git add, perintah untuk menambahkan file baru, atau perubahan pada file pada staging sebelum proses commit.
3. git commit, perintah untuk menyimpan perubahan kedalam database git.
4. git push -u origin master, perintah untuk mengirim perubahan pada repository local menuju server repository.
5. git clone [url], perintah untuk membuat working directory yang diambil dari repositry sever.
6. git remote add origin [url], perintah untuk menambahkan remote server/reopsitory server pada local repositry (working directory).


Langkah-Langkah Menggunakan Git

• Klik kanan pada monitor akan munjucul tampilan seperti gambar di bawah lalu Klik " Git Bash Here"
![klik kanan](https://user-images.githubusercontent.com/46584235/51678735-af59b180-200f-11e9-86f2-377378e3ddbd.jpeg)

• Akan muncul tampilan command prompt seperti dibawah ini                                     
![commond front](https://user-images.githubusercontent.com/46584235/51678746-b7195600-200f-11e9-908c-050b95711a54.jpeg)

• Buka Drive yang ingin dipakai, semisal Drive D  jalankan dengan perintah cd /d                       
![drive d](https://user-images.githubusercontent.com/46584235/51678761-c1d3eb00-200f-11e9-8a81-0dd9ed5e7429.jpeg)

• Buat directory dengan printah "mkdir" sebagai contoh : directory Pemograman1 
![pemog1](https://user-images.githubusercontent.com/46584235/51678781-d31cf780-200f-11e9-824b-7e3b9a389506.jpeg)

• Buka directory Pemograman1 dengan perintah cd Pemograman1                            
![buka pemog](https://user-images.githubusercontent.com/46584235/51678794-db753280-200f-11e9-9f2d-ede68e191ddd.jpeg)

• Buatlah directory projrct paktikum pertama denagan nama latihan1 dan kemudian masuk ke dierectory tersebut, directory aktif akan menjadi : d\pemograman1\latihan1                      
![mkdir latihan](https://user-images.githubusercontent.com/46584235/51678808-e203aa00-200f-11e9-8f02-088734603990.jpeg)

• Jalankan perintah git init untuk menjalankan repository local.                                                                         
• Repository baru berhasil di analisasi, dengan terbentuknya satu directory hidden dengan nama .git                                     
• Pada direktori tersebut, semua perubahan pada working directory akan disimpan                                         
![printah git init](https://user-images.githubusercontent.com/46584235/51678876-ff387880-200f-11e9-9655-fd106724468f.jpeg)

• Menambahkan file baru pada repository dengan perintah echo "#latihan1" >> README.md
• Untuk membuat file dapat menggunakan text editor, lalu menyimpan filenya pada direktori aktif (repository)
• disini kita akan coba buat satu file bernama README.md (text file)

![printah echo](https://user-images.githubusercontent.com/46584235/51678856-f47de380-200f-11e9-9479-df02b09770bc.jpeg)

• Untuk menambahkan file yang baru saja dibuat tersebut gunakan perintah git add README.md                           
• File README.md berhasil dibuat.                                    
![git add readme](https://user-images.githubusercontent.com/46584235/51678898-0cedfe00-2010-11e9-8e36-fe43769a7a7e.jpeg)

• Untuk menyimpan perubahaan yang ada kedalam database repository local, gunakan perintah git commit -m "File pertama saya"     
![17](https://user-images.githubusercontent.com/46584235/51680875-8f2cf100-2015-11e9-8b74-aac226788a78.jpeg)

• Anda harus membuat akun terlebih dahulu.                 
• Pada laman github, klik tombol start a project, atau                                                
• Dari menu (icon +) klik New Repository                                           
• Buat repository server isi nama repositorynya semisal : latihan1, kemudian klik tombol Creat repository                         
![repo server](https://user-images.githubusercontent.com/46584235/51678919-1a0aed00-2010-11e9-803f-b7c639ad2925.jpeg)

• Menambahkan remote repository.                                                                                           
• Remote repository merupakan repository server yang akan digunakan untuk menyimpan setiap perubahan sehingga dapat diakses oleh banyak user                                                           
• Untuk menambahkan remote repository server, gunakan perintah git remote add origin [url]
![remote repo](https://user-images.githubusercontent.com/46584235/51678946-298a3600-2010-11e9-8f32-de6c7dd3c61c.jpeg)

• Mengirim perubahan ke server dengan perintah git push -u origin master                                      
• Perintah ini akan meminta memasukkan username dan password pada akun github.com                          
![git push](https://user-images.githubusercontent.com/46584235/51678958-3149da80-2010-11e9-8bbc-5737a16d1f7e.jpeg)

• Melihat hasil pada repository, buka laman github.com arahkan pada repositorynya.                                                      
• Maka perubahan akan terlihat pada laman tersebut                                  
![hasil 01](https://user-images.githubusercontent.com/46584235/51678981-3f97f680-2010-11e9-99c1-b5199fe5d0a8.jpeg)

• Buka drive D kemudian klik Pemograman1                                
• kemudian klik direktori latihan1                                                                          
![klik latihan1](https://user-images.githubusercontent.com/46584235/51680812-5a209e80-2015-11e9-915e-26f8aaa380d8.jpeg)

• Klik kanan pada file Readme.md kemudian pilih aplikasi untuk mengubah file                                      
• Semisal dibawah ini dengan aplikasi notepad menambahkan / mengedit data dalam file README.md                                                  
![notepad](https://user-images.githubusercontent.com/46584235/51679023-60604c00-2010-11e9-8b79-617805ea0c72.jpg)

• Untuk mengirim perubahan jalankan perintah git push -u origin master                                                    
• Kemudian jalankan perintah git add README.md                                                                
• Kemudian jalankan perintah git commit -m "latihan1"                                                                  
![push origin 2](https://user-images.githubusercontent.com/46584235/51679040-6eae6800-2010-11e9-834c-6773b7f17200.jpg)
![git add readme 2](https://user-images.githubusercontent.com/46584235/51679053-753cdf80-2010-11e9-9f76-36e4ac970623.jpg)
![git commit 2](https://user-images.githubusercontent.com/46584235/51679070-7e2db100-2010-11e9-8bd4-fd927dc185c3.jpg)

• Kemuidan lihat perubahannya pada laman github.com                                              
![hasil final](https://user-images.githubusercontent.com/46584235/51679084-85ed5580-2010-11e9-9caf-4fe414e97cf8.jpg)

 Sekian dan terima kasih 
