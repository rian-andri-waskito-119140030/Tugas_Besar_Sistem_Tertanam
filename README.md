# Tugas_Besar_Sistem_Tertanam
<br/>Sistem Monitoring Minuman Menggunakan Sensor Suhu MLX90614 Dan Sensor Ultrasonik

# Kelompok_9
<br/>Rian Andri Waskito - 119140030
<br/>Putu Ary Kusuma Yudha - 119140098
<br/>Rahmad Sidiq - 119140096
<br/>Sisilia Juli Anggraini - 118140167

# Arsitektur Sistem
![arsitektur_sistem](https://user-images.githubusercontent.com/82927821/147825576-1543f776-4737-40bd-a30e-cc1a91f8963c.jpg)


# Deskripsi
<br/>Alat yang kami buat adalah sistem monitoring suhu minuman menggunakan sensor suhu MLX90614. Ketika suhu minuman sudah ideal maka buzzer dan lampu led hijau akan menyala. Sedangkan jika suhu minuman belum ideal maka led merah akan menyala.<br/>
<br/>Kondisi 1 (awal)
<br/>Sensor Ultrasonik mengukur jarak > = 4 cm
<br/>Output Kedua Lampu mati dan buzzer mati
![IMG20211230095531](https://user-images.githubusercontent.com/82927821/147799123-06f89639-4c3e-49be-b2d3-80eee1cdb749.jpg)<br/>
<br/>
<br/>Kondisi 2  (Minuman panas diletakan pada alat)
<br/>Sensor Ultrasonik mengukur jarak < 4 cm
<br/>Sensor MLX90614 mengukur suhu >50 oC
<br/>Output Lampu led merah menyala dan buzzer mati
![IMG20211230102916](https://user-images.githubusercontent.com/82927821/147799154-6840542d-06c0-4c84-ad01-d3d3ffbef2ad.jpg)<br/>
<br/>
<br/>Kondisi 3 (Minuman sudah dapat diminum)
<br/>Sensor Ultrasonik mengukur jarak < 4 cm
<br/>Sensor MLX90614 mengukur suhu <=50 oC
<br/>Output Lampu led hijau menyala dan buzzer berbunyi
![IMG20211230095441](https://user-images.githubusercontent.com/82927821/147799170-13b9681d-eea3-48f5-974b-c0d63a0f6c40.jpg)<br/>
<br/>
# Video Demo Project
[![Video](https://img.youtube.com/vi/TQs7PqWAGs8/0.jpg)](https://www.youtube.com/embed/TQs7PqWAGs8) </br>
Link:- https://www.youtube.com/watch?v=TQs7PqWAGs8 </br>

# Referensi
[1]T. d. -. detikHealth, "10 Manfaat Minum Air Putih Hangat di Pagi Hari dan Sebelum Tidur," Detikcom, 17 Desember 2020. [Online]. Available: https://health.detik.com/berita-detikhealth/d-5298233/10-manfaat-minum-air-putih-hangat-di-pagi-hari-dan-sebelum-tidur/1. [Accessed 27 Oktober 2021].
<br/>[2]A. Manullang, Martin Clinton Tosima Saputra, D. Sipangkar, and A. M. Bangun, Alexander Diva Grael Ardhi, “IoT and Cloud 1,” vol. 0, .
