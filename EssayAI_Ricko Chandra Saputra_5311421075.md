Nama   : Ricko Chandra Saputra 
|| NIM    : 5311421075

**Penggunaan Algoritma KNN untuk Membantu Klasifikasi Data Pasien Penyakit Diabetes**

Penyakit diabetes adalah salah satu penyakit yang ditandai dengan kadar glukosa darah yang tinggi akibat dari gangguan kerja insulin yang merupakan hormon pada tubuh yang mengatur kadar gula dalam darah. 
Penyakit diabetes dapat menyebabkan dampak yang serius, seperti gangguan jantung, ginjal, mata, saraf, dan pembuluh darah. 
Di Indonesia sendiri jumlah pasien yang terkena penyakit diabetes menurut laporan International Diabetes Federation (IDF) mencapai 41 ribu orang pada tahun 2022. 
Oleh karena itu untuk mengatasi jumlah pasien penyakit diabetes yang semakin bertambah, maka dibutuhkan suatu metode atau solusi untuk mengetahui penyakit diabetes sejak dini dan dapat ditangani secara langsung. 

Salah satu cara untuk mendeteksi penyakit diabetes adalah dengan melakukan klasifikasi data pasien berdasarkan gejala-gejala dan hasil pemeriksaan laboratorium yang dimiliki. 
Klasifikasi data pasien dengan gejala penyakit diabetes dapat membantu dokter dalam melakukan diagnosis dan pengobatan yang tepat bagi pasien.  
Selain itu klasifikasi data pasien dengan gejala penyakit diabetes juga dapat membantu pasien dalam meningkatkan kesadaran dan kewaspadaan terhadap penyakitnya.

Salah satu metode klasifikasi data yang dapat digunakan adalah K-Nearest Neighbor (KNN). 
KNN adalah salah satu algoritma dalam machine learning yang memiliki prinsip kerja dengan mencari tetangga terdekat dari data yang baru diberikan berdasarkan jarak euclidean atau jarak manhattan.
Algoritma ini pada prinsip kerjanya menggunakan data pelatihan untuk menentukan kelas atau target dari suatu objek baru berdasarkan jaraknya dengan objek pelatihan yang kelas atau targetnya sudah diketahui.
Algoritma KNN ini juga dapat disesuaikan untuk mengatasi data yang tidak seimbang dengan cara memberikan bobot pada setiap tetangga berdasarkan jaraknya dari objek baru.
Pada proses klasifikasi menggunakan algoritma KNN ini dibutuhkan nilai k yang berfungsi sebagai menentukan jumlah tetangga terdekat yang akan dipertimbangkan.
KNN memiliki beberapa kelebihan, seperti mudah dipahami dan diimplementasikan, fleksibel terhadap jenis data, dan tidak memerlukan asumsi tentang distribusi data. 
Namun, KNN juga memiliki beberapa kelemahan, seperti sensitif terhadap data yang tidak relevan atau mempengaruhi klasifikasi atau regresi, membutuhkan waktu komputasi yang lama, dan memerlukan pemilihan nilai k yang tepat.

Data parameter penyakit diabetes yang akan digunakan untuk diklasifikasi menggunakan algoritma KNN adalah meliputi konsentrasi glukosa, tekanan darah (mmHg), 
ketebalan lipatan kulit trisep (mm), tingkat insulin pada tubuh, indeks massa tubuh, indikator riwayat diabetes dalam keluarga. dan umur pasien. 
Untuk mempermudah proses klasifikasi dengan algoritma KNN, maka dapat menggunakan beberapa alat bantu seperti orange data mining dan jupyter notebook. 
Klasifikasi menggunakan algoritma KNN ini dapat dengan cara memasukan nilai indikator dari pasien yang akan diperiksa berdasarkan data parameter yang sudah disebutkan sebelumnya dan mengatur nilai k yang optimal untuk mendapatkan hasil klasifikasi yang terbaik. 
Kemudian langkah selanjutnya adalah algoritma KNN akan melakukan klasifikasi data pasien dengan gejala penyakit diabetes.
Kemudian setelah proses klasifikasi, maka didapatkan hasil diagnosa bahwa pasien tersebut terkena penyakit diabetes atau tidak berdasarkan data yang sudah diklasifikasi. 
