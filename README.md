# Informasi Dataset
Dataset ini adalah dataset Corona (Covid19) Di Indonesia baik data surveliance, cluster dan perkembangan yang diperoleh dari berbagai sumber.
Untuk data surveliance dan cluster diperoleh dari [Covid Monitoring Kementrian Kesehatan Indonesia](https://covid-monitoring.kemkes.go.id/statistik).
Sementara untuk data perkembangan diperoleh dari berbagai sumber dan sudah di cek kembali.

# Tujuan pembuatan dataset
Tujuannya yaitu untuk sebagai bahan analisis bagaimana perkembangan Covi19 di indonesia sehingga nantinya bisa dilakukan pencegahan atau
pengurangan dampak yang diakibatkan.

# Penjelasan atribut
## 1. Data Surveliance
Data ini berbentuk json, terdiri dari beberapa atribut yaitu :  
id_pasien : nomor pasien corona  
hasil_lab : hasil lab dari pengecekan  
kode_pasien : nomor pasien  
provinsi : kode provinsi asal pasien  
long : longitude  
lat : latitude  
umur : umur pasien  
jenis_kelamin : jenis kelamin (P/L)  
cluster : keterangan cluster  
keterangan : keterangan  
## 2. Data Cluster
Data ini berbentuk json, terdiri dari beberapa atribut yaitu :  
from : nomor pasien asal penyebaran  
to : nomor pasien yang menerima penyebaran  
## 3. Data Provinsi
Data ini berbentuk json, terdiri dari beberapa atribut yaitu :  
provinsi : nomor provinsi  
lat : latitude  
long :longitude  
jumlah_pasien : jumlah pasien  
## 4. Data Perkembangan Kasus Corona
Hari ke : hari ke- sejak covid19 terdeteksi di indonesia  
Tanggal : tanggal 
Kasus baru : jumlah kasus baru  
Kasus kumulatif : jumlah kasus secara kumulatif  
Dalam perawatan : jumlah pasien dalam perawatan  
Sembuh baru : jumlah pasien yang baru sembuh  
Sembuh kumulatif : jumlah pasien yang sembu secara kumulatif  
Meninggal baru : jumlah pasien baru meninggal  
Meninggal kumulatif : jumlah pasien yang meninggal secara kumulatif  
Tingkat kematian : presentase tingkat kematian diperoleh dari meninggal Meninggal kumulatif dibagi kumulatif kasus baru  
Jumlah periksa : jumlah orang yang diperiksa  
Positif : jumlah pasien yang positif  
Negatif : jumlah pasien yang negatif  
