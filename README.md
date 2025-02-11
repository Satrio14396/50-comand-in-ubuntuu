# 50 comand in ubuntuu
Berikut adalah daftar 50 perintah Ubuntu yang sering digunakan, beserta penjelasannya:
1-10: Navigasi & Manajemen File

    pwd – Menampilkan direktori kerja saat ini.
    ls – Menampilkan isi direktori.
    cd [direktori] – Berpindah ke direktori lain.
    mkdir [nama_folder] – Membuat folder baru.
    rmdir [nama_folder] – Menghapus folder kosong.
    rm [file] – Menghapus file.
    rm -r [folder] – Menghapus folder beserta isinya.
    cp [file1] [file2] – Menyalin file.
    mv [file1] [file2] – Memindahkan atau mengganti nama file.
    find [path] -name "[nama_file]" – Mencari file di dalam direktori.

11-20: Manajemen Paket & Software

    apt update – Memperbarui daftar paket.
    apt upgrade – Meng-upgrade semua paket yang sudah usang.
    apt install [nama_paket] – Menginstal paket baru.
    apt remove [nama_paket] – Menghapus paket.
    dpkg -i [nama_paket.deb] – Menginstal paket dari file .deb.
    snap install [nama_paket] – Menginstal aplikasi dari Snap.
    snap remove [nama_paket] – Menghapus aplikasi Snap.
    flatpak install [remote] [package] – Menginstal aplikasi Flatpak.
    flatpak remove [package] – Menghapus aplikasi Flatpak.
    which [command] – Menunjukkan lokasi eksekusi dari perintah.

21-30: Informasi Sistem & Proses

    uname -a – Menampilkan informasi sistem.
    uptime – Menampilkan lama sistem berjalan.
    top – Menampilkan proses yang berjalan.
    htop – Versi lebih interaktif dari top (perlu diinstal).
    ps aux – Menampilkan daftar proses yang berjalan.
    kill [PID] – Menghentikan proses berdasarkan ID.
    pkill [nama_proses] – Menghentikan proses berdasarkan nama.
    df -h – Menampilkan informasi penggunaan disk.
    du -sh [folder] – Menampilkan ukuran folder tertentu.
    free -h – Menampilkan penggunaan RAM.

31-40: Manajemen Pengguna & Hak Akses

    whoami – Menampilkan pengguna saat ini.
    id – Menampilkan ID pengguna dan grup.
    adduser [nama_user] – Menambahkan pengguna baru.
    deluser [nama_user] – Menghapus pengguna.
    passwd [nama_user] – Mengubah kata sandi pengguna.
    chmod [mode] [file] – Mengubah izin file.
    chown [user]:[group] [file] – Mengubah kepemilikan file.
    groups [user] – Menampilkan grup pengguna.
    usermod -aG [grup] [user] – Menambahkan pengguna ke grup.
    sudo [command] – Menjalankan perintah sebagai administrator.

41-50: Jaringan & Lainnya

    ping [domain/ip] – Mengecek koneksi ke server.
    wget [url] – Mengunduh file dari URL.
    curl [url] – Mengambil data dari URL.
    ifconfig – Menampilkan informasi jaringan (butuh net-tools).
    ip a – Menampilkan alamat IP.
    netstat -tulnp – Menampilkan daftar port yang digunakan.
    ssh [user]@[host] – Masuk ke server via SSH.
    scp [file] [user]@[host]:[path] – Mengirim file via SSH.
    history – Menampilkan riwayat perintah.
    clear – Membersihkan tampilan terminal.
