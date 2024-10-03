# PROJECT AKHIR DICODING - E-COMMERCES

Proyek ini merupakan bagian dari tugas akhir kursus "Belajar Analisis Data dengan Python" di Dicoding. Dalam proyek ini, saya melakukan analisis terhadap dataset transaksi e-commerce dan membangun dashboard interaktif menggunakan Streamlit. Proses yang saya lakukan mencakup pembersihan data, eksplorasi untuk mengidentifikasi pola, serta visualisasi data melalui grafik interaktif. 
## 1. File Struktur
   ```plaintext
├── Dashboard
│   ├── dashboard.py
│   └── df_all_data.csv
├── data
│   ├── orders.csv
│   ├── product_category_name_translation.csv
│   ├── product_dataset.csv
│   ├── sellers_dataset.csv
│   ├── geolocation_dataset.csv
│   ├── new_text_document.txt
│   ├── order_items_dataset.csv
│   ├── order_reviews_dataset.csv
│   └── customers_dataset.csv
├── screenshots
│   ├── Screenshots_1.png
│   ├── Screenshots_2.png
│   ├── Screenshots_3.png
│   └── Screenshots_4.png
├── README.md
└── notebook.ipynb
  ```

## 2. Langkah-langkah mengerjakan project

### 1. Data Wrangling:

- **Mengumpulkan Data**: Mengumpulkan data dari sumber yang tersedia, termasuk data transaksi harian dan bulanan.
- **Menilai Data**: Menilai kualitas data dengan melihat tipe data, missing values, dan duplikat.
- **Membersihkan Data**: Menghapus atau mengganti nilai yang hilang, duplikat, serta kolom yang tidak relevan.

### 2. Exploratory Data Analysis (EDA):

- **Menentukan Pertanyaan Bisnis**: Menyusun pertanyaan bisnis yang ingin dijawab, seperti tren penjualan berdasarkan waktu dan produk terlaris.
- **Eksplorasi Data**: Menganalisis data untuk melihat pola, tren, atau informasi penting yang bisa membantu memahami performa penjualan dengan lebih baik.

### 3. Visualisasi Data:

- Menampilkan grafik untuk menganalisis tren musiman, mengukur dampak kondisi cuaca terhadap tingkat penggunaan, serta membandingkan pola penggunaan antara pengguna kasual dan pengguna terdaftar.

### 4. Dashboard

- **Mengatur DataFrame yang Akan Digunakan?**: Menyiapkan data dari DataFrame yang sebelumnya dianalisis di Google Colab, termasuk hasil pembersihan dan eksplorasi, untuk diintegrasikan ke dalam dashboard.
- **Membuat Komponen Filter di Dashboard**: Menambahkan fitur filter seperti musim, kondisi cuaca, dan suhu guna mempermudah pengguna dalam melakukan eksplorasi data.
- **Menambahkan Visualisasi Data ke dalam Dashboard**: Melengkapi dashboard dengan berbagai visualisasi grafik untuk menjawab pertanyaan bisnis utama.
- Langkah 1 hingga 3 dilakukan sebagai bagian dari analisis data, sedangkan langkah 4 digunakan untuk membangun dashboard dengan Streamlit.

## 3. Langkah-langkah menjalankan project

## Notebook.ipynb

1. Download file projectnya.
2. Kemudian buka Google Colaboratory di website/Chrome.
3. Buat notebook baru di Google Colab.
4. Upload dan pilih file dengan format `.ipynb` yang telah didownload tadi.
5. Hubungkan ke runtime yang sudah di-hosting dengan mengklik "Connect".
6. Jalankan kode di notebook dengan menekan tombol "Run" pada setiap cell kode.

## Dashboard.py/main.py

1. Download file projectnya.
2. Install Streamlit di terminal dengan mengetikkan `pip install streamlit`.
3. Pastikan file CSV (dataset) disimpan dalam folder yang sama dengan file `dashboard.py` atau `main.py`.
4. Buka Visual Studio Code (VSCode), aktifkan virtual environment dengan mengetikkan perintah berikut di terminal:

 ```bash
 .\venv\Scripts\activate
 ```

  - Jika sudah masuk ke virtual environment, jalankan Streamlit dengan perintah:

```bash
streamlit run main.py
```

  - Jika menggunakan `dashboard.py`, ubah perintahnya menjadi:

   ```bash
   streamlit run dashboard.py
   ```

## 4. Screenshoot
![image](https://github.com/user-attachments/assets/6b1f9a6a-98ec-42b9-99bc-e4e284954743)

![image](https://github.com/user-attachments/assets/8fd366c5-73fb-4a44-b686-f97797683289)

![image](https://github.com/user-attachments/assets/b64eb10b-dbf3-4e73-a314-7e01c151f121)

![image](https://github.com/user-attachments/assets/0e6f9a89-43e8-4979-a565-1b8da6477d71)


