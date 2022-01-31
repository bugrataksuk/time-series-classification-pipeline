# Time Series Classification Pipeline 
- In this project,I am going to construct a pipeline which performs K-NN Classifier on 5 different time series data taken from http://www.timeseriesclassification.com/http://www.timeseriesclassification.com/.  The desired pipeline is expected to do Cross Validation on K value on train data and to decide paramaters of representations, to construct best model and then test it on the test data based on performance measures. After looking the data set briefly, I manipulated them in a similar way and let the pipeline show me the results of the different techniques based on accuracy measures.

## Models,Representations and Data Used 

### The data is provided by  http://www.timeseriesclassification.com/http://www.timeseriesclassification.com . The data sets chosen for the performance test are Earthquakes , ECG200, Fish , Large Kitchen Appliences and Mixed Shapes Small datasets

### The model used is KNN-Classifier : 

![image](https://user-images.githubusercontent.com/73999139/151790426-0e014435-9ca4-4e60-8bc0-ed1d9667d996.png)

### The representations and Distance Measures used : 

- *Dynamic Time Warping(DTW)* :
- 
https://en.wikipedia.org/wiki/Dynamic_time_warping

![image](https://user-images.githubusercontent.com/73999139/151788911-c83a6205-158c-4029-b8d9-042c78255d63.png)

- *Symoblic Aggregate Approximation(SAX)*:
- 
https://pyts.readthedocs.io/en/stable/auto_examples/approximation/plot_sax.html

![image](https://user-images.githubusercontent.com/73999139/151789208-00cf1934-9598-4d43-aa40-4f499da19843.png)

- *Principal Component Analysis(PCA)*:
- 
https://en.wikipedia.org/wiki/Principal_component_analysis

![image](https://user-images.githubusercontent.com/73999139/151789515-e0a00c77-613b-41cd-966e-8febfcd77f04.png)

## Files

- "Datasets" includes the train and test datasets to test the pipeline 
- time-series-classification-pipeline.jpynb is the interactive python notebook inculidng codes
- Requirements.txt is the all libraries you need for the analysis


## Libraries 
```
pandas
numpy
seaborn 
matplotlib
scipy
sklearn
dtaidistance
pyts
```

## Author 

https://github.com/bugrataksuk
