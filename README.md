# Crypto Analysis using Machine Learnings (KMeans, Scaling and PCA)

In this project we use machine learning techniques (KMeans, StandardScaler, and Principal Component Analysis) to scale, reduce the dimensionality, and cluster our data. Below is a simple explanation of what these processes aim to accomplish:

* KMeans - Clusters the data into group that share similar characteristics
* Elbow analysis - Process to determine which number of clusters are the most efficient by studying the inertia
* Standard Scaler - Processes the data to have and equal scale, a necessary before applying our ML models since unscaled data can be skewed and alter our results
* Principal Component Analysis - Reduces the dimensionality of our data, that is remove data that does not affect our results in a significant manner. This not only reduces our data but can make the ML models more efficient/faster.
* Explained Variancy Analysis - To determine which percentage of the original data each component holds and the aggregate of these.

---

## Technologies

The following technologies were used to build and deploy this application:

* Python - Version 3.9.7
* Anaconda (Which includes Jupyter Lab and Pandas)
* Path (from pathlib)
* hvPlot
* sklearn

---

## Installation and Usage Guide

### 1. Install Python 3.9.7

For installing Python 3.9.7 you can find the Installation Files for both Windows/Mac OS in the following link
 * [Anaconda Installation Files](https://www.anaconda.com/products/individual "Anaconda Installation Files")

If you require assistance installing it, you can follow the following videos for guidance
* [Youtube Video Python Installation Guide - Windows](https://www.youtube.com/watch?v=uSVl7gRXP80 "Python Installation Video - Windows") 
* [Youtube Video Python Installation Guide - Mac](https://www.youtube.com/watch?v=r6bBaj797t8 "Python Installation Video - Mac") 
 
### 2. Install Anaconda

For installing Python 3.9.7 you can find the Installation Files for both Windows/Mac OS in the following link
 * [Python Installation Guide](https://www.python.org/downloads/release/python-397/ "Python Installation Guide")

If you require assistance installing it, you can follow the following videos for guidance
* [Youtube Video Anaconda Installation Guide - Windows](https://www.youtube.com/watch?v=g6ln1dAt-RI "Anaconda Installation Video - Windows") 
* [Youtube Video Anaconda Installation Guide - Mac](https://www.youtube.com/watch?v=oWVTO_69U4c "Anaconda Installation Video - Mac")

### 3. Installing Required Librabries

For installing the sklearn library please follow the following link
 * [sklearn Installation](https://scikit-learn.org/stable/install.html "sklearn")

 For installing the hvPlot library please follow the following link
 * [hvPlot Installation Guide](https://hvplot.holoviz.org/developer_guide/index.html "hvPlot Installation Guide")


### 3. Downloading the Crypto Analysis using Machine Learnings (KMeans, Scaling and PCA) Repository

Navigate to your desired location where you would like to save the documents for this application. You can do this by using the ```cd``` command followed by a space and the file path inside quotations ```" file path "```. In my example I have gone to Desktop.

![image](https://user-images.githubusercontent.com/94983278/149385012-181d1769-0af6-487e-8e04-823a28f2c3ed.png)

Clone this project's repository from GitHub using the following command 

```https://github.com/epocaterrasus/CryptoCurrenciesKMeansPCA.git```

### 4. Opening the notebook

Being in the folder created when you downloaded the repository type ```jupyter lab```, this will open the Jupyter Lab

---


## Images

* Elbow Analysis, before and after Principal Component Analysis Application
![image](https://user-images.githubusercontent.com/94983278/155596351-bed58cdd-ff6e-4527-bed5-6e687b9f311b.png)

* Scatter plots using 4 Clusters (Optimal Number as shown in Elbow Analysis) before and after Principal Component Analysis Application
![image](https://user-images.githubusercontent.com/94983278/155596515-5f67fd5a-bef9-49d9-b6b2-7d75d3b7e61a.png)
---

## Contributors

Edgar Pocaterra - epocaterra@protonmail.ch / +1 806 283 5455

---

## License

MIT License

Copyright (c) 2022 epocaterrasus

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.