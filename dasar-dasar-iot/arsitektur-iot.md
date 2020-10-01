# Arsitektur IoT

## Penjelasan Arsitektur IoT

Dalam arsitektur IoT, belum ada standar atau kesepakatan universal mengenai arsitektur IoT. ada salah satu contoh arsitektur iot yang bisa kita pelajari pada gambar berikut.

![](../.gitbook/assets/image%20%281%29.png)

### Keterangan

* Sensor mengkonversi parameter fisik menjadi sinyal elektronik dan aktuator mengkonversi sinyal elektronik menjadi output fisik
* Data berpindah dari sensor/aktuator ke cloud dan sebaliknya melalui gateway
* Streaming Data Processor memastikan transisi dari Input ke Data Lake Berjalan dengan baik
* Data Lake menampung raw data dari bergabai device, untuk selanjutnya diolah dalam big Data Warehouse. Data biasa disimpan dalam Bentuk unstructured dan semi structured.
* Big Data Warehouse berisi data yang berasal dari data lake diubah serta disiapkan dalam bentuk lebih terstruktur, serta hanya diambil yang akan Berguna untuk analisa selanjutnya.
* Data Analytics berfungsi mencari insight di dalam data, dengan metode statistika, Visualisasi data, melihat pola serta korelasi antar data, dan analisis lainya.
* Machine Learning membantu membuat model pembelajaran mesin dengan algoritma _Artificial Intelligence_, berdasarkan data yang diberikan. Model ini berpeluang untuk mengotomatisasi beberapa hal dalam IoT.
* Control Applications Mengirimkan aksi secara otomatis ke actuator, berdasarkan data Ataupun model yang telah dihasilkan.
* User Applications \(antar muka pengguna\) dapat berupa mobile app, ataupun web app. Aplikasi ini biasa digunakan untuk monitoring, control Serta konfigurasi behavior dari device IoT.
* Untuk Device Administrator, User Administrator, dan Security Monitoring adalah faktor pendukung. Device Administrator di bagi menjadi empat yaitu Device Identification, Configuration And Control, Monitoring And Diagnostics, dan Software Update and Maintenance. User Administrator di bagi menjadi tiga yaitu User Identification, User Privileges, dan User Log and Recording. Security Monitoring di bagi menjadi empat yaitu Network Security, Outlier Analysis, Policy Rules, dan Log Analysis.

