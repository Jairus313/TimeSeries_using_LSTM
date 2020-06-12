# Time Series for Univariate Dataset using RNN with LSTM

Here I have implemented RNN with LSTM for Univariate Time Series dataset from one of the kaggle's competition:

https://www.kaggle.com/c/predice-el-futuro/overview

### **Problem Discription:**

Data consist of two files:

- **train_csv.csv**: The training dataset consists of 80 observation with observation id, timestamp and feature value.

- **test_csv.csv**: The next 40 observation along with observation id and timestamp are present here. You'll have to predict the value of feature at these timestamps.

- **value to predict**: The value of feature attribute has to be predicted.

#### File Description:

- **train_csv.csv** - the training set

- **test_csv.csv** - the test set

---

 ####  Here I have implemeted RNN with LSTM with loss value lesser than 0.03 while training and RMSE value 122.90 on validation split.
