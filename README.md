
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
│   ├── dash.py
│   └── Day_analisis.csv
├── data
│   ├── day.csv
|   └── hour.csv
├── screenshots
|   ├── Screenshots (821).png
|   ├── Screenshots (826).png
|   ├── Screenshots (839).png
|   ├── Screenshots (845).png
|   ├── Screenshots (901).png
|   ├── Screenshots (921).png
|   ├── Screenshots (912).png
|   ├── Screenshots (851).png
|   └── Screenshots (926).png
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
2. Install streamlit di cmd denfan `pip install streamlit`. Install library lain seperti pandas, numpy, scipy, matplotlib, and seaborn
3. jangan ubah file csv. tetapkan dalam folder yang sama dengan dashboard.py
4. buka pycharm dan jalankan `streamlit run dash.py` pada terminal

## 4. Screenshots

![Screenshot 2024-10-04 180821](https://github.com/user-attachments/assets/dd5bf9e8-64d6-4e65-8110-1d8e0918ab9c)
![Screenshot 2024-10-04 180826](https://github.com/user-attachments/assets/c9ae325a-db80-4e0b-baee-e5ed75961a43)
![Screenshot 2024-10-04 180839](https://github.com/user-attachments/assets/72bab38d-5684-4ced-ac10-50bc73521f04)
![Screenshot 2024-10-04 180845](https://github.com/user-attachments/assets/0bb1b9f5-4a59-420d-b9b1-ea2643480f2d)
![Screenshot 2024-10-04 180901](https://github.com/user-attachments/assets/f752197e-ccfc-45ff-8f81-04b79181a5fa)
![Screenshot 2024-10-04 180921](https://github.com/user-attachments/assets/e3691dfc-2e7c-43a9-ae3f-165a0d5c7e22)
![Screenshot 2024-10-04 180912](https://github.com/user-attachments/assets/3be244c2-93ca-47a7-a198-6dfe9c75e9c4)
![Screenshot 2024-10-04 180851](https://github.com/user-attachments/assets/87e0c158-dad2-4635-977e-abd08dea27fa)
![Screenshot 2024-10-04 180926](https://github.com/user-attachments/assets/640cbb08-7424-4e00-8e3f-60b5d75cc195)





