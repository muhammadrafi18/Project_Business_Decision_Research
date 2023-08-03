# Project_Business_Decision_Research
# Pendahuluan
Sport center adalah toko yang menjual berbagai kebutuhan olahraga seperti Jaket, Baju, Tas, dan Sepatu. Toko ini mulai berjualan sejak tahun 2013, sehingga sudah memiliki pelanggan tetap sejak lama, dan tetap berusaha untuk mendapatkan pelanggan baru sampai saat ini.

Customer termasuk sudah bukan disebut pelanggan lagi (churn) ketika dia sudah tidak bertransaksi ke tokonya lagi sampai dengan 6 bulan terakhir dari update data terakhir yang tersedia.  

Data transaksi dari tahun 2013 sampai dengan 2019 dalam bentuk csv (comma separated value) dengan data_retail.csv dengan jumlah baris 100.000 baris data.
Berikut tampilan datanya:
 
 
Field yang ada pada data tersebut antara lain:
1. No
2. Row_Num
3. Customer_ID
4. Product
5. First_Transaction
6. Last_Transaction
7. Average_Transaction_Amount
8. Count_Transaction

# Customer acquisition by year
Setelah semuanya lancar, langkah berikutnya adalah membuat visualisasi data berupa trend of customer acquisition by year dengan meggunakan bar chart. 

Buat feature/kolom tambahan yang merupakan tahun dari First_Transaction dan tahun dari Last_Transaction masing-masingnya dengan nama Year_First_Transaction dan Year_Last_Transaction sebelum melakukan visualisasi.

![alt text](?raw=true)![alt text](?raw=true)

# Transaction by year
Visualisasikanlah trend jumlah transaksi per tahunnya dengan menggunakan bar chart.



# Average transaction amount by year
Dengan menggunakan seaborn pointplot, memvisualisasikan tren dari tahun ke tahun rata-rata jumlah transaksi untuk tiap-tiap produknya.



# Proporsi churned customer untuk setiap produk

Dari sisi churned customer, khususnya untuk melihat seberapa besar proporsi churned customer untuk tiap-tiap produk dapat diketahui insight-nya melalui pie chart. 

Visualisasi pie chartnya untuk keempat produk yang dimaksudkan.



# Distribusi kategorisasi count transaction
Selanjutnya akan melakukan visualisasi dari distribusi kategorisasi count transaction. 

Kategorisasi ini dilakukan dengan mengelompokkan jumlah transaksi

Setelah menambahkan kolom baru untuk kategori ini dengan nama Count_Transaction_Group, maka visualisasi dengan bar chart.



# Distribusi kategorisasi average transaction amount
Selanjutnya, akan melakukan visualisasi dari distribusi kategorisasi average transaction amount. 

Kategorisasi ini dilakukan dengan mengelompokkan rata-rata besar transaksi.

Setelah ditambahkan kolom baru untuk kategori ini dengan nama Average_Transaction_Amount_Group, maka visualisasikan dengan bar chart. 



# Visualisasi Confusion Matrix
Confusion matrix yang telah dihitung sebelumnya dapat divisualisasikan dengan menggunakan heatmap dari seaborn.

Visualisasi dari confusion matrix ini.



