
# House Price Prediction 

This data science project walks through step by step process of how to build a real estate price prediction website. 
1. I have built a model using sklearn and linear regression using banglore home prices dataset from kaggle.com. 
2. Step would be to write a python flask server that uses the saved model to serve http requests. 
3. This component is the website built in html,css and javascript that allows user to enter home square ft area, bedrooms etc and it will call python flask server to retrieve the predicted price. 
4. During model building we will cover almost all data science concepts such as data load and cleaning, outlier detection and removal, feature engineering, dimensionality reduction, gridsearchcv for hyperparameter tunning, k fold cross validation etc.

# Notebook

Refer to the "model/House_pp.ipynb" folder for model creation.
Refer to the "server/deployment and server/util" for flask.

# Testing

You can use porstman for testing your app.
## Installation

Install credentials with requirements.txt

```bash
  pip install -r requirements.txt
```
    
## Screenshots

![home](https://user-images.githubusercontent.com/66559862/140810161-4cb32fe5-1b2d-4663-a63d-40ecab8189ac.JPG) 
![aboutus](https://user-images.githubusercontent.com/66559862/140810152-f89920bd-c15b-4c16-9fdd-93fc94a7cc7d.JPG)
![estimate](https://user-images.githubusercontent.com/66559862/140810158-af746580-8d3c-43a8-a14b-d84e501d99d5.JPG)
![evaluation](https://user-images.githubusercontent.com/66559862/140810160-18ba97a8-b46c-436a-92f4-836975163f52.JPG)

The Predict app is the "Estimate page"

