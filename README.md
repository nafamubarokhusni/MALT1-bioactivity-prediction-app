![Logo](logo.png)

# bioactivity-prediction-app

## Daftar Anggota
1. Nama: Husni Na'fa Mubarok, NIM: 121450078
2. Nama: Meliza Wulandari, NIM: 121450065
3. Nama: Yosia Gilbert Wuaten, NIM: 118140174
4. Nama: Dwi Nur Saleh, NIM: 120410090
5. Nama: Nazwa Nabilla, NIM: 121450122

# Referensi

[Bioinformatics Project from Scratch - Drug Discovery #6 (Deploy Model as Web App) | Streamlit #22](https://youtu.be/htBIP17S-20)

# Reproducing this web app
To recreate this web app on your own computer, do the following.

### Create conda environment
Firstly, we will create a conda environment called *bioactivity*
```
conda create -n bioactivity python=3.7.9
```
Secondly, we will login to the *bioactivity* environement
```
conda activate bioactivity
```
### Install prerequisite libraries

Download requirements.txt file

```
wget https://raw.githubusercontent.com/nafamubarokhusni/MALT1-bioactivity-prediction-app/main/requirements.txt

```

Pip install libraries
```
pip install -r requirements.txt
```

###  Download and unzip contents from GitHub repo

Download and unzip contents from https://github.com/nafamubarokhusni/MALT1-bioactivity-prediction-app/archive/main.zip

### Generating the PKL file

The machine learning model used in this web app will firstly have to be generated by successfully running the included Jupyter notebook [bioactivity_prediction_app.ipynb](https://github.com/nafamubarokhusni/MALT1-bioactivity-prediction-app/blob/master/bioactivity_prediction_app.ipynb). Upon successfully running all code cells, a pickled model called acetylcholinesterase_model.pkl will be generated.

###  Launch the app

```
streamlit run app.py
```
