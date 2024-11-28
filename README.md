# Analisis Sentimen Produk Skincare dengan SVM

Proyek ini bertujuan untuk melakukan analisis sentimen pada ulasan produk skincare menggunakan model klasifikasi Support Vector Machine (SVM). Data yang digunakan berasal dari file CSV yang berisi komentar tentang produk skincare, yang kemudian dianalisis untuk menentukan apakah sentimen dalam komentar tersebut positif atau negatif.


# Deskripsi
Dalam proyek ini, kami melakukan beberapa langkah penting untuk menganalisis sentimen ulasan produk:

1. Pembersihan Data: Melakukan konversi teks menjadi huruf kecil dan membersihkan komentar dari karakter yang tidak relevan.
2. Tokenisasi: Memecah kalimat menjadi kata-kata.
3. Penghapusan Stopwords: Menghapus kata-kata umum yang tidak memiliki makna penting untuk analisis sentimen.
4. Stemming: Mengubah kata menjadi bentuk dasarnya untuk menyederhanakan analisis.
5. Analisis Sentimen: Menggunakan TextBlob untuk menghitung polaritas dan mengklasifikasikan sentimen sebagai positif atau negatif.
6. Visualisasi: Membuat bar chart dan word clouds untuk memvisualisasikan distribusi sentimen dan kata-kata yang sering muncul pada masing-masing sentimen.
7. Model SVM: Membangun model klasifikasi menggunakan Support Vector Machine (SVM) untuk memprediksi sentimen ulasan produk.
8. Evaluasi Model: Menggunakan berbagai metrik evaluasi seperti Accuracy, Precision, Recall, dan F-Measure untuk menilai kinerja model.
