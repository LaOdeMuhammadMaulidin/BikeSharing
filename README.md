
# Bike Rentals - Final Project Data Analytics

Ini Merupakan projek akhir dari course analisis data dengan python untuk analisis data dan membuar dashboard interaktif menggunakan streamlit, disini dataseet bike dengan penjelasan
instant: record index
dteday : date
season : season (1:springer, 2:summer, 3:fall, 4:winter)
yr : year (0: 2011, 1:2012)
mnth : month ( 1 to 12)
hr : hour (0 to 23)
holiday : weather day is holiday or not (extracted from [Web Link])
weekday : day of the week
workingday : if day is neither weekend nor holiday is 1, otherwise is 0.
weathersit :
1: Clear, Few clouds, Partly cloudy, Partly cloudy
2: Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist
3: Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds
4: Heavy Rain + Ice Pallets + Thunderstorm + Mist, Snow + Fog
temp : Normalized temperature in Celsius. The values are derived via (t-t_min)/(t_max-t_min), t_min=-8, t_max=+39 (only in hourly scale)
atemp: Normalized feeling temperature in Celsius. The values are derived via (t-t_min)/(t_max-t_min), t_min=-16, t_max=+50 (only in hourly scale)
hum: Normalized humidity. The values are divided to 100 (max)
windspeed: Normalized wind speed. The values are divided to 67 (max)
casual: count of casual users
registered: count of registered users
cnt: count of total rental bikes including both casual and registered

## 1. File Structures
```
.
├── dashboard
│   ├── main.py
│   └── Day_analisis.csv
├── data
│   ├── day.csv
|   └── hour.csv
├── screenshots
|   ├── Screenshots (050).png
|   ├── Screenshots (058).png
|   ├── Screenshots (106).png
|   └── Screenshots (115).png
├── README.md
├── Proyek_Analisis_Data.ipynb
└── requirement.txt
```

## 2. Project work cycle
1. Data Wrangling: 
 - Mengumpulkan data
 - Menilai data
 - membersihkan data
2. Exploratory Data Analysis:
 - Defenisikan pertanyaan bisnis
 - Buat Explorasi Data
3. Data Visualization:
 - Buat visualisasi data untuk menjawab pertanyaan bisnis
4. Dashboard:
 - Meng-set dataframe yang diguankan
 - membuat komponen filter
 - Lengkapi dashboard dengan visualisasi

**Note: Numbers 1 to 3 are in the dicoding-collection-exercise and number 4 is in dashboard.**

## 3. Getting Started
### `notebook.ipynb`
1. Donwload Project ini.
2. Buka notebook favorite anda (disini saya pakai Google Colab).
3. Buat notebook baru.
4. Upload dan pilih file dengan extensi ipynb.
5. hubungkan ke host runtime.
6. terakhir,jalankan cell kode.

### `dashboard/dashboard.py`
1. Download project ini .
2. Install streamlit di cmd dengan `pip install streamlit`. Install library lain seperti pandas, numpy,streamlit, matplotlib, and seaborn
3. jangan ubah file csv. tetapkan dalam folder yang sama dengan dashboard.py
4. buka pycharm dan jalankan `streamlit run main.py` pada terminal

## 4. Screenshots

![Screenshot 2024-10-07 073050](https://github.com/user-attachments/assets/b299c783-6a24-406b-9267-949b93dba21a)
![Screenshot 2024-10-07 073058](https://github.com/user-attachments/assets/1cfeac21-14bc-4575-bbbb-fceb2496d8d2)
![Screenshot 2024-10-07 073106](https://github.com/user-attachments/assets/0086c100-d1a9-4c3d-b789-e58fddeb5183)
![Screenshot 2024-10-07 073115](https://github.com/user-attachments/assets/dd4e92b7-efc0-436d-8785-f1fffcda8e63)







