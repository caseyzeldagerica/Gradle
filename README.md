# Gradle

## Background Proyek
Proyek Gradle ini dibuat sebagai bagian dari upaya untuk mempelajari dan mengimplementasikan sistem otomatisasi build yang efisien dalam pengembangan perangkat lunak. Dengan meningkatnya kompleksitas proyek dan kebutuhan untuk integrasi berkelanjutan, alat seperti Gradle menjadi sangat penting untuk memastikan konsistensi build dan mempercepat siklus pengembangan. Gradle menawarkan fleksibilitas tinggi dan konfigurasi yang dapat disesuaikan, membuatnya menjadi pilihan yang populer di antara pengembang untuk mengelola dependensi, otomatisasi tugas, dan peningkatan alur kerja.

## Cara Menjalankan Proyek
Untuk menjalankan proyek ini, pastikan Anda telah menginstal Gradle dan JDK pada sistem Anda. Ikuti langkah-langkah berikut:
- Buka terminal atau command prompt.
- Navigasikan ke direktori root proyek menggunakan perintah
  'cd path/to/your/project.'
- Untuk menjalankan tugas khusus yang telah dibuat, masukkan perintah berikut:
'./gradlew greetingTask -Pname=YourName'
Ganti YourName dengan nama yang ingin Anda gunakan. Jika berhasil, Anda akan melihat pesan ucapan yang mencetak nama yang Anda masukkan di terminal.
- Untuk menjalankan tugas lain seperti build atau test, gunakan perintah ./gradlew build atau ./gradlew test sesuai dengan tugas yang ingin Anda jalankan.

## Deskripsi Proyek
Proyek ini merupakan demonstrasi dari penggunaan Gradle sebagai alat otomatisasi build dalam pengembangan perangkat lunak. Melalui proyek ini, kami mengeksplorasi fitur-fitur kunci Gradle, termasuk:

- Tugas Khusus: Implementasi tugas greetingTask yang menunjukkan bagaimana Gradle dapat digunakan untuk membuat tugas otomatisasi yang dapat menerima parameter CLI dan melakukan aksi berdasarkan parameter tersebut.
- Manajemen Dependensi: Demonstrasi penggunaan Gradle untuk mengelola dependensi proyek dengan mudah dan efisien, memungkinkan penambahan, penghapusan, atau pembaruan dependensi dengan perubahan minimal pada konfigurasi.
- Pengujian dan Build: Konfigurasi untuk menjalankan pengujian unit menggunakan JUnit dan proses build yang dapat dikustomisasi untuk memenuhi kebutuhan spesifik proyek.
- Konfigurasi Toolchain Java: Penyesuaian versi Java yang digunakan dalam proyek melalui Java toolchain, memastikan kompatibilitas dan fleksibilitas dalam pengembangan.
