# latihanVCS
Nama	: Taufiq alif rahman

NIM	: 312010289

Kelas	: TI.20.A.2

## latihan Version Control System (VCS)

1. 	Langkah pertama membuat folder **program 1**  
saya membuat folder nya berada 	di 	desktop 
2.	Klik kanan pada folder yang sudah di buat tadi lalu klik terminal
	lalu akan muncul seperti gambar di bawah ini:


![0](https://user-images.githubusercontent.com/72717218/96336317-0ab3b900-10a9-11eb-8762-48889c7fb8de.png)


3. 	Kemudian buatlah folder dengan mengetik di terminal `(mkdir latihan1)`


![1](https://user-images.githubusercontent.com/72717218/96336432-fa500e00-10a9-11eb-8f21-2e0cf96717f6.png)


dan nantinya di folder program 1 didalam nya ada folder baru **latihan1**


4.	Langkah selanjut nya masuk kedalam folder “latihan1” dengan mengetik `(cd latihan1)`


![2](https://user-images.githubusercontent.com/72717218/96336488-692d6700-10aa-11eb-8b8e-8352c49c04bd.png)


5.	Buatlah folder tersebut menjadi repo (repository) dengan cara `git init`.
	Jika benar akan seperti gambar di bawah ini:

![3](https://user-images.githubusercontent.com/72717218/96336551-dccf7400-10aa-11eb-9807-2cb66b4eede3.png)

jika sudah seperti ini artinya folder sudah menjadi repo.

6.	Setelah itu buat file README.md dengan mengertik `(echo “latihan 1” >> 	README.md)`

![4](https://user-images.githubusercontent.com/72717218/96337317-6afa2900-10b0-11eb-888f-d87f70a72239.png)

7.	Cara mengecek file tersebut ketik `git status` maka akan muncul sebagai berikut

![5](https://user-images.githubusercontent.com/72717218/96337356-c9270c00-10b0-11eb-882c-8935d6c08dfd.png)

warna merah tersebut berarti file belum di add.

8. 	Cara nya dengan mengetik `git add <file>` atau jika file yang merah lebih dari satu `( git add . )`

![6](https://user-images.githubusercontent.com/72717218/96337667-e3fa8000-10b2-11eb-9a86-782543b09e36.png)

untuk mengecek nya ketik `git status`

![13](https://user-images.githubusercontent.com/72717218/96337738-4c496180-10b3-11eb-9eba-65a663986b96.png)

maka warna file nya akan berubah hijau, file sudah di add.

9.	Langkah selanjutnya commit file tersebut `(git commit -m “pesan”)`

![7](https://user-images.githubusercontent.com/72717218/96337876-646db080-10b4-11eb-99bd-8f8710ba2d65.png)

jika tidak ada masalah maka akan seperti gambar di atas.

10. langkah selanjutnya buat lah akun di github  (http://github.com)

11. Jika sudah memiliki akun buat lah repository baru `new repository` 

![8](https://user-images.githubusercontent.com/72717218/96338035-9b909180-10b5-11eb-8ea3-cdb33aae8204.png)

12.	Langkah selanjutnya mengisi repository nya 

![9](https://user-images.githubusercontent.com/72717218/96338102-0c37ae00-10b6-11eb-81bf-3e5f8e0db00e.png)

- isi repository nya dengan nama “latihan1” ,untuk penamaan bisa di rubah sesui keperluan.	
- untuk description / pesan buat lah sejelas mungkin.
- pilih lah public 
- lalu create repository 

13.	Maka akan muncul seperti gambar berikut 

![10](https://user-images.githubusercontent.com/72717218/96338192-97b13f00-10b6-11eb-9353-c89d4dc3c45a.png)

copy link tersebut untuk menghubungkan dengan akun git yang ada di pc/ laptot.

14.	Cara menghubungkan nya dengan mengetik `git remote add origin <link>`

![11](https://user-images.githubusercontent.com/72717218/96338201-9e3fb680-10b6-11eb-9d03-310f906136d1.png)

15.	Langkah selanjutnya ketik `git push -u origin master`

![12](https://user-images.githubusercontent.com/72717218/96338208-a13aa700-10b6-11eb-838a-ae2f1df85ae5.png)

## Pengertian
 - `mkdir <nama file>` untuk membuat file baru
 - `git init` untuk membuat depository local
 - `git status` untuk mengecek apakah ada perubahan di dalam file 
 - `git add` untuk menambah kan file baru 
 - `git commit` untuk menyimpan perubahan kedalam database git.
 - `git remote` sumber dari repo 
 - `git push` untuk meng upload file ke github
 - `git pull` cloning repo yang ada di remote 
