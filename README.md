# SMART TRASH CAN
### Tong Sampah Pintar Berbasis Arduino

## 1. Pengertian Proyek

Smart Trash Can adalah sebuah tempat sampah pintar yang dirancang menggunakan teknologi mikrokontroler dan sensor untuk mempermudah pengguna ketika membuang sampah.

Tempat sampah ini memiliki sistem buka dan tutup otomatis menggunakan motor servo. Selain itu, terdapat sensor ultrasonik yang berfungsi mendeteksi keberadaan tangan atau benda di dekat tempat sampah. Ketika seseorang mendekat, sensor akan mendeteksi jarak dan buzzer akan mengeluarkan bunyi sebagai tanda bahwa objek telah terdeteksi.

Proyek ini dibuat untuk meningkatkan kebersihan, kenyamanan, dan mengurangi kontak langsung dengan tempat sampah.

## 2. Tujuan Pembuatan

- Membuat tempat sampah yang dapat terbuka dan tertutup secara otomatis.
- Mengurangi kontak langsung antara tangan dengan tempat sampah.
- Memanfaatkan teknologi Arduino dan sensor ultrasonik.
- Menerapkan sistem otomatisasi dalam kehidupan sehari-hari.
- Meningkatkan kreativitas dan kemampuan dalam bidang teknologi.

## 3. Komponen yang Digunakan

1. **Arduino Uno** – Sebagai otak atau pengendali utama sistem.
2. **Sensor Ultrasonik HC-SR04** – Untuk mendeteksi jarak tangan atau benda.
3. **Motor Servo SG90** – Untuk menggerakkan tutup tempat sampah secara otomatis.
4. **Buzzer** – Untuk menghasilkan bunyi ketika ada objek yang terdeteksi.
5. **Kabel Jumper** – Untuk menghubungkan setiap komponen.
6. **Breadboard** – Sebagai media penghubung rangkaian elektronik.
7. **Tempat Sampah** – Sebagai wadah utama proyek.
8. **Adaptor atau Sumber Daya 5V** – Untuk memberikan daya pada rangkaian.

## 4. Cara Kerja Smart Trash Can

Sistem Smart Trash Can bekerja melalui beberapa tahapan:

1. Arduino dinyalakan dan mulai menjalankan program.
2. Sensor ultrasonik HC-SR04 akan mendeteksi jarak objek di depannya.
3. Ketika tangan seseorang berada dalam jarak sekitar 20 cm, sensor mengirimkan data ke Arduino.
4. Arduino memproses data tersebut dan mengaktifkan buzzer sehingga mengeluarkan bunyi.
5. Motor servo bergerak untuk membuka tutup tempat sampah secara otomatis.
6. Setelah tangan menjauh selama beberapa detik, motor servo akan menggerakkan tutup kembali ke posisi tertutup.

Dengan sistem ini, pengguna tidak perlu menyentuh tutup tempat sampah secara langsung.

## 5. Cara Pembuatan

**Langkah 1: Menyiapkan alat dan bahan**

Siapkan seluruh komponen elektronik seperti Arduino Uno, sensor ultrasonik, motor servo, buzzer, kabel jumper, serta tempat sampah yang akan digunakan.

**Langkah 2: Merangkai komponen elektronik**

Hubungkan sensor ultrasonik, motor servo, dan buzzer ke Arduino menggunakan kabel jumper sesuai dengan pin yang telah ditentukan.

**Langkah 3: Memasang sensor**

Pasang sensor ultrasonik pada bagian depan tempat sampah agar dapat mendeteksi tangan atau benda yang mendekat.

**Langkah 4: Memasang motor servo**

Pasang motor servo pada bagian tutup tempat sampah. Hubungkan mekanisme servo dengan tutup menggunakan penghubung mekanis agar tutup dapat terbuka dan tertutup.

**Langkah 5: Memasukkan program**

Hubungkan Arduino ke komputer menggunakan kabel USB. Kemudian buat dan unggah program menggunakan aplikasi Arduino IDE.

**Langkah 6: Melakukan pengujian**

Nyalakan sistem dan dekatkan tangan ke sensor. Periksa apakah buzzer berbunyi dan tutup tempat sampah dapat terbuka secara otomatis. Setelah tangan menjauh, periksa apakah tutup kembali tertutup.

## 6. Manfaat Proyek

- Mempermudah pengguna ketika membuang sampah.
- Menjaga kebersihan dan mengurangi sentuhan langsung.
- Mengurangi penyebaran kuman akibat kontak dengan tutup tempat sampah.
- Memanfaatkan teknologi otomatisasi.
- Menjadi salah satu penerapan teknologi Internet of Things dan sistem mikrokontroler dalam kehidupan sehari-hari.

## 7. Kesimpulan

Smart Trash Can merupakan inovasi tempat sampah pintar yang memanfaatkan Arduino, sensor ultrasonik, motor servo, dan buzzer. Sistem ini mampu mendeteksi keberadaan objek, memberikan tanda berupa bunyi, serta membuka dan menutup tutup tempat sampah secara otomatis.

Melalui proyek ini, kita dapat memahami penerapan mikrokontroler, sensor, motor servo, dan pemrograman dalam menciptakan teknologi yang bermanfaat bagi kehidupan sehari-hari.
