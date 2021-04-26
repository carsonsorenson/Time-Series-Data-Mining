# Time Series Data Mining
* Collection of time series classification methods I used for my final project in CS 6890 - Temporal Data Mining
* The purpose of this project is to diagnose whether a
person has Autism or Asperger’s from a functional magnetic
resonance imaging (fMRI) scan of their brain. To do this, I
will implement several time series classification algorithms
and deep learning techniques to explore which methods
perform the best.

## Techniques Used

### Time Domain Based Classifiers
* 1 Nearest Neighbor Classifier
* K Nearest Neighbors with DTW and Euclidean distance metrics

### Differential Distance Based Classfiers
* KNN using Complexity Invariant Distance

### Interval Based Classifiers
* Time Series Forest

### Dictionary Based Classifiers
* Bag of Patters

### Deep Learning Methods
* Fully connected neural network
* Convolutional neural network

## Final Results

|Method|Recall Score|Accuracy Score|
|------|------------|--------------|
|1 Nearest Neighbor|32.2%|53%|
|KNN (Euclidean Distance)|48.3%|49%|
|KNN (DTW Distance)|56.3%|52%|
|KNN (CID Distance)|40.2%|54.5%|
|Time Series Forest|42.5%|62.1%|
|Bag of Patters|43.7%|50%|
|Fully Connected Neural Network|57.5%|59.2%|
|Convolutional Neural Network|60.7%|55.5%|
