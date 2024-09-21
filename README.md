# Smartphone-Dataset-Analyze-And-Prediction
<h3>Data source: https://www.kaggle.com/datasets/informrohit1/smartphones-dataset</h3>
<h3>Kaggle notebook: https://www.kaggle.com/code/tnkhanghunh/smartphone-data-analyze</h3>

<h3 align="left">Languages and Tools in this project:</h3>

<p align="left"> 
        <a href="https://www.python.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/>   </a> 
        <a href="https://seaborn.pydata.org/" target="_blank" rel="noreferrer"> <img src="https://seaborn.pydata.org/_images/logo-mark-lightbg.svg" alt="seaborn" width="40" height="40"/> </a>
        <a href="https://pandas.pydata.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/2ae2a900d2f041da66e950e4d48052658d850630/icons/pandas/pandas-original.svg" alt="pandas" width="40" height="40"/> </a>
        <a href="https://matplotlib.org" target="_blank" rel="noreferrer"> <img src="https://avatars.githubusercontent.com/u/215947?s=200&v=4" alt="python" width="40" height="40"/>   </a> 
        <a href="https://plotly.com" target="_blank" rel="noreferrer"> <img src="https://avatars.githubusercontent.com/u/5997976?s=200&v=4" alt="python" width="40" height="40"/>   </a> 
        <a href="https://numpy.org" target="_blank" rel="noreferrer"> <img src="https://avatars.githubusercontent.com/u/288276?s=200&v=4" alt="python" width="40" height="40"/>   </a> 
        <a href="https://scikit-learn.org/" target="_blank" rel="noreferrer"> <img src="https://avatars.githubusercontent.com/u/365630?s=48&v=4" alt="python" width="40" height="40"/>   </a> 
        <a href="https://lightgbm.readthedocs.io/en/stable/" target="_blank" rel="noreferrer"> <img src="https://lightgbm.readthedocs.io/en/stable/_images/LightGBM_logo_black_text.svg" alt="python" width="40" height="40"/>   </a> 
        <a href="https://xgboost.readthedocs.io/en/stable/" target="_blank" rel="noreferrer"> <img src="https://www.intel.com/content/dam/www/central-libraries/us/en/images/2022-11/xgboost-logo-rwd.png.rendition.intel.web.480.360.png" alt="python" width="40" height="40"/>   </a> 
        <a href="https://optuna.org/" target="_blank" rel="noreferrer"> <img src="https://avatars.githubusercontent.com/u/57251745?s=48&v=4" alt="python" width="40" height="40"/>   </a> 
</p>
---

### Dataset Overview

This dataset includes information on 210 samples of smartphones with 26 different columns. Each row corresponds to a specific smartphone model from various brands. Below is a detailed explanation of each column:

- **brand_name:** Brand name of the phone (980 non-null values, data type: object).
- **model:** Phone model (980 non-null values, data type: object).
- **price:** Price of the phone (980 non-null values, data type: int64).
- **rating:** User rating for the phone (879 non-null values, data type: float64).
- **has_5g:** Whether the phone supports 5G network (980 non-null values, data type: bool).
- **has_nfc:** Whether the phone supports NFC (980 non-null values, data type: bool).
- **has_ir_blaster:** Whether the phone supports IR Blaster (980 non-null values, data type: bool).
- **processor_brand:** Brand of the processor (960 non-null values, data type: object).
- **num_cores:** Number of processor cores (974 non-null values, data type: float64).
- **processor_speed:** Processor speed (938 non-null values, data type: float64).
- **battery_capacity:** Battery capacity of the phone (969 non-null values, data type: float64).
- **fast_charging_available:** Whether fast charging is available for the phone (980 non-null values, data type: int64).
- **fast_charging:** Fast charging power (769 non-null values, data type: float64).
- **ram_capacity:** RAM capacity (980 non-null values, data type: float64).
- **internal_memory:** Internal memory capacity (980 non-null values, data type: float64).
- **screen_size:** Screen size (980 non-null values, data type: float64).
- **refresh_rate:** Screen refresh rate (980 non-null values, data type: int64).
- **num_rear_cameras:** Number of rear cameras (980 non-null values, data type: int64).
- **num_front_cameras:** Number of front cameras (976 non-null values, data type: float64).
- **os:** Operating system of the phone (966 non-null values, data type: object).
- **primary_camera_rear:** Resolution of the primary rear camera (980 non-null values, data type: float64).
- **primary_camera_front:** Resolution of the primary front camera (975 non-null values, data type: float64).
- **extended_memory_available:** Whether the phone supports expandable memory (980 non-null values, data type: int64).
- **extended_upto:** Maximum capacity of expandable memory (500 non-null values, data type: float64).
- **resolution_width:** Width resolution of the screen (980 non-null values, data type: int64).
- **resolution_height:** Height resolution of the screen (number of non-null values not specified).

---
