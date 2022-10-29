# AirQualityForecastingAI60002
Term Paper for ML for Earth System Sciences course of Spring Sem 2022 at IIT Kgp

Group members:
- Abhranil Chandra (19ME30051)
- Manav Nitin Kapadnis (19EE30013)
- Kolla Ananta Raj (19EE30012)
- Parth Mane (19IE10020)
- Akshat Patidar (18MA20004)
- Amit Anand (18CE36002)

## Code Repository Organisation
```bash
├── dataset/
|    ├── Gucheng
|    ├── Nongzhanguan
|    └── Wanshouxigong
├── Forecast Images/
|    ├── Gucheng
|    ├── Nongzhanguan
|    └── Wanshouxigong
├── predictions/
|    ├── Gucheng
|    ├── Nongzhanguan
|    └── Wanshouxigong
├── PRSA_Data_20130301-20170228/
|    ├── PRSA_Data_Aotizhongxin_20130301-20170228.csv
|    ├── PRSA_Data_20130301-20170228/PRSA_Data_Changping_20130301-20170228.csv
|    └── PRSA_Data_20130301-20170228/PRSA_Data_Dingling_20130301-20170228.csv
|    └── PRSA_Data_20130301-20170228/PRSA_Data_Dongsi_20130301-20170228.csv
|    └── PRSA_Data_20130301-20170228/PRSA_Data_Guanyuan_20130301-20170228.csv
|    └── PRSA_Data_20130301-20170228/PRSA_Data_Huairou_20130301-20170228.csv
|    └── PRSA_Data_20130301-20170228/PRSA_Data_Shunyi_20130301-20170228.csv
|    └── PRSA_Data_20130301-20170228/PRSA_Data_Tiantan_20130301-20170228.csv
|    └── PRSA_Data_20130301-20170228/PRSA_Data_Wanliu_20130301-20170228.csv
├── result/
|    ├── Gucheng_prophet.csv
|    ├── Nongzhanguan_prophet.csv
|    └── Wanshouxigong_prophet.csv
├── 1. Data Preprocessing.ipynb
├── 2. Exploratory Data Analysis.ipynb
├── 3. Time series with LSTM.ipynb.ipynb
├── 4. Time series with RNN.ipynb
├── 5. Time series with Prophetnet.ipynb.ipynb
├── Results Sheet.xlsx
├── README.md
```

## Obtaining the code and data

First, clone this repository
```
https://github.com/abhraIITKgp/AirQualityForecastingAI60002.git

```

All the code and Data will get downloaded by the above command.
In order to reproduce our results,
- Open any choice of architechture LSTM/RNN/ProphetNet and corresponding the IPython Notebook present in the root 
- Just choose the city for which predictions are to be made , and change the file paths in the notebooks accordingly in the IPython Notebook and then do run all
- Provide correct path to the dataset and features.csv files for the language for which you are running the code
- The model will be saved after all the code cells get executed.
