Nama : Sania Apriza 
<br> Kelas : TK 3 C 
<br> NIM : 09030282327059 

# Arsitektur Komputer

> ## SOAL <br> Carilah perbedaan antara Arsitektur Linux Oc dengan  Windows 
<br> Jawab : 
<br><br>
A. Kernel 
   - Linux OS : 
     * Kernel Monolitik : Semua fungsi inti, termasuk perangkat keras, memori, dan driver, dijalankan dalam satu kernel.
     * Modularitas : Kernel Linux bersifat modular, memungkinkan modul seperti driver dimuat atau dilepas tanpa perlu reboot.
     * Sumber Terbuka : Kernel ini berbasis open source, yang memungkinkan kontribusi dan modifikasi dari siapa saja.

   - Windows OS : 
     * Kernel Hybrid : Windows menggabungkan konsep kernel monolitik dan microkernel, dengan beberapa fungsi berjalan di ruang pengguna untuk > > * stabilitas lebih baik.
     * Sumber Tertutup : Kernel Windows adalah proprietary, dikembangkan dan dikelola secara eksklusif oleh Microsoft.

B. Manajemen Memori
   - Linux OS :
     * Menggunakan paging dan swapping yang lebih fleksibel, memberikan pengguna kendali lebih dalam pengaturan memori, seperti ukuran swap dan penggunaan RAM.
     * Memori virtual Linux lebih adaptif terhadap berbagai jenis perangkat keras.

   - Windows OS :
     * Menggunakan paging memori virtual yang sebagian besar diatur secara otomatis, dengan kontrol yang lebih sedikit bagi pengguna.
     * Manajer memori Windows efisien, namun tidak sefleksibel Linux dalam konfigurasi.
C. Keamanan
   - Linux OS : 
     * Keamanan lebih transparan karena sifat open source-nya, memungkinkan siapa pun untuk mengaudit atau memperbaiki celah keamanan.
     * Linux memiliki sistem izin yang ketat dan mendukung alat keamanan tambahan seperti SELinux dan AppArmor.

   - Windows OS : 
     * Dilengkapi dengan alat keamanan seperti Windows Defender, BitLocker, dan User Account Control (UAC).
     * Windows menjadi target malware lebih sering, tetapi terus mengembangkan teknologi keamanan dan memiliki patch otomatis yang lebih terintegrasi.

D. Sistem File 
   -  Linux OS : 
     * Mendukung berbagai sistem file seperti ext4, XFS, Btrfs, dan ZFS, menawarkan pilihan untuk kinerja dan integritas data.
     * Menggunakan struktur direktori FHS, di mana perangkat diakses melalui mount point tanpa penggunaan drive letter.

   - Windows OS :
     * Menggunakan NTFS sebagai sistem file utama, mendukung fitur seperti kompresi, keamanan, dan enkripsi, serta FAT32 dan exFAT untuk kompatibilitas yang lebih luas.
     * Sistem file Windows lebih ramah pengguna umum, dengan struktur direktori seperti Program Files dan drive yang diidentifikasi dengan huruf (C:, D:, dll).
E. Filosofi Desain
   - Linux OS : 
     * Didesain berdasarkan prinsip open source, memungkinkan pengguna untuk memodifikasi dan mendistribusikan ulang sesuai kebutuhan.
     * Linux sangat modular dan fleksibel, dengan berbagai distribusi yang disesuaikan untuk server, desktop, atau sistem embedded.
 
   - Windows OS :
     * Berfokus pada kemudahan penggunaan, dirancang untuk memberikan antarmuka grafis yang ramah bagi pengguna akhir.
     * Menawarkan dukungan luas untuk perangkat lunak dan perangkat keras dengan ekosistem yang terintegrasi, khususnya di desktop.

F. Manajemen Perangkat Lunak
   - Linux OS :
     * Menggunakan manajer paket seperti APT, Yum/DNF, atau Pacman untuk instalasi perangkat lunak dari repository terpusat.
     * Juga mendukung kompilasi dari kode sumber, memberikan fleksibilitas bagi pengguna teknis.
   - Windows OS :
     * Instalasi perangkat lunak biasanya melalui file .exe atau .msi dengan antarmuka wizard.
     * Microsoft Store : menawarkan distribusi perangkat lunak, tetapi ekosistemnya tidak sefleksibel sistem repository di Linux.
