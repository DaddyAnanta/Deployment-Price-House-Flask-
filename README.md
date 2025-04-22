# Deployment Prediksi Harga Rumah dengan Flask 🏠

Selamat datang di proyek deployment model prediksi harga rumah menggunakan framework Flask! Proyek ini memungkinkan pengguna memasukkan fitur-fitur rumah dan mendapatkan prediksi harga berdasarkan model Machine Learning yang telah dilatih.

## Teknologi & Library yang Digunakan

[![Python](https://img.shields.io/badge/Python-3.9+-blue)](https://www.python.org/) [![Flask](https://img.shields.io/badge/Flask-3.0.3-black)](https://flask.palletsprojects.com/) [![Pandas](https://img.shields.io/badge/Pandas-1.5.3-lightgrey)](https://pandas.pydata.org/) [![NumPy](https://img.shields.io/badge/NumPy-1.26.4-blueviolet)](https://numpy.org/) [![Scikit--learn](https://img.shields.io/badge/Scikit_learn-1.3.0-orange)](https://scikit-learn.org/) [![XGBoost](https://img.shields.io/badge/XGBoost-2.0.3-darkgreen)](https://xgboost.ai/) [![Gunicorn](https://img.shields.io/badge/Gunicorn-22.0.0-green)](https://gunicorn.org/) [![Joblib](https://img.shields.io/badge/Joblib-1.4.2-grey)](https://joblib.readthedocs.io/)

*(Catatan: Badge di atas menampilkan library utama yang digunakan. Dependensi lain seperti Werkzeug, Jinja2, dll., otomatis terinstal bersama Flask atau library lainnya).*

## Cara Menjalankan Proyek

1.  **Clone Repository (jika ada)**
    ```bash
    git clone [URL_REPOSITORY_ANDA]
    cd [NAMA_FOLDER_REPO]
    ```

2.  **Buat Virtual Environment (Opsional tapi disarankan)**
    ```bash
    python -m venv venv
    # Aktivasi di Windows
    .\venv\Scripts\activate
    # Aktivasi di macOS/Linux
    source venv/bin/activate
    ```

3.  **Install Dependensi** ⚙️
    Sebelum mencoba kode di atas, Anda harus menginstall dependensi terlebih dahulu dengan perintah berikut di terminal:
    ```bash
    pip install -r requirements.txt
    ```

4.  **Jalankan Aplikasi Flask** ▶️
    Untuk menjalankan programnya, masukkan perintah ini di terminal:
    ```bash
    python app.py
    ```
    Aplikasi akan berjalan secara default di `http://127.0.0.1:5000` atau alamat lain yang mungkin muncul di terminal Anda. Buka alamat tersebut di browser Anda.

## Tampilan Website 🖼️

Tampilan dari website prediksinya seperti di bawah ini:

**Halaman Input:**
![Tampilan Input Prediksi Harga Rumah](https://github.com/user-attachments/assets/2d57a307-2cb7-4d09-85de-8cf06dc62cb6)
*Pengguna memasukkan data fitur rumah di sini.*

**Contoh Pengisian:**
![Contoh Input Fitur](https://github.com/user-attachments/assets/bdca1c00-3c2c-47c2-a507-36f306c3ec6e)
*Contoh pengisian form dengan data fitur rumah.*

**Halaman Hasil Prediksi:**
![Hasil Prediksi Harga Rumah](https://github.com/user-attachments/assets/fda22914-cf62-4db4-bf89-76fa9cfd69f1)
*Hasil prediksi harga rumah ditampilkan setelah submit.*
