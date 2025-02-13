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
3. Melakukan analisis data seluler dengan **Network Cell Info** di dekat tower BTS.
4. Melakukan analisis kualitas WiFi dengan **WiFi Analyzer**.
   ![image](https://github.com/user-attachments/assets/dbb8061d-bb94-40fa-92a3-0eba1fc953da)


