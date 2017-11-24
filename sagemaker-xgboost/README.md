### Multiclass classification with single machine and distributed SageMaker XGBoost algorithm
This notebook `sagemaker-xgboost-distributed-multiclass-classification.ipynb` demos end-to-end training and scoring multi-classification model with single machine and distributed versions of Amazon SageMaker XGBoost. The dataset used is MNIST digit recognition dataset in `LIBSVM` format, which has a training set of 60,000 examples, and a test set of 10,000 examples. This notebook will walk the users through data preparation, IM training, IM hosting, and prediction.
 
### Regression with single machine SageMaker XGBoost algorithm
This notebook `sagemaker-xgboost-regression.ipynb` demos end-to-end training and scoring a regression model with single machine XGBoost. The dataset used is the [Abalone dataset](https://www.csie.ntu.edu.tw/~cjlin/libsvmtools/datasets/regression.html) in `LIBSVM` format. Age of abalone is to be predicted from eight physical measurements (numeric attributes). This notebook will walk the user through data preparation, IM training, IM hosting, and prediction.

### Bring Your Own Model (XGboost)
`sagemaker-xgboost-bring-your-own-model.ipynb` shows how to train and Xgboost model in scikit-learn and then inject it into Amazon SageMaker's first party XGboost container for scoring. This addresses the use case where a customer has already trained their model outside of Amazon SageMaker, but wishes to host it for predictions within Amazon SageMaker.