# Laporan Project Machine Learning Predictive Analytic - Rahadianto Alif B.
# Domain Project
Rumah merupakan kebutuhan dasar dari manusia, juga merupakan kebutuhan primer yang harus dipenuhi setelah sandang dan pangan. Kenyamana dan keamana merupakan faktor yang harus terpenuhi, karena rumah merupakan tempat tinggal dan berkumpulnya keluarga dan orang-orang tercinta. Maka dari itu, kebutuhan akan hunian atau tempat tinggal yang nyaman dan aman adalah impian dari setiap manusia. Memiliki rumah merupakan suatu kebutuhan setiap keluarga. Karena rumah merupakan sarana pembina keluarga yang mendukung peri kehidupan dan penghidupan. Rumah sebagai pusat pendidikan keluarga, persemaian budaya, dan penyiapan generasi muda
Namun dewasa ini kebutuhan akan rumah yang layak huni semakin meningkat. Hal tersebut disebabkan karena terus bertambahnya jumlah penduduk namun tak seiring dengan meningkatnya taraf hidup masyarakat dengan perekonomi lemah. Oleh karena itu, sulit kiranya sekarang ini untuk membangun rumah secara langsung. Terlebih di kota besar, perbandingan harga tanah yang mahal dan bahan bangunan yang semakin lama semakin melambung tinggi dengan rata-rata gaji yang didapat oleh kebanyakan warga di kota besar, sulit kiranya untuk membangun rumah secara langsung. Sehingga hal tersebut mengharuskan sebagian masyarakat tinggal di rumah yang tidak layak huni, yang semakin terus bertambah sehingga menjadi permukiman kumuh.
# Business Understanding
# Problem Statements
Suatu perusahaan harus selalu survive agar dapat terus bersaing dengan perusahaan-perusahaan sejenis yang sama-sama bergerak dalam bisnis perumahan. Karena banyaknya perusahaan yang bergerak di bidang perumahan, maka perusahaan harus mengenali apa yang mempengaruhi harga jual pada perumahan lain. Jangan sampai kita yang seharusnya mendapat keuntungan karna terdapat kualitas yang bagus pada perumahan kita, kita malah menjualnya dengan harga rendah. Berdasarkan kondisi yang telah diuraikan sebelumnya, perusahaan akan mengembangkan sebuah sistem prediksi harga rumah untuk menjawab permasalahan berikut:
- Fitur apa yang paling mempengaruhi harga rumah?
# Goals
- Mengetahui fitur yang paling berkorelasi dengan harga rumah.

Metodologi Prediksi harga adalah tujuan yang ingin dicapai. Seperti yang kita tahu, harga merupakan variabel kontinu. Dalam predictive analytics, saat membuat prediksi variabel kontinu artinya Anda sedang menyelesaikan permasalahan regresi. Oleh karena itu, metodologi pada proyek ini adalah: membangun model regresi dengan harga diamonds sebagai target. Metrik Pengembangan model akan menggunakan beberapa algoritma machine learning yaitu K-Nearest Neighbor, Random Forest, dan Boosting Algorithm. Dari ketiga model ini, akan dipilih satu model yang memiliki nilai kesalahan prediksi terkecil.
# Data Understanding
Data yang digunakan pada project ini adalah kc_house_data.csv yang berisikan rumah pada King County pada Amerika Serikat. Dataset ini memiliki 21613 sampel data dengan berbagai macam karakteriskik. karakteristik yang dimaksud adalah fitur non numerik, pada dataset ini hanya memiliki 1 non numerik, yaitu date. fitur numerik pada dataset ini adalah floors, price, bedroom. fitur fitur ini yang akan digunakan  dalam menemukan pola pada data, sedangkan harga merupakan fitur target. Adapun uraikan seluruh variabel atau fitur pada data, adalah sebagai berikut:
- date = keterangan bulan
- floors = keterangan jumlah lantai
- price = keterangan harga
- bedroom = keterangan jumlah kamar tidur

dataset dapat dilihat dan diunduh pada link berikut: https://www.kaggle.com/datasets/shivachandel/kc-house-data

