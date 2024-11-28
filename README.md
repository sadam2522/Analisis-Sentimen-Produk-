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

# Fitur
- Pembersihan Data: Menghilangkan tanda baca, angka, dan kata-kata yang tidak penting.
- Analisis Sentimen: Menggunakan TextBlob untuk menganalisis sentimen berdasarkan polaritas.
- Visualisasi: Membuat Word Cloud untuk sentimen positif dan negatif serta Bar Chart untuk distribusi sentimen.
- Model Klasifikasi: Menggunakan Support Vector Machine (SVM) dengan kernel linear untuk mengklasifikasikan sentimen.
- Evaluasi: Menyediakan metrik evaluasi model untuk menilai kinerja SVM.

# Install 
Untuk menjalankan proyek ini, perlu menginstal beberapa pustaka Python. Anda dapat menginstalnya dengan menggunakan pip:
pip install pandas nltk textblob Sastrawi wordcloud scikit-learn matplotlib

# Output
Setelah menjalankan kode di atas, Anda akan mendapatkan:

- Distribusi Sentimen: Sebuah bar chart yang menunjukkan jumlah sentimen positif dan negatif.
- Word Cloud: Visualisasi kata-kata yang paling sering muncul pada komentar positif dan negatif.
- Evaluasi Model: Metrik seperti Accuracy, Precision, Recall, dan F-Measure untuk menilai kinerja model klasifikasi SVM.

# Kontribusi
Jika Anda ingin berkontribusi pada proyek ini, silakan buat fork dan kirim pull request Anda. Pastikan Anda menambahkan fitur atau perbaikan yang relevan dengan proyek ini.




