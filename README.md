# Kaggle_houseprice_prediction
My codes in Kaggle houseprice prediction competition


**Key important change**: from rmse 3.5+ down to rmse 1.5+
 
In Kaggle, test.csv don't have labels, so train.csv can be split into train-val dataset. So when encoding and scaling, we should fit_transform(train_data), transform(val_data), transform (test_data)
