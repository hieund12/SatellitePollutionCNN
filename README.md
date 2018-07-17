# SatellitePollutionCNN

![Methodology](methodology.png)

Predicting Air Pollution Levels from Satellite Images Using Deep Convolutional Neural Networks

TLDR: A novel algorithm to predict air pollution levels with state-of-art accuracy using deep learning and GoogleMaps satellite images.

While it has been well-recognized that air pollution can be a significant problem that affects public health, agriculture, and urban development, there are visible limitations in current methodologies to obtain accurate air pollution information.  Some of these use incomplete or unreliable information, while others rely on expensive or unstandardized sensor readings.  This study investigates the feasibility and accuracy of using a convolutional neural network upon satellite images to predict the Breezometer Air Quality Index (BAQI).  Data for this analysis can be obtained using open and free resources online, and the analytics can be performed on relatively inexpensive, consumer-grade hardware.  To perform the analysis, a set of scripts and applications were used for parallelized data collection of 10,000 satellite images at resolution 1280 x 1280 and 10,000 Breezometer air quality data records across 57 cities.  A variety of models, including a six-layer convolutional network, were trained to predict the BAQI, given the satellite imagery.  The number of convolutional layers, number of maxpool layers, size of convolutional layers, use of dropout, and use of data augmentation were varied, among other parameters and techniques.  The experiments found that one model achieved an accuracy rate of 85.15% in binary classification of pollution, and another model achieved an accuracy rate of 72.70% in 10-class classification of pollution.  This novel research demonstrates that satellite images, which are inexpensive and ubiquitous, are accurate in predicting air pollution.
