**Faculty Advisor - Dr. Babatunde Olubando**

Contact info: [babatunde.olubando@morgan.edu](mailto:babatunde.olubando@morgan.edu) / Slack

** \
Write your own K Nearest Neighbor Classifier to predict breast cancer**



1. Download the **wdbc.data** and **wdbc.names** files 
2. Read and store the contents of the  wdbc.data file.  The only fields (columns) that will be used in the classifier are radius and _smoothness_. Split its contents into two datasets, 70% for training and 30% for testing.
3. Use the Lab 1 code as a guide to build your own Nearest Neighbor classifier (K = 1). 
4. Display the percent error after classifying the test data
5. Loop the code so that you display classification error for K = 1..10
6. For K = 2, produce a graph to show the data from the two classes (radius vs compactness), and the classification of the test data (see figure)


```
Percent error (K=1): 16.3317%
Percent error (K=2): 12.8141%
Percent error (K=3): 14.8241%
Percent error (K=4): 13.3166%
Percent error (K=5): 14.3216%
Percent error (K=6): 14.5729%
Percent error (K=7): 14.3216%
Percent error (K=8): 13.3166%
Percent error (K=9): 14.8241%
Percent error (K=10): 13.5678%
```






<p id="gdcalert1" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image1.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert2">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image1.png "image_tooltip")


_X-axis is Radius, and Y-axis is Compactness. Red circles are Benign and Blue Malignant.  Red crosses are Benign predictions and Blue crosses are Malignant predictions.  If circles and crosses agree in color that’s a correct prediction, if not, its an incorrect prediction._

_[Breast Cancer Wisconsin (Diagnostic) Data Set](https://archive.ics.uci.edu/ml/datasets/breast+cancer+wisconsin+(diagnostic))_

_[https://github.com/gari3008ma/Breast-cancer-classification-using-neural-network/blob/master/wdbc.names](https://github.com/gari3008ma/Breast-cancer-classification-using-neural-network/blob/master/wdbc.names)_

_[Breast Cancer Wisconsin (Diagnostic) Data Set](https://www.kaggle.com/uciml/breast-cancer-wisconsin-data)_
