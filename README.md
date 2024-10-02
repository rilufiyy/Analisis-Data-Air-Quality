# Analisis-Data-Air-Quality
Author: Sri Lutfiya Dwiyeni
Email: srilutfiyadwiy@gmail.com
ID Dicoding: sri_lutfiya_dwiyeni

# Proyek Analisis Data: Air Quality Dataset

Proyek ini adalah dashboard interaktif yang dikembangkan menggunakan **Streamlit** untuk menganalisis timeseries Air Quality Dataset. Dashboard ini mempermudah eksplorasi dan visualisasi data, yang mendukung pengambilan keputusan berbasis data dengan lebih efektif. 

### Pertanyaan Bisnis
- Bagaimana nilai temperature pada waktu jam, harian, bulanan, tahun, musim?
- Bagaimana nilai DEWP pada waktu jam, harian, bulanan, tahun, musim?
- Bagaimana nilai Pressure pada waktu jam, harian, bulanan, tahun, musim?

### Details of the Columns:

- Year: the data's (integer) year, which is regarded as categorical
- Month: The data's (integer) month, regarded as categorical
- Day: the data's (integer) day, which is regarded as categorical
- Hour: the data's (integer) hour, which is regarded as categorical
- PM2.5: (integer) The area's hourly PM2.5 concentration. It is continuous and measured in (ug/m³).
- PM10: (integer) The area's hourly PM2.5 concentration. It is continuous and measured in (ug/m³).
- SO2: (integer) The area's hourly PM2.5 concentration. It is continuous and measured in (ug/m³).
- NO2: (integer) The area's hourly PM2.5 concentration. It is continuous and measured in (ug/m³).
- CO-:(integer) Pm2.5 concentration in the area each hour. It is continuous and measured in (ug/m³).
- O3: (integer) Pm2.5 concentration per hour in the vicinity. It is continuous and measured in (ug/m³).
- PRES: (integer) The local air pressure. Pascal-measured and regarded as continuous
- DEWP: degree point temperature (integer) regarded as continuous
- RAIN: (integer) The amount of precipitation in the region deemed continuous
- WD: (string) The direction of the wind there, which is regarded as categorical.
- Wind speed, or WASPM (). It is continuous and has a measurement of (m/s).
- Station(string): The site's name for monitoring air quality. Twelve monitoring locations in Beijing make up the data, which is regarded as categorical.

## Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/yourusername/bike-sharing-analysis.git
    ```

2. **Navigate to the project directory**:
    ```bash
    cd bike-sharing-analysis
    ```

3. **Create a virtual environment**:
    ```bash
    virtualenv venv
    ```

4. **Activate the virtual environment**:
   - On Windows:
     ```bash
     .\venv\Scripts\activate
     ```
   - On Mac/Linux:
     ```bash
     source venv/bin/activate
     ```

5. **Install the dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

6. **Run the Streamlit app**:
    ```bash
    streamlit run app.py
    ```

## Fitur Utama
1. **Visualisasi
- *heatmap* untuk menampilkan intensitas nilai dalam bentuk warna yang menunjukkan perbedaan nilai dari data pada suatu periode waktu dan kategori (temp, DEWP, PRESS).
- *Bar Chart* untuk memvisualisasikan distribusi data atau agregasi berdasarkan kategori waktu (misalnya, hari, bulan, atau tahun). Ini adalah metode yang baik untuk membandingkan data antar grup atau kategori yang berbeda.
- *Box Plot* digunakan untuk menunjukkan distribusi data, termasuk median, kuartil, dan pencilan. Ini sangat berguna untuk melihat variabilitas atau dispersi data dan mengidentifikasi outlier dalam dataset.
- *Line Chart* untuk memudahkan dalam melihat tren TEMP, DEWP, dan PRESS pada dataset air quality secara berkelanjutan dari waktu ke waktu.
- **Analisis Distribusi Variabel Temperatur, DEWP, dan Pressure**: *Histogram* untuk melihat distribusi di berbagai daerah yang ada di Beijing.

## Dependencies

- Python 3.10
- pandas
- seaborn
- matplotlib
- numpy
- streamlit
- plotly
