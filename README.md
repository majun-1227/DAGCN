# DAGCN
## Datasets
>The ISRUC-Sleep dataset is available [here](https://sleeptight.isr.uc.pt).
## Requirements
## Preprocess
>Run ISRUC_S3_preprocess.py

```
python ISRUC_S3_preprocess.py
```

>This program will preprocess the ISRUC-S3 dataset and save a file named 'ISRUC_S3.npz'.
## Extract Features
>Run train_FeatureNet.py
```
python train_FeatureNet.py
```
>This program will extract features and save features to 'path_feature'.
## Train
>Run train_DAGCN_model.py

```
python train_DAGCN_model.py
```

>This program will train models and save to 'path_output'.

## Evaluate
>Run evaluate_DAGCN_model.py
```
python evaluate_DAGCN_model.p
```
>This program will evaluate models and save to 'path_output'.

