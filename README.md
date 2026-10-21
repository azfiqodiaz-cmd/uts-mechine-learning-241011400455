# UTS Machine Learning — Diaz Azfiqo

- Nama: Diaz Azfiqo
- NIM: 241011400455
- `RANDOM_STATE`: 55 (dua digit terakhir NIM)

## Isi repositori
- `tugas_UTS.ipynb`: notebook jawaban yang sudah dijalankan dan berisi output/grafik.
- `Ads_Data.csv`: dataset regresi linear.
- `Email_Data.csv`: dataset klasifikasi spam.
- `README.md`: identitas dan ringkasan hasil.

## Ringkasan hasil pada pembagian data ini
- Linear Regression: persamaan `ŷ = 29.5113 + 8.9558 × BiayaIklan`.
- Linear Regression testing: MAE ≈ 4.7986; MSE ≈ 39.2230; RMSE ≈ 6.2628; R² ≈ 0.9425.
- Logistic Regression testing pada threshold 0.5: confusion matrix `[[6, 0], [0, 9]]`; accuracy, precision, recall, dan F1-score masing-masing 1.00.
- Gradient Descent Linear Regression: learning rate 0.02 mendekati Normal Equation; 0.001 lebih lambat; 0.1 divergen pada data ini.

## Cara menjalankan
1. Pastikan Python, Jupyter Notebook, NumPy, pandas, dan Matplotlib tersedia.
2. Simpan ketiga file utama (`tugas_UTS.ipynb`, `Ads_Data.csv`, `Email_Data.csv`) di folder yang sama.
3. Buka notebook lalu pilih **Run All**.
4. scikit-learn hanya dipakai pada bagian bonus.


