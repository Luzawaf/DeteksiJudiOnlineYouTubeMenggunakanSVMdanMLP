# Deteksi Judi Online YouTube Menggunakan SVM dan MLP

Penelitian ini berfokus pada deteksi komentar promosi judi online berbahasa Indonesia di YouTube menggunakan algoritma Support Vector Machine (SVM) dan Multilayer Perceptron (MLP), dengan penerapan normalisasi *character obfuscation* dan TF-IDF untuk meningkatkan akurasi klasifikasi.

## Tujuan Penelitian
Mengembangkan model machine learning yang mampu mengidentifikasi komentar promosi judi online dan membedakannya dari komentar normal.

## Metode yang Digunakan
- **Algoritma:** Support Vector Machine (SVM) dan Multilayer Perceptron (MLP).
- **Feature Extraction:** TF-IDF (Unigram dan Bigram).
- **Text Preprocessing:** Standard Preprocessing, Advanced Preprocessing, dan Dataset Clean.
- **Normalisasi:** Character Obfuscation.

## Tahapan Penelitian
1. Pengumpulan dan pemahaman dataset.
2. Pembersihan dan preprocessing teks.
3. Normalisasi karakter yang disamarkan (*character obfuscation*).
4. Ekstraksi fitur menggunakan TF-IDF.
5. Pelatihan model SVM dan MLP.
6. Evaluasi dan perbandingan performa model.

## Evaluasi Model
Evaluasi dilakukan menggunakan:
- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- 5-Fold Cross Validation

## Tools & Libraries
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

## Hasil Penelitian
Model terbaik diperoleh menggunakan SVM dengan Advanced Preprocessing, yang menghasilkan akurasi sebesar 98%.
