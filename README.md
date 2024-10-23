# Computer Rental Manager
______ _____ _____ ____________ ______ _______ |\ \ _____
\ \ \ \ \ _ / \ |\ \ \ \ / / | | / |
\ | | | / /| | |_/\ \/| \ \ | /| | |/ /| / \
| | | | / / //| |\ _|/ | |/ // | |_/ | | /\ \
| _/ /| | | ||/ | | | |// |\ \ | / | | | \
|\ | | | |________ __ / / __ | |\ \ | \ _|/ | / \
| \ __ |\ |\ \ / / // | / /|| | | \ \ |\ /\ \
\ _/\ \ | _| |_/| |/| // |//| \ _\ | _\ _\ \ | |//| | | //| | || | | / | | / | | | \ | | | | | | | || | | |_____| |||/ ||/ ||/ |____|/ || |||| ||/ |__/


Computer Rental Manager adalah aplikasi desktop yang digunakan untuk mengelola penyewaan komputer. Proyek ini dikembangkan menggunakan Java dan JavaFX untuk memberikan antarmuka pengguna (GUI) yang interaktif. Aplikasi ini memungkinkan pengguna untuk menyewa, mengembalikan, dan menambah komputer dalam sistem penyewaan.

## Fitur Utama

- **Penambahan Komputer:** Tambah komputer baru ke dalam daftar komputer yang tersedia untuk disewakan.
- **Penyewaan Komputer:** Pengguna dapat menyewa komputer dengan menentukan durasi rental.
- **Pengembalian Komputer:** Setelah penyewaan selesai, pengguna dapat mengembalikan komputer dan melihat detail penyewaan.
- **Manajemen Biaya Rental:** Sistem secara otomatis menghitung biaya berdasarkan durasi penyewaan (Rp. 5000 per jam).

## Prasyarat

Pastikan Anda telah menginstal beberapa perangkat lunak berikut sebelum menjalankan proyek ini:

- [Java Development Kit (JDK) 11 atau lebih tinggi](https://www.oracle.com/java/technologies/javase-jdk11-downloads.html)
- [JavaFX SDK](https://openjfx.io)

## Cara Menjalankan Proyek

1. **Kloning repositori:**

    ```bash
    git clone https://github.com/username/computer-rental-manager.git
    cd computer-rental-manager
    ```

2. **Setup Proyek:**

    Pastikan bahwa JavaFX sudah diatur dengan benar dalam environment Anda. Jika menggunakan IDE seperti IntelliJ IDEA atau Eclipse, tambahkan `javafx-sdk/lib` ke dalam classpath.

    Jika menjalankan proyek menggunakan `javac` dan `java`, gunakan perintah berikut:

    ```bash
    javac --module-path /path/to/javafx-sdk/lib --add-modules javafx.controls,javafx.fxml -d bin src/org/example/ComputerRental/*.java
    ```

    Kemudian, untuk menjalankan aplikasi:

    ```bash
    java --module-path /path/to/javafx-sdk/lib --add-modules javafx.controls,javafx.fxml -cp bin org.example.ComputerRental.ComputerRentalManager
    ```

3. **Menjalankan Aplikasi:**

   Setelah setup selesai, Anda bisa menjalankan aplikasi menggunakan command-line atau langsung dari IDE Anda. Aplikasi akan terbuka dalam GUI di mana Anda dapat mengelola komputer yang disewakan.

## Struktur Proyek

- **`ComputerRentalManager`**: Kelas utama untuk mengelola aplikasi penyewaan komputer.
- **`Computer`**: Kelas model yang mewakili data komputer yang disewakan, seperti ID, tipe, waktu penyewaan, dan biaya.

## Informasi Tambahan

- **Biaya Sewa:** Rp. 5000 per jam
- **Lisensi:** © 2024 Computer Rental Management. All rights reserved.

Jika Anda mengalami masalah atau membutuhkan bantuan, jangan ragu untuk membuka issue di repositori GitHub kami.

