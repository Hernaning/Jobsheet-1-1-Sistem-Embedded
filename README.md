# Jobsheet-1-1-Sistem-Embedded


Teori Singkat


ESP-NOW adalah protokol yang dikembangkan oleh Espressif, yang memungkinkan banyak 
perangkat untuk berkomunikasi satu sama lain tanpa menggunakan Wi-Fi. Protokol ini mirip 
dengan konektivitas nirkabel 2.4GHz berdaya rendah. Pendifinisian alamat (MAC Address) 
pada masing-masing ESP32 diperlukan pada awal konfigurasi. Setelah konfigurasi alamat 
selesai dilakukan, jaringan peer-to-peer akan terbentuk dan perangkat tidak perlu melakukan 
handshaking kembali ketika akan berkomunikasi. Hal ini memunjukkan bahwa setelah 
perangkat ESP32 saling terpasang satu sama lain, koneksi akan tetap ada. Dengan kata lain, 
jika tiba-tiba salah satu ESP32 kehilangan daya atau diatur ulang, ketika restart, secara 
otomatis akan terhubung ke pasangan ESP32 yang telah terdefinisi alamatnya untuk 
melanjutkan komunikasi.


a) Memperoleh MAC Address ESP32 Receiver


![mac address](https://user-images.githubusercontent.com/119298912/209358689-ba5def6b-6339-47db-8ee8-b1b1e3564ed1.jpg)


b) ESP-NOW One-Way Point-to-Point Communication


![receiver one to point](https://user-images.githubusercontent.com/119298912/209359045-690c8bf8-3c24-4968-ba8d-8b195e0e9055.jpg)


c) One-Way, One-to-Many Communication


  1. Mengirim Pesan yang Sama Ke Beberapa Board ESP32
  
  
  ![one to many (a) receiver](https://user-images.githubusercontent.com/119298912/209359196-b4cd740f-7d2c-45b9-83af-8357da151fc7.jpg)

  2. Mengirim Pesan yang Berbeda Ke Beberapa Board ESP32
  
  (belum)
  
d) One-Way, Many-to-One Communication
