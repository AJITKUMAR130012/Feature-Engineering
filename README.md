# Feature-Engineering
In this repository, We will be learning about "Feature Engineering". It is part of the machine learning.

**Feature Engineering:** Feature engineering is the process of using domain knowledge to extract features from the raw data. Thease feature can be used to                          improve the performance of machine learning algorithm. Here we will be learning, How to make good dataset for the machine learning                          algorithm.

"BAD MACHINE LEARNING ALGORITHM PERFORMS GOOD ON GOOD DATASET"
                                    
There is four part of the feature engineering:
1. Feature Transformation
2. Feature Construction
3. Feature Selection
4. Feature Extraction

**Feature Transformation:** Feature transformation is mainly responsible for the "Feature Scaling", "Outlier Detection", "Handeling Categorical Feature", and "Missing value imputation".

**Feature Scaling:** It is the step that perform before giving input data to machine learning model. It is last step of the feature engineering. It is a technique to standardise the independent features present in the data in a fixed range. It makes all the dataset column value to one scale.
a.Standardization(Z-score Normalization)
b.Normalization

**Standardization(Z-score Normalization):** 
**Xi=(Xi-Xmean)/standard deviation**

After Standardization:

mean=0 and standard deviation=1

![Screenshot from 2022-12-31 08-30-40](https://user-images.githubusercontent.com/60688738/210122967-f4b64b67-ade8-48f5-82a2-ad2354edf865.png)

Standarization only change the scale of data, It doen't effect the shape of the data.

![Screenshot from 2022-12-31 08-34-31](https://user-images.githubusercontent.com/60688738/210123033-c19037cc-4c88-4d3b-9cfa-e95a92a1bc3b.png)

Doesn't effect on outlier only scale of data is changed. In the below diagram, one outlier goes into the test set after splitting of the data.

![Screenshot from 2022-12-31 08-38-01](https://user-images.githubusercontent.com/60688738/210123126-184cbb18-18df-4c2c-9bad-b36eb1406a33.png)

When to use Standarization:

1. It should be use K-mean algorithm.
2. It should be use before applying the K-nearest neighbour.
3. It should be use before applying the priniciple component analysis(PCA).
4. It should be use before applying Artificial Nueral Network.
5. It should be use before applying the Gradient Decent.


**Normalization:** Normalization is technique often apply as part of the data preparation for machine learning. The goal of machine learning 
                   normalization is to change the value of numeric columns in the dataset to use a common scale, without distorting differences
                   in the ranges of value or loosing information.
                   
1. Min-Max scaling
2. Mean Normalization
3. Max Absolute
4. Robust Scaling









