Proyek ini menggunakan Decision Tree Classifier untuk memprediksi apakah produk perlu di restock berdasarkan data Jumlah Terjual dan Stok. Model dilatih dengan data yang telah dibersihkan, kemudian dievaluasi menggunakan akurasi. Setelah itu, pengguna dapat memasukkan data produk baru untuk memprediksi kebutuhan restock secara otomatis.
INSTRUKSI CARA MENJALAN KAN CODE
Berikut instruksi singkat untuk menjalankan proyek ini:

1. **Install Library**: Pastikan Anda menginstal `pandas` dan `scikit-learn` dengan perintah:
   
2. **Siapkan Dataset**: Gunakan file CSV yang berisi data produk dengan kolom "Jumlah Terjual" dan "Stock".

3. **Bagi Data**: Pisahkan data menjadi fitur ("Jumlah Terjual", "Stock") dan target (apakah stok < 5).

4. **Latih Model**: Gunakan **Decision Tree Classifier** untuk melatih model dengan data yang sudah dibersihkan.

5. **Evaluasi**: Hitung akurasi model menggunakan data uji.

6. **Input Pengguna**: Masukkan jumlah terjual dan stok produk, kemudian model akan memprediksi apakah produk perlu di restock atau tidak.

7. **Jalankan**: Lakukan prediksi dan tampilkan hasilnya.
