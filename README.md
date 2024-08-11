# Capstone3_IndahWidya

**Prediksi Harga Rumah Menggunakan Metode Algoritma XGBoost dengan Dataset Perumahan California**

Dataset ini adalah kumpulan data perumahan dari wilayah California, Amerika Serikat, yang diperoleh dari sensus tahun 1990. 

Salah satu tantangan utama bagi pengembang perumahan adalah menentukan harga properti yang tepat dan memilih lokasi yang sesuai untuk pembangunan perumahan, agar harga yang ditetapkan tidak salah sasaran. Pengembang tentu tidak ingin membangun perumahan mewah di daerah dengan pendapatan rendah atau sebaliknya, membangun perumahan sederhana di kawasan elit. Keputusan yang tidak tepat ini dapat mempengaruhi penjualan properti tersebut.

Tujuan dari pemodelan ini adalah untuk memperkirakan harga jual sebuah rumah berdasarkan fitur-fitur yang tersedia di daerah California. Perbedaan dalam berbagai fitur, seperti jumlah kamar, lokasi, dan pendapatan rata-rata populasi, dapat meningkatkan keakuratan prediksi harga jual, yang pada akhirnya dapat memberikan keuntungan bagi pengembang perumahan sambil memastikan bahwa properti tersebut sesuai dengan target pasar yang diinginkan.

Algoritma yang digunakan: XGBoost
Metrik Evaluasi:
RMSE: mengukur standar deviasi residu dari hasil prediksi dengan nilai aktual
MAE: alternatif untuk data dengan banyak outlier
RMSLE: pengukuran rmse dalam skala logaritmik karena rentang nilai prediksi nya besar, dalam skala ratusan ribu USD
MAPE: relative error
R-Square: menghitung kemampuan model dalam menjelaskan hasil prediksi
