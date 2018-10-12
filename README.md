# Disaster Risk Predictor
We are predicting likelihood of natural disasters occurring at a particular location by building a time series model of previous occurrences on the basis of time of calamity and severity. We will be using a dataset which has a record of natural disasters with their severity, time of occurrence, duration of occurrence and geographical location. A doomsday clock for natural disasters akin to the one for man-made disasters will also be animated.
Further, we are also clustering all the disasters based on geographical location. A coloured map will be generated with reference to likelihood of natural disasters occurring.
Precautionary guidelines will be recommended based on the type and severity of disaster predicted.
This project is intended to help reduce the damage caused by natural disasters by helping people be more prepared.
We will scrape real time natural disaster reports from various sources as well and display in a feed.
Since all model training and predictions take place on server side, the app usability should not be affected even in regions with poor connectivity.
Implementation: We will be using an unsupervised learning clustering algorithm for identifying risk prone areas to learn spatial dependency. For the time series analysis, we will be using an LSTM algorithm to learn temporal dependency. 
Datasets used: EM-DAT: The Emergency Events Database by CRED, Significant Earthquakes, 1965-2016 by US Geological Survey, Landslides After Rainfall, 2007-2016 by NASA.
