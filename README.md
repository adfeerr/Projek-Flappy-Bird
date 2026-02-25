# Projek-Flappy-Bird
Kelompok:
1. Sulthan
2. Fakhri
3. Tristan
4. Angga

Kami dari kelompok 12 ingin menjelaskan bagaimana cara kerja kode projek Flappy Bird ini. Tapi sebelum itu, ada cara mendownload gamenya


# CARA MAININ GAMENYA!
Repository ini bersifat publik dan dapat di akses lewat 2 cara. Yaitu, download langsung, atau download lewat terminal.

Download lewat terminal(Khususnya terminal VScode):
1. Download VScode
2. Ketik "brew install git" di dalam terminal VScode
3. Copy file github kami
4. Ketik lagi di terminal VScode "git clone [KODE HTTPS]"
5. Lalu, file akan otomatis tergenerate

Download langsung filenya:
1. Download VScode
2. Buat folder untuk file ini
  <img width="1351" height="626" alt="image" src="https://github.com/user-attachments/assets/ee04d846-78af-4a58-8a50-19f6f1b65ce1" />

3. Buka github dan download code dari git kami, dan masukan file code kami ke dalam folder yang udah kalian buat
4. Lalu buka VScode dan arahkan kursor ke "File" dan klik
5. Terakhir, klik "Open Folder" dan cari file yang udah di buat

# Cara Menjalankan
1. Download Python
2. Download pygame
3. Jalankan game


Dan ini adalah, logic dari game yang kami buat
# Langkah 1 (Importing)
1. Import module pygame(untuk fungsional game dan menampilkan game)
2. Import system dan hanya mengambil spesifik yaitu function exit
3. Import module random(untuk mengatur pipa di dalam game)

# Langkah 2 (Variable dan Class)
1. Buat variable patokan untuk setiap class
2. Buat variable dan class untuk kategori "Bird"
3. Buat variable dan class untuk kategori "Pipa/Pipe"

# Langkah 3 (Gambar Flappy Bird)
Kami mengimport foto Flappy Bird dari internet dan rename nama filenya agar mudah dimengerti, lalu memasukan setiap gambar kedalam variabel yang udah disediakan untuk proses game logic berikutnya, dan menggunakan fungsi pygame agar bisa di load di dalam game. Sebelum itu juga kami menambahkan variabel untuk memenuhi logic gamenya.

# Langkah 4 (Game Logic)
Dalam langkah ini terdapat beberapa komponen yang membuat game ini berjalan dan dapat dinikmati. Yaitu:
1. Skor
2. Pergerakan loncat Burungnya
3. Generate Pipa, dan...
4. Kondisi saat user kalah

Oleh karena itu, agar ketiga fungsi diatas bisa berjalan, kami mendeklarasi 3 Function, kondisi kalah(USER=FALSE), dan terakhir loop agar game tetap berjalan dan tergenerate seiring skor terus bertambah.

Ada 3 Function utama:
1. draw = skor
2. move = pergerakan burung
3. create_pipes = generate pipanya

setelah 3 Function tadi selesai, kami menambahkan fungsi pygame untuk menginisiasi/membuka windows baru untuk menampilkan output 3  Function tadi. Lalu, kami tambahkan while loop untuk menciptakan kondisi (jika USER != False), maka game akan tetap berlanjut dan mengupdate objek dalam game. Namun, (Jika USER == False) maka Game Over dan game akan selesai.
