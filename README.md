# MeltpoolNet

This github repository contains the datasets and codes for our paper "MeltpoolNet: Melt pool Characteristic Prediction in Metal Additive Manufacturing Using Machine Learning" published in the jounal of Additive Manufacturing. 
# Dataset
Two dataset has been collected for the MeltpoolNet:
1. [Regression dataset for the meltpool geometry](https://github.com/BaratiLab/MeltpoolNet/blob/main/Data/meltpoolnet_regression.csv)
2. [Classification dataset for the meltpool modes and defects](https://github.com/BaratiLab/MeltpoolNet/blob/main/Data/meltpoolnet_classification.csv) 

# Prerequisites
The following modules and packages are required in order to run the associated code:
* numpy
* pandas
* sklearn
* XGBoost
* matplotlib
* scipy
* hyperopt

They can be installed independently, or all at once by running `pip install -r requirements.txt`. "requirements.txt" file can be found [here](https://github.com/BaratiLab/MeltpoolNet/blob/main/requirements.txt).


# Paper
Our paper can be found [here](https://www.sciencedirect.com/science/article/pii/S2214860422002172).

# Citation
If you use our data and notebook please cite: 

```
@article{AKBARI2022102817,
title = {MeltpoolNet: Melt pool characteristic prediction in Metal Additive Manufacturing using machine learning},
journal = {Additive Manufacturing},
volume = {55},
pages = {102817},
year = {2022},
issn = {2214-8604},
doi = {https://doi.org/10.1016/j.addma.2022.102817},
url = {https://www.sciencedirect.com/science/article/pii/S2214860422002172},
author = {Parand Akbari and Francis Ogoke and Ning-Yu Kao and Kazem Meidani and Chun-Yu Yeh and William Lee and Amir {Barati Farimani}}}
```

# Authors
Parand Akbari, Francis Ogoke, Ning-Yu Kao, Kazem Meidani, Chun-Yu Yeh, William Lee, Amir Barati Farimani
