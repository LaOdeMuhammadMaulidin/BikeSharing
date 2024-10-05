
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
|   ├── Screenshots (455).png
|   ├── Screenshots (504).png
|   ├── Screenshots (511).png
|   ├── Screenshots (528).png
|   ├── Screenshots (517).png
|   ├── Screenshots (540).png
|   ├── Screenshots (547).png
|   └── Screenshots (555).png
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

![Screenshot 2024-10-06 000455](https://github.com/user-attachments/assets/9a59a722-56f0-4637-b4d1-b39bcb9bc994)
![Screenshot 2024-10-06 000504](https://github.com/user-attachments/assets/0a0e998e-d274-4176-b80b-aaa9fd9a8498)
![Screenshot 2024-10-06 000511](https://github.com/user-attachments/assets/65c08d55-13d9-4bf3-9dac-eeced92bb66b)
![Screenshot 2024-10-06 000528](https://github.com/user-attachments/assets/9ead7a57-1d39-49ae-a6dc-a8a5b64f2fb5)
![Screenshot 2024-10-06 000517](https://github.com/user-attachments/assets/23892ef6-6081-4da9-b2c2-54276aafaed2)
![Screenshot 2024-10-06 000540](https://github.com/user-attachments/assets/7d8ce5ff-64fd-4a92-a741-f2a570687739)
![Screenshot 2024-10-06 000547](https://github.com/user-attachments/assets/f0576fc9-8dd1-41e3-a608-4b1025b141f4)
![Screenshot 2024-10-06 000555](https://github.com/user-attachments/assets/df5f3264-407b-49ed-b679-eecee9085219)







