# Model Prediksi Pembatalan Registrasi Kamar Hotel
Faishal Hananta Aji
JCDSBSDAM-31

# Stakeholder
- Bidang administrasi hotel
- Bidang sales dan marketing hotel
- Bidang front office hotel

# Permasalahan
- Bagaimana cara memprediksi apakah seorang calon customer yang ingin melakukan reservasi kamar nantinya akan membatalkan reservasi kamar tersebut dari dini hari.
- Bagaimana melihat faktor-faktor yang paling mempengaruhi kemungkinan seorang customer untuk membatalkan reservasi kamar.

# Tujuan
- Menemukan sistem yang dapat berperan sebagai alternatif/pembantu terhadap strategi overbooking hotel dalam menangani pembatalan registrasi kamar hotel.
- Melihat faktor-faktor yang paling mempengaruhi kemungkinan seorang customer untuk membatalkan reservasi kamar.

# Insight Kunci
1. Model yang bisa memprediksi pembatalan registrasi kamar hotel dengan baik: model Random Forest
   
2. Kemungkinan registrasi kamar dibatalkan akan lebih tinggi jika:
    - Customer melakukan pembayaran deposit yang non-refundable
    - Customer sering melakukan pembatalan registrasi kamar sebelumnya
    - Jumlah permintaan khusus yang dibuat saat memesan kamar sedikit
    - Tipe customer Transient

3. Kemungkinan registrasi kamar dibatalkan akan lebih kecil jika:
    - Customer tidak melakukan pembayaran deposit yang non-refundable
    - Customer belum pernah melakukan pembatalan registrasi kamar sebelumnya
    - Jumlah permintaan khusus yang dibuat saat memesan kamar banyak
    - Customer mengindikasikan kalau ia membutuhkan jumlah parkir yang banyak
    - Tipe customer Transient-Party, atau bukan Transient
 
# Tools & Teknologi
- Python: pandas, numpy, seaborn, matplotlib, sklearn, category_encoders, imblearn, shap
- Visual Studio Code: sebagai alat dan media untuk proses analisis

# Dataset
Hotel Booking Demand
Keduanya dapat diakses di [https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page](https://drive.google.com/drive/folders/17KIeOXK7eYGuzgpn_IljlUFcE4v96lSL)
