# Capital Bikeshare: Bikesharing Analysis and Dashboard

## 📝 Analysis with Jupyter Notebook

🚧 Untuk melihat detail dan visualisasi, silahkan kunjungi [notebook](https://github.com/HilmaRohman/dicoding-data/blob/main/proyek_analisis_data.ipynb) 🚧


🚧 Untuk melihat dashboard streamlit silahkan kunjungi: https://dicoding-hilma-data.streamlit.app/ 🚧

Dashboard ini akan menunjukkan data pengguna yang teregistrasi maupun casual. Selain itu, ditampilkan grafik mengenai sebaran pengguna pada tiap-tiap musim. Tidak hanya itu, karena akan dilanjutkan dengan grafik scatter plot yang akan memvisualkan jumlah pelanggan saat liburan berdasarkan suhu.

### Run Streamlit on Local

### Setup Environment - Anaconda
```
conda create --name main-ds python=3.9
conda activate main-ds
pip install -r requirements.txt
```

### Setup Environment - Shell/Terminal
```
mkdir proyek_analisis_data
cd proyek_analisis_data
pipenv install
pipenv shell
pip install -r requirements.txt
```

```bash
pip install -r requirements.txt
```

#### Run Dashboard
```bash
cd dashboard
streamlit run dashboard.py
```
