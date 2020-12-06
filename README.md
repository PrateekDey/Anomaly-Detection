# Anomaly-Detection
Firstly the Generation of the algorithm is done on the small dataset with specified number of outliers present in it. Represented below is a Scatter graph of the data values Xi which is Throughput(mb/s) vs Latency(ms).
![alt text](https://github.com/PrateekDey/Anomaly-Detection/blob/master/Outlier%20Plotting/Intial%20View%20of%20Dataset.png?raw=true)

Estimating the Parameter of the Gaussian curve from the Data values of Xi, i.e, mean and Standard deviation for plotting the Gaussian Curve. Represented below is a Visual Fit of the Gaussian Curve density over the data values estimating the highest density of the values.
![alt text](https://github.com/PrateekDey/Anomaly-Detection/blob/master/Outlier%20Plotting/Gaussian%20Distribution%20Contour%20to%20fit%20the%20Data%20Values.png?raw=true)

After this , estimating the threshold value for cross validation the data values. The probability of the data value is normal or an anomaly is detected and marked in red circle in the represented graphs below.

![alt text](https://github.com/PrateekDey/Anomaly-Detection/blob/master/Outlier%20Plotting/Detecting%20the%20Anomalies.png?raw=true)

Result, A total of 17 outliers are found from the small dimensional data set.
Now using the high dimensional dataset, estimating the parameters and selecting a threshold value for the cross validation is done.
Result , A total of 117 outliers are found in the high dimensional dataset.
