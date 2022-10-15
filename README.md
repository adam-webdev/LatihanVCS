
## Instalasi `GIT` dan Latihan menggunakan `Version Control System`

## - `Instalasi GIT :`

1. Download git di link berikut : [https://git-scm.com/downloads](https://git-scm.com/downloads)
2. Berikut File Git yang sudah didownload lalu open :


   ![Berikut File Git yang sudah didownload](img/install.png)

3. Maka akan muncul infomasi lisensi Git, klik Next > untuk melanjutkan.

    ![Berikut File Git yang sudah didownload](img/2.%20Informasi%20tentang%20git.JPG)


4. Selanjutnya menentukan lokasi instalasi. Biarkan saja apa adanya, kemudian klik Next >.

    ![Berikut File Git yang sudah didownload](img/3.%20Lokasi%20instal.JPG)

5. Selanjutnya pemilihan komoponen, biarkan saja seperti ini kemudian klik Next >.

    ![Berikut File Git yang sudah didownload](img/4.%20Pemilihan%20komponen.JPG)

6. Selanjutnya pemlilihan direktori start menu, klik Next >.

    ![Berikut File Git yang sudah didownload](img/5.%20pembuatan%20start%20menu.JPG)

7. Selanjutnya pengaturan PATH Environment. Pilih yang tengah agar perintah git dapat di kenali di Command Prompt (CMD). Setelah itu klik Next >.

    ![Berikut File Git yang sudah didownload](img/6.%20Path%20environment.JPG)

8. Selanjutnya konversi line ending. Biarkan saja seperti ini, kemudian klik Next >.

    ![Berikut File Git yang sudah didownload](img/7.%20konversi%20line%20ending.JPG)

9. Selanjutnya pemilihan emulator terminal. Pilih saja yang bawah, kemudian klik Next >.

    ![Berikut File Git yang sudah didownload](img/8.%20Pemilihan%20emulator%20terminal.JPG)

10. Selanjutnya pemilihan opsi ekstra. Klik saja Next >.

    ![Berikut File Git yang sudah didownload](img/9.%20Konfigurasi%20Opsi%20Ekstra.JPG)

11. Selanjutnya pemilihan opsi ekspreimental, langsung saja klik Install untuk memulai instalasi.

    ![Berikut File Git yang sudah didownload](img/10.%20Opsi%20ekperimental.JPG)

12. Tunggu beberapa saat, instalasi sedang dilakukan.

    ![Berikut File Git yang sudah didownload](img/11.%20Installing.JPG)

13. Setelah selesai, kita bisa langsung klik Finish.

    ![Berikut File Git yang sudah didownload](img/12.%20Finish.JPG)

## `Cara Pengguanan GIT :`

1. Pertama kita harus Konfigurasi global akun yaitu name dan email agar tidak eror ketika git commit :
    - `git config --global user.name “name”`
    - `git config --global user.email "email"`

     ![Berikut File Git yang sudah didownload](img/img-penggunaan-git/config%20name.png)

     ![Berikut File Git yang sudah didownload](img/img-penggunaan-git/config%20email.png)

2. Membuat repository / folder baru dan masuk repository tersebut dengan masukan perintah sebagai berikut :

    - `mkdir LatihanVCS`
    - `cd LatihanVCS`

     ![Berikut File Git yang sudah didownload](img/img-penggunaan-git/membuat%20repository%20%20folder.png)

     ![Berikut File Git yang sudah didownload](img/img-penggunaan-git/pindah%20direktori.png)

3. Selanjutnya kita akan membuat file baru bernama README.md :

    - `echo "# LatihanVCS" >> README.md`

     ![Berikut File Git yang sudah didownload](img/img-penggunaan-git/buat%20file%20baru.png)

4. Lalu kita inisialisasi dengan perintah berikut :

    - `git init`

      ![Berikut File Git yang sudah didownload](img/img-penggunaan-git/inisialisasi.png)

5. Setelah itu kita akan melihat status dari file tersebut :

    - `git status`

      ![Berikut File Git yang sudah didownload](img/img-penggunaan-git/status%20file.png)

      Terlihat disitu terdapat file README.md yang belum di tambahkan yang bertulis dengan warna merah

6. Untuk menambahkan file tersebut / perubahan pada file
   pada staging sebelum proses commit. ketikan perintah berikut

   Lalu cek kembali status file tersebut jika sudah sukses di tambahkan tulisan file berwarna hijau

    - `git add "README.md"`
    - `git status`

      ![Berikut File Git yang sudah didownload](img/img-penggunaan-git/git%20add%20readme.png)

7. Setelah itu simpan perubahan / penambahan yang terjadi dengan
   mengetikan perintah berikut :

    - `git commit -m "first commit"`
    - `git remote -v` => untuk mengecek sudah terhubung dengan url server git

      ![Berikut File Git yang sudah didownload](img/img-penggunaan-git/git%20commit.png)

      Perubahan / penambahan pada repository berhasil disimpan didatabse lokal,
      Jika kita ingin menyimpannya diserver repository
      silahkan kunjungi link berikut : [https://github.com](https://github.com)

8. Lalu akan muncul tampilan sebagai berikut :

      ![Berikut File Git yang sudah didownload](img/img-penggunaan-git/home.png)

      Silahkan login jika sudah memiliki akun namun jika belum silahkan daftar terlebih dahulu :

9. Lalu akan muncul tampilan sebagai berikut silahkan daftar :

      ![Berikut File Git yang sudah didownload](img/img-penggunaan-git/daftar%20github.png)

    Sampai semua ceklis berwarna hijau
    Jika sudah klik Continue

10. Membuat Repository baru digithub klik tombol create or new yang  berwarna hijau :

      ![Berikut File Git yang sudah didownload](img/img-penggunaan-git/new%20repo.png)

11. Lalu akan tampil halaman berikut silahakan diisi nama repository sesuai keinginan kalian:

      ![Berikut File Git yang sudah didownload](img/img-penggunaan-git/latihann.png)

    - Public => repository dapat dilihat oleh semua orang
    - Private => repository dibatas tidak semua orang bisa melihat

12. Jika Berhasil akan muncul tampilan sebagai berikut :

      ![Berikut File Git yang sudah didownload](img/img-penggunaan-git/tutor%20push.png)

    - 1 Untuk menyimpan repository jika di komputer lokal belum ada
    - 2 Untuk membuat repository jika di komputer lokal sudah ada dan tersimpan kalian tinggal ikutin perintahnya
    -
13. Baik sekarang kita akan push repository lokal kita ke github pertama kita lakukan remote sebagai berikut :

    - `git remote add origin https://github.com/adam-webdev/LatihanVCS.git`

    Lalu cek status remote apakah berhasil :

    - `git remote -v`

    Lalu kita bisa atur branch repository kita dengan menjalankah perintah berikut :

    - `git branch -M main`

      ![Berikut File Git yang sudah didownload](img/img-penggunaan-git/branch.png)

14. Selanjutnya kita push dengan menggunakan perintah  :

    - `git push -u origin main`
    - `origin` adalah nama remote yang tadi kita buat
    - `main` adalah branch repository kita

      ![Berikut File Git yang sudah didownload](img/img-penggunaan-git/push.png)

    - Kita sudah berhasil menyimpan repository kita di `GITHUB`

15. Jika kita ingin menggunakan repository yang telah ada di Github kita bisa mendownload atau mengclone pertama klik `code` berwarna hijau lalu copy url https repository kita :

      ![Berikut File Git yang sudah didownload](img/img-penggunaan-git/clone.png)

    Berikut perintah untuk menggunakan git clone :
    - `git clone https://github.com/adam-webdev/LatihanVCS.git `


      ![Berikut File Git yang sudah didownload](img/img-penggunaan-git/cloning.png)

    - Masuk kerepository dengan cara `cd LatihanVCS`

    Setelah itu jangan lupa untuk melakukan pull untuk mengetahui perubahan yang terakhir dilakukan

    - `git pull origin main `

      ![Berikut File Git yang sudah didownload](img/img-penggunaan-git/pull.png)

    - Atau anda juga bisa mendownload langsung dengan memilih download zip

      ![Berikut File Git yang sudah didownload](img/img-penggunaan-git/clone.png)





