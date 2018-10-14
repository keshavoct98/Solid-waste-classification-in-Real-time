# Solid-waste-classification-in-Real-time
Download dataset from [here_](https://github.com/garythung/trashnet/blob/master/data/dataset-resized.zip?raw=true)

1. Image_to_hist.ipynb -  Image augmentation using 'skimage' library. Rotating images and adding noise and Calculating histograms of final Image dataset produced. Storing calculated histograms data in a dataframe, adding labels and saving final dataframe in 'hist.csv'.

2. Classifier.ipynb - XGBoost parameter tuning on hist.csv data and saving trained model for future predictions.

3. RealTimePredictions.ipynb - Classifying solid wastes into one of the five categories in real time![.](https://github.com/keshavoct98/Solid-waste-classification-in-Real-time/blob/master/clc.gif)
