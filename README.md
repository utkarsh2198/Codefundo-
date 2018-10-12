# Codefundo++
## Determination of aftershock patterns following large earthquakes using deep learning techniques.

### Problem Background
Large Earthquakes are generally followed by aftershocks, using past earthquake data of major and after shock we plan to predict after shock pattern of future earthquakes.By predicting aftershock, steps can be taken in the direction to disburse relief funds accordingly and care can be taken to minimize the casualties and destruction caused by the disaster. 
### Solution proposed and data required
This problem is addressed as a binary classification problem, areas are divided into grids and data is extracted for each grid. This data include various features related to earthquake and a target variable indicating whether aftershock occured in the area corresponding to the grid or not. We plan to train a deep learning model on this data which can then predict the presence of aftershock in that particular area.
### Datasets 
We will be training and testing our model using co-seismic slip distributions from the SRCMOD online database of finite-fault rupture mode(http://equake-rc.info/SRCMOD/).
The aftershocks that occurred between one second and one year after the mainshocks in each grid cell will be compiled from the International Seismological Center (ISC) event catalogue(http://www.isc.ac.uk/iscbulletin/search/catalogue/).
### Technologies
We will be using python libraries like keras with tensorflow backend for data preprocessing, training and testing our model. Microsoft Azure will also be used for building, testing, deploying our application.
