# M.Sc. Data Science Final Thesis of Firoj Ahmmed Patwary
## ETA Prediction
This is the repository of my Data Science master's degree thesis at Freie Universität Berlin

### Folder Description
- **Data Preprocessing:** Contains all the notebook to preprocess the data for models implementation.
- **Data:** This folder contains the final data that have used in this thesis. 
- **Exploratory Data Analysis:** This folder contains all notebooks for the EDA before and after outlier detection in all features of the final dataset.
- **Feature Matrices:** Contains all feature matrices for the final data and sub dataset.
- **Figures:** Contains all visualization plot, figures of the thesis.
- **Lock Data Integration:** Contains the notebook for the river lock data integration with the main data.
- **Models:** Contains MLP, BiLSTM, GRU, and 1D-CNN models notebooks and hyperparameter tuning.
- **Trip Generator:** Notebook for the successfull trip generator from one POI to the next consecutive POI.

### Prediction Performance of All Models to the Test Dataset

| **Model** | **MAE (All)** | **MSE (All)** | **MAE (AIS)** | **MSE (AIS)** | **MAE (AIS & Weather)** | **MSE (AIS & Weather)** | **MAE (AIS, Lock & Weather)** | **MSE (AIS, Lock & Weather)** |
|:----------|--------------:|--------------:|--------------:|--------------:|------------------------:|------------------------:|-----------------------------:|------------------------------:|
| **MLP**   |        159.21  |      70682.30 |      198.81   |      97982.30 |       174.77            |      78189.60           |      172.28                   |       76835.76                 |
| **BiLSTM**|         62.04  |      15544.70 |      156.26   |      72359.01 |        95.80            |      30941.30           |       81.12                   |       22487.25                 |
| **GRU**   |         82.90  |      24592.00 |      158.42   |      73186.94 |        93.03            |      29953.55           |       91.35                   |       28799.90                 |
| **1D-CNN**|        108.40  |      33597.39 |      171.85   |      79980.45 |       129.61            |      43108.33           |      123.93                   |       41250.50                 |

*Note: MAE in minutes and MSE in minutes².*
