# Cryptocurrencies

### Purpose
#### Our client as that we create a report that includes what cryptocurrencies are on the trading market and how they could be grouped to create a classification system for this new investment. 
#### For this we are going to:
* Preprocess the Data for PCA
* Reduce Data Dimensions Using PCA
* Cluster Cryptocurrencies using K-Means
* Visualize Cryptocurrencies Results 

### Results 
#### Imported data, this is the initial DataFrame created showing that we have 1,252 rows of data as shown on the bottom of the image below

![Image_1](https://github.com/walzfran/Cryptocurrencies/blob/main/Images/origial_data.png)

#### After the data is cleaned we only have 532 rows of data to work with

![Image_2](https://github.com/walzfran/Cryptocurrencies/blob/main/Images/cleaned_data.png)

#### The first Image that was generated was an Elbow Curve depicting the inertia and k values 

![Image_3](https://github.com/walzfran/Cryptocurrencies/blob/main/Images/Elbow_Curve.png)

#### I also merged different DataFrames to create a seperate DataFrame showing the Principal Component Analysis 

![Image_4](https://github.com/walzfran/Cryptocurrencies/blob/main/Images/pca_added.png)

#### I created a 3D Scatterplot with clusters which shows the tradable cryptocurrencies 

![Image_5](https://github.com/walzfran/Cryptocurrencies/blob/main/Images/3d.png)

#### Below is the print statement created to show the amount of tradable cryptocurrencies 

![Image_6](https://github.com/walzfran/Cryptocurrencies/blob/main/Images/tradable.png)

#### A final DataFrame with scaled data 

![Image_7](https://github.com/walzfran/Cryptocurrencies/blob/main/Images/Scaled_Data.png)

#### The last visualization made was a scatter plot showing the tradable cryptocurrencies

![Image_8](https://github.com/walzfran/Cryptocurrencies/blob/main/Images/Scatter.png)
