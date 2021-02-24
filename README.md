# birdnest-occupancy-model
An object detection model to count birds nesting. The model will place a box around each bird detected, allowing extraction of metrics about the size and location of the bird. Optionally we try to classify the bird species.

## References
- Using Yolo, with [dataset](http://nameless.cis.udel.edu/data/nests/): [Fast, Deep Detection and Tracking of Birds & Nests](http://vision.cis.udel.edu/pubs/2016/WRS16/fast-deep-detection.pdf)
- Using Retinanet: [An Automatic Detection Method of
Bird’s Nest on Transmission Line
Tower Based on Faster_RCNN](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9187664)
- [Predicting Bounding Boxes using Cornell’s NABirds Data.](https://towardsdatascience.com/bird-box-1d31bad4c9c7) with EfficientNet uses the [NABirds V1 collection of 48,000 annotated photographs of the 400 species of birds that are commonly observed in North America](https://dl.allaboutbirds.org/nabirds)
- [Dataset 250 Bird Species 35215 Train, 1250 Test, 1250 Validation images 224X224X3 jpg format](https://www.kaggle.com/gpiosenka/100-bird-species)
