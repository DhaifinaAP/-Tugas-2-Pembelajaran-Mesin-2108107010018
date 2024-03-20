# Tugas-2-Pembelajaran-Mesin-2108107010018
Repository ini dibuat guna memenuhi tugas 2 Mata Kuliah Pembelajaran Mesin

Code yang diupload melakukan proses Klasifikasi dan Regresi dataset "Breast Cancer Data Set" dengan menggunakan model SVM (Support Vector Machine). 
Link Dataset : https://www.kaggle.com/datasets/erdemtaha/cancer-data

Dataset ini berisi karakteristik pasien yang terdiagnosis kanker. Dataset berisi ID unik untuk setiap pasien, jenis kanker (diagnosis), karakteristik visual kanker, dan nilai rata-rata karakteristik tersebut.

Fitur utama dari dataset adalah sebagai berikut:
1. **id**: ID unik untuk setiap pasien.
2. **Diagnosa**: Jenis kanker yang didiagnosis pada pasien (M untuk Malignant atau ganas, dan B untuk Benign atau jinak).
3. **radius_mean**: Nilai rata-rata dari radius kanker.
4. **texture_mean**: Nilai rata-rata dari tekstur kanker.
5. **perimeter_mean**: Nilai rata-rata dari perimeter kanker.
6. **area_mean**: Nilai rata-rata dari area kanker.
7. **smoothness_mean**: Nilai rata-rata dari kehalusan kanker.
8. **compactness_mean**: Nilai rata-rata dari kekompakan kanker.
9. **concavity_mean**: Nilai rata-rata dari cekungan kanker.
10. **concave points_mean**: Nilai rata-rata dari titik cekung kanker.

ada 22 fitur lain yang memiliki nilai karakteristik, jika karakteristik yang menjadi fitur utama berupa nilai rata - rata, fitur yang lain berupa nilai standard error dan worst(terburuk).

Fitur-fitur ini memberikan informasi penting tentang karakteristik visual kanker, yang sangat berguna untuk analisis dan prediksi.

# How to run: 

-git clone https://github.com/DhaifinaAP/Tugas-2-Pembelajaran-Mesin-2108107010018.git

-python3 -m venv env

-source env/bin/activate

-python3 pip install -r requirements.txt

-run code Klasifikasi.ipynb dan Regresi.ipynb 
