# Note Yang Harus Selalu Diingat!

Berikut merupakan beberapa tahapan yang harus selalu di ingat diantaranya yaitu : 

1. Tahapan untuk membuat folder di VScode :
    
    a. Buka terminal, pilih ubuntu kemudian ketik "ls"
    
    b. Kemudian ketik "mkdir nama_folder"
    
    c. Lalu untuk memastikan folder sudah ada ketik "cd nama_folder"
    
    d. Setelah itu ketik "code ." maka nantinya tampilan akan diarahkan ke VScode dengan folder yang barusan kita buat

2. Tahapan untuk membuat isi pada folder di VScode :
    
    a. Buka terminal, pilih ubuntu kemudian ketik "ls" jika sebelumnya sudah 
    buka terminal tinggal lanjutin aja ga perlu ketik "ls" lagi
    
    b. Kemudian ketik "mkdir nama_folder"
    
    c. Lalu untuk memastikan folder sudah ada ketik "cd nama_folder"
    
    d. setelah itu ketik "code ." maka nantinya tampilan akan diarahkan ke VScode dengan folder yang barusan kita buat

3. Tahapan untuk push ke github :
    
    a. git add .
    
    b. git commit -m "nama_folder"
    
    c. git push -u origin main


Berikut merupakan beberapa perintah beserta fungsi kegunaannya antara lain yaitu : 

1. "ls atau list" 
    digunakan untuk menampilkan daftar file didalam sebuah direktori. Atau bisa dikatakan kita menggunakan perintah “ls” ini untuk melihat file file apa yang sudah kita pernah buat.  Selain itu perintah “ls” juga dapat digunakan untuk menjalankan perintah lainnya diantaranya yaitu : 
    
    a. “ ls -l “ digunakan untuk menampilkan daftar secara panjang yang mencakup informasi izin akse, pemilik, grup, ukuran dan waktu terakhir ketika kita melakukan perubahan.
    
    b. “ ls -a “ digunakan untuk menampilkan semua berkas, bahkan termasuk berkas tersembunyi yang biasanya ditandai dengan tanda . di awal kata ketika menamakan berkasnya.
    
    c. “ ls -h “ digunakan untuk menggunakan format agar lebih mudah dibaca oleh orang awam mengenai ukuran suatu berkas misal seperti kb, mb, gb.
    
    d. “ ls -t “ digunakan untuk mengurutkan berkas berdasarkan waktu terakhir melakukan perubahan atau mengedit
  

2. “cd atau change directory”  digunakan untuk berpindah dari   
    satu folder ke folder lainnya yang ada di dalam struktur sistem file. Atau dapat dikatakan misal pada awalnya kita ada di folder Pertemuan1 tapi kita mau pindah ke folder Pertemuan2 maka perintah yang bisa kita lakukan di terminal untuk pindah ke folder Pertemuan2 yaitu “cd pertemuan2”. Begitupun jika kita mau masuk ke suatu folder yang ada di dalam suatu sistem maka kita juga bisa menggunakan perintah “cd” untuk masuk ke folder tersebut.

    Berikut merupakan beberapa contoh penerapan perintah “cd” diantaranya yaitu : 
    
    a. Untuk berpindah ke folder tertentu menggunakan perintah “ cd nama_folder ” 
    
    b. Untuk kembali ke tampilan folder menggunakan perintah “ cd .. ” 
    
    c. Untuk berpindah ke folder home pengguna atau user “ cd ~ “
    
    d. Untuk berpindah ke folder sebelumnya “ cd - “

3. “mkdir atau make directory” digunakan untuk membuat struktur 
    directory baru dalam suatu sistem untuk menyimpan file atau informasi. Atau dapat dikatakan misal ketika kita berada di perkuliahan minggu ketiga, kita ingin membuat sebuah directory atau folder untuk menyimpan materi dan tugas yang ada di perkuliahan minggu ketiga tersebut maka perintah yang harus kita lakukan di terminal yaitu perintah “mkdir” atau make directory. 

    Berikut merupakan contoh penerapan perintah “mkdir” diantaranya yaitu ;
    
    a. Untuk membuat folder menggunakan perintah “ mkdir nama_folder”
    
    b. Untuk membuat beberapa folder secara bersamaan menggunakan perintah “ mkdir nama_folder1 nama_folder2” dst
    
    c. Untuk membuat folder dalam path tertentu menggunakan “ mkdir /path/ke/directory/baru” 


4. “Touch" digunakan untuk membuat berkas kosong baru atau 
    memperbarui waktu terakhir ketika melakukan perubahan. Berikut merupakan contoh gambaran penerapan perintah 
    “touch” diantaranya yaitu : 

    a. Untuk membuat berkas kosong baru menggunakan perintah “ touch nama_berkas ” di terminal tapi, ketika ternyata kita sudah mempunyai file/folder dengan “ nama_berkas ” maka secara otomatis nantinya akan memperbarui waktu terakhir melakukan perubahan menjadi waktu saat itu juga tanpa mengubah isi dari file/folder tersebut.
    
    b. Perintah “ touch ” juga dapat digunakan untuk membuat berkas kosong dengan menggunakan ekstensi tertentu, misal menggunakan ekstensi “ .txt ” gunakan perintah “ nama_berkas.txt”. Ekstensi “ .txt ” biasa digunakan buat nandain kalo isi file atau berkas tersebut merupakan teks mentah atau dapat dikatakan isi file nya ga pake format khusus jadi bisa buka dimana aja, selain itu file yang menggunakan ekstensi “ .txt ” biasanya gampang di pindah antar sistem karena gada format khusus yang digunakan.

  
4. “rm atau remove” digunakan untuk menghapus file/folder yang 
    ada di sistem file. Harus hati hati saat menggunakan perintah ini takutnya ada kesalahan saat menggunakan perintah yang nantinya akan membuat kita kehilangan data yang kita miliki. 

    Berikut merupakan contoh gambaran penerapan perintah “rm” diantaranya yaitu : 
    
    a. Untuk menghapus berkas menggunakan perintah “ rm nama_berkas ”.
    
    b. Untuk menghapus folder beserta isi yang ada di dalamnya menggunakan perintah “ rm -r nama_berkas ”. *r = recursive
    
    c. Untuk menghapus berkas tanpa harus konfirmasi user menggunakan perintah “ rm -f nama_berkas ”.
    
    d. Untuk menghapus berkas dengan konfirmasi user menggunakan perintah “ rm -i nama_berkas ”. *i = interactive
    
    e. Untuk menghapus file secara bersamaan menggunakan perintah “ rm berkas1 berkas2 dst”.


5. “code” merupakan suatu perintah yang dilakukan di terminal 
    untuk membuka VScode. Saat akan menggunakan perintah ini, dapat juga disertakan nama file/folder yang akan kita buka. Dimana nama file/folder berperan sebagai argumen nya. 

    Berikut merupakan contoh gambaran penerapan “code” antara lain yaitu : 
    
    a. Untuk membuka folder di VScode menggunakan perintah “ code nama_folder ”.
    
    b. Untuk membuka file di VScode menggunakan perintah “ code nama_file ”.
    
    c. Selain itu juga dapat digunakan untuk membuka VScode tanpa file/folder tertentu menggunakan perintah “ code “.


6. “Git” diibaratkan sebagai alat yang digunakan untuk mengelola 
    sebuah perubahan, menyimpan riwayat perubahan selain itu perintah “git” juga digunakan untuk mengelola 
    kode sumber suatu proyek dengan efisien. 

    Berikut merupakan contoh gambaran penerapan perintah “git” diantaranya yaitu : 
    
    a. Untuk memulai proyek baru menggunakan perintah “ git init ”.
    
    b. Untuk menyalin proyek yang sudah ada menggunakan perintah “ git clone ”.
    
    c. Untuk menambahkan file yang sudah diubah ke proyek menggunakan perintah “ git add ”.
    
    d. Untuk menyimpan perubahan yang baru dilakukan menggunakan perintah “ git commit ”.
    
    e. Untuk melakukan push ke github menggunakan perintah “ git push ”.
    
    f. Untuk mengambil perubahan terbaru dari penyimpanan yang dilakukan secara online ke dalam proyek yang sedang kita lakukan menggunakan perintah “ git pull ”.
    
    g. Untuk melihat list perubahan yang udah kita lakukan dan yang belum disimpan menggunakan perintah “ git status ”.
    
    h. Untuk membuat, menampilkan atau menghapus cabang? dari proyek yang kita punya menggunakan perintah “ git branch ”.
    
    i. Untuk menggabungkan perubahan dari proyek lainnya ke proyek utama yang kita punya menggunakan perintah “ git merge ”.
    
    j. Untuk beralih dari satu proyek ke proyek lainnya menggunakan perintah “git checkout ”.
    
    k. Untuk melihat note dari keseluruhan perubahan yang udah kita lakukan menggunakan perintah “ git log ”.
    
    l. Untuk mengembalikan proyek ke versi sebelumnya atau menghapus perubahan yang belum kita simpan menggunakan perintah “ git reset ”.


7. “mv atau move” digunakan untuk memindahkan atau mengubah nama 
    berkas dari satu lokasi ke lokasi penyimpanan lainnya di dalam sebuah sistem. 
    
    Berikut merupakan contoh gambaran penerapan perintah “mv” diantaranya yaitu : 
    
    a. Untuk memindahkan berkas atau menggunakan perintah “ mv nama_berkas /lokasi/tujuan/ ”. Jika berkas dalam folder yang sama dengan lokasi tujuan maka perintah ini akan mengubah nama foldernya. 
    
    b. Untuk mengubah nama berkas atau folder menggunakan perintah “ mv nama_lama nama_baru ”. Perintah ini juga dapat digunakan untuk memindahkan berkas/folder ke lokasi yang sama dengan mengubah namanya.
    
    c. Untuk menggabungkan dengan opsi lainnya agar terhindar dari penghapusan atau pengubahan nama yang dilakukan secara tidak sengaja menggunakan perintah “ mv -i nama_berkas  /lokasi/tujuan/ ”. *i = interactive. Opsi dari perintah akan membutuhkan konfirmasi dari user sebelum dilakukan pemindahan atau perubahan pada nama berkas yang user miliki. 


8. “chmod atau change mode” digunakan untuk mengubah izin akses dari suatu berkas atau folder didalam suatu sistem. 
    
    Berikut merupakan contoh gambaran penerapan perintah “chmod” diantaranya yaitu : 
    
    a. Untuk mengubah izin akses yang ingin diatur untuk file atau folder menggunakan mode, dimana mode yang digunakan merepresentasikan numerik (biasa digunakan dalam format 3 digit) atau simbolis (kombinasi huruf dan simbol) menggunakan perintah “ chmod mode nama_berkas ”. Misal “ chmod 755 file.txt ”.
    
    b. Untuk melakukan penerapan khusus, misal untuk memberikan izin eksekusi untuk ke semua user menggunakan perintah “ chmod +x file.txt ” , untuk memberikan hak akses penuh ke semua user menggunakan perintah “ chmod 777 file.txt ” , untuk membatasi izin baca dan tulis hanya untuk user saja menggunakan perintah “ chmod 600 file.txt ” , dan untuk memberikan izin baca dan eksekusi untuk user dan izin baca aja untuk grup menggunakan perintah  “ chmod 755 file.txt ”.



