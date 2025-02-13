# Provider-Detail_Wifi-Quality
Repository ini berisi mengenai analisis beberapa provider jaringan menggunakan aplikasi **Network Cell Info** dan kualitas WiFi dengan aplikasi **WiFi Analyzer**.

Kelompok 1 :
1. Alamsyah Putra 09011282227114
2. Muhammad Zihni Athallah 09011282227084
3. Muhammad Ghozi Qudama 09011282126083
4. Muhammad Azrell Samudra 09011282126063

# Alat yang digunakan untuk analisis
1. Network Cell Info, untuk mengetahui detail dari provider jaringan yang digunakan.
2. CellMapper, untuk mengetahui lokasi menara BTS (Base Transmitter Station) dari penyedia jaringan.
3. WiFi Analyzer, untuk mengetahui strength sinyal WiFi yang digunakan

# Langkah-langkah Analisis
1. Menggunakan **CellMap** untuk memastikan lokasi dari tower **BTS** terdekat.
2. Melakukan analisis data seluler dengan **Network Cell Info** di rumah.
   ![image](https://github.com/user-attachments/assets/416faa06-76a6-49f4-a09b-e21a977ae807)
   a. Muhammad Azrell Samudra

   Sinyal LTE ISAT memiliki RSRP -94 dBm, yang masuk kategori sedang dan cukup stabil untuk penggunaan normal. RSRQ -11 dB masih tergolong cukup baik, tetapi semakin mendekati -20 dB kualitasnya menurun. RSSNR 4.0 dB menunjukkan rasio sinyal terhadap noise yang cukup baik, meskipun lebih tinggi lebih diinginkan untuk koneksi yang lebih stabil.
   
   b. Muhammad Qhozi Qudama

   LTE memiliki kecepatan unduh lebih tinggi (26,6 Mb/s) dibanding WiFi (20,6 Mb/s), sementara WiFi unggul dalam kecepatan unggah (13,9 Mb/s vs. 7,4 Mb/s). Sinyal LTE cukup bagus dengan RSRP -82 dBm, tetapi memiliki SNR rendah (5.0 dB), yang dapat memengaruhi kestabilan koneksi. WiFi memiliki sinyal yang sangat kuat (-52 dBm) dengan link speed 65 Mbps, namun berada di channel 2 pada 2.4 GHz yang rentan terhadap interferensi. LTE lebih cocok untuk unduhan cepat dan mobilitas, sedangkan WiFi lebih ideal untuk unggahan stabil dalam ruangan. Untuk optimasi, pindah ke channel 1, 6, atau 11 di 2.4 GHz atau gunakan 5 GHz jika tersedia.

   c. Alamsyah Putra
   
   Sinyal XL dengan RSRP -83 dBm, ASU 57, dan RSRQ -9 dB tergolong baik dan cukup stabil untuk aktivitas sehari-hari seperti browsing dan streaming. RSRP -83 dBm menunjukkan sinyal yang masih kuat, sementara ASU 57 menandakan kualitas sinyal yang cukup tinggi. RSRQ -9 dB juga masuk kategori baik, menandakan kualitas sinyal yang stabil. Kombinasi ini memastikan koneksi yang andal, meskipun kondisi lingkungan dan kepadatan jaringan tetap dapat memengaruhi performanya.

   d. Muhammad Zihni Athallah

   Jaringan Tri "3SinyalKuatHemat" memiliki sinyal cukup baik dengan RSRP -90 dBm di sel utama, tetapi kualitasnya (RSRQ -12 dB) kurang stabil, terutama jika ada gangguan atau banyak pengguna. Nilai RSSNR 3.0 dB menunjukkan adanya noise yang dapat mempengaruhi kecepatan internet. Sel tetangga memiliki sinyal lebih lemah (RSRP -100 dBm, RSRQ -20 dB), sehingga jika jaringan berpindah ke sel ini, koneksi bisa melambat atau tidak stabil. Secara keseluruhan, sinyal masih cukup baik, tetapi kestabilannya bergantung pada lokasi dan kepadatan pengguna. Jika sering terganggu, disarankan berpindah tempat atau mengunci jaringan ke LTE Only untuk koneksi lebih stabil.

3. Melakukan analisis kualitas WiFi dengan **WiFi Analyzer**.
   ![image](https://github.com/user-attachments/assets/dbb8061d-bb94-40fa-92a3-0eba1fc953da)

   a. Muhammad Azrell Samudra

   Jaringan Wi-Fi yang terdeteksi menunjukkan bahwa DydyQueen* memiliki sinyal paling kuat sekitar -60 dBm dalam jarak 6 meter, sedangkan ADIVASA dan ZTE_2.4G_rL9Tri memiliki sinyal sangat lemah di sekitar -90 dBm, kemungkinan tidak stabil untuk digunakan. DydyQueen* berada di kanal 4, yang kurang umum dan bisa menyebabkan interferensi dengan jaringan lain. ADIVASA di kanal 1 dan ZTE_2.4G_rL9Tri di kanal 10 berpotensi mengalami gangguan, terutama jika ada lebih banyak jaringan tersembunyi. Hidden SSID yang terdeteksi memiliki sinyal sangat fluktuatif, menandakan ketidakstabilan koneksi.

   b. Muhammad Qhozi Qudama

   Sinyal Wi-Fi dengan RSSI -52 dBm tergolong kuat dan stabil, didukung oleh link speed 65 Mbps yang cukup untuk aktivitas harian seperti streaming dan video conference. Namun, jaringan menggunakan frekuensi 2.4 GHz pada channel 2, yang rentan terhadap interferensi dari perangkat lain. Hasil speed test menunjukkan kecepatan download 16.69 Mbps dan upload 19.14 Mbps, dengan ping 27 ms yang baik untuk browsing, tetapi jitter 40 ms bisa mengganggu stabilitas saat gaming atau video call. Analisis WiFi Analyzer menunjukkan banyak SSID lain di channel 2 dan 6, yang bisa menyebabkan interferensi. Disarankan mengganti channel ke 1 atau 11, atau beralih ke pita 5 GHz jika tersedia untuk koneksi yang lebih stabil.

   c. Alamsyah Putra

   WiFi "HAMIZIAN" memiliki sinyal yang sangat kuat dengan RSSI -40 dBm, menunjukkan perangkat berada sangat dekat dengan router (sekitar 1 meter). Beroperasi pada frekuensi 2.4 GHz dengan channel 3 (2422 MHz), yang tidak umum digunakan karena kanal optimal di 2.4 GHz biasanya 1, 6, atau 11 untuk menghindari interferensi. Kecepatan koneksi mencapai 65 Mbps, cukup baik untuk aktivitas sehari-hari seperti browsing, streaming, dan video call, dengan keamanan yang memadai menggunakan WPS WPA WPA2. Namun, untuk menghindari potensi gangguan dari interferensi channel 3, disarankan untuk beralih ke channel 1, 6, atau 11. Jika router mendukung 5 GHz, pindah ke pita tersebut bisa memberikan kecepatan lebih tinggi dan stabilitas yang lebih baik.

   d. Muhammad Zihni Athallah

   Jaringan WiFi @net-unsri-newBB beroperasi pada frekuensi 5 GHz di Channel 52 (5260 MHz) dengan lebar pita 80 MHz dan kekuatan sinyal cukup kuat di sekitar 2.3 meter dengan -54 dBm, serta menawarkan kecepatan koneksi 96 Mbps yang ideal untuk aktivitas berat seperti streaming dan gaming. Selain itu, jaringan ini tersedia di Channel 60 (5300 MHz) dengan sinyal lebih lemah (-78 dBm) hingga jarak 35.7 meter, dan juga pada frekuensi 2.4 GHz di Channel 11 (2462 MHz) dengan jangkauan lebih luas hingga 9.7 meter dan kekuatan sinyal -60 dBm. Perangkat yang digunakan berasal dari Hewlett Packard Enterprise (HPE), yang umumnya ditemukan di lingkungan kampus atau perusahaan besar.


   Dokumentasi Tambahan
   
![image](https://github.com/user-attachments/assets/968b467b-b403-43dc-90b9-b671cbb2d917)


