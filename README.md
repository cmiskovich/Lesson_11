# Lesson_11
# Primary application file

Produce a Google colab file analyzing the company's financial and user data in clever ways to make the company grow. So, you want to find out if the ability to predict search traffic can translate into the ability to successfully trade the stock.


---

## Technologies

The following Technologies were used to develop this program:

Python 
    Version 3.9.7

Terminal
    Version 2.12.5 (444)

Visual Studio Code
    Version: 1.66.2 (Universal)
    Commit: dfd34e8260c270da74b5c2d86d61aee4b6d56977
    Date: 2022-04-11T07:49:20.994Z
    Electron: 17.2.0
    Chromium: 98.0.4758.109
    Node.js: 16.13.0
    V8: 9.8.177.11-electron.0
    OS: Darwin x64 21.4.0
    
Jupyter Lab 
    Version 3.2.9
    
Google.colab

---

## General information about analysis.

First you need to  import the data (provided in the starter code) and prepare the data (provided in the starter code). After that you need to find the Best Value for k Using the Original Data.  Then you cluster cryptocurrencies with K-means Using the Original Data and optimize clusters with Principal Component Analysis.

Then you will find the Best Value for k Using the PCA Data and cluster the cryptocurrencies with K-means using the PCA Data. Finally you visualize and compare the results.

When comparing the results on the elbow curve, I still came up with 4 as the components to use but after optimizing the data using Principal Component Analysis the amount reduced significantly from 79.022 inertia to 49.665 inertia.  

Also, comparing the scatter plots you notice that the grouping was much better compared to data without Principal Component Analysis applied to the data.






---

## Information about datasets

Data frame for crypto market data:

df_market_data

Data set using StandardScaler to normalize data:

scaled_data

Create a data frame with Scaled Data:

df_market_data_scaled

Create a data frame for the elbow curve plot:

k, inertia, elbow data, df_elbow, df_elbow_plot

Initalize K-Means and fit scaled data:

model

Predict clusters to group the cryptocurrencies:

k_4

Create data frame to display the results of the predictions:

df_market_data_predictions

Plot the data frame to visualize the results of predictions:

df_market_data_predictions_plot

Create a PCA data frame to reduce to three components:

pca, market_pca_data, market_pca_df

Create a data frame for the elbow curve plot for PCA data:

k, inertia, elbow data_1, df_elbow_1, df_elbow_1_plot

Initalize K-Means and fit scaled data for PCA data:

model

Predict clusters to group the cryptocurrencies for PCA data:

k_4a

Create data frame to display the results of the predictions for PCA data:

market_pca_predictions_df

Plot the data frame to visualize the results of predictions for PCA data:

market_pca_predictions_df




---

## Libraries used in analysis

pandas

hvplot

Path

KMeans

PCA

StandardScaler

---

## Contributors


**Chris Miskovich**

Contact Information:

Email: cmiskovich@verizon.net

[LinkedIn](https://www.linkedin.com/in/christopher-miskovich-9a61b0234/) 

---

## License

[MIT](/license.txt)
