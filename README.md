# HTRU1

The HRTU1 Batched Dataset is a subset of the HTRU Medlat Training Data, a collection of labeled pulsar candidates from the intermediate galactic latitude part of the HTRU survey. It was assembled to train the SPINN pulsar classifier described in:

*SPINN: a straightforward machine learning solution to the pulsar candidate selection problem*
V. Morello, E.D. Barr, M. Bailes, C.M. Flynn, E.F. Keane and W. van Straten
http://arxiv.org/abs/1406.3627

The full HTRU dataset is available [here](https://archive.ics.uci.edu/ml/datasets/HTRU2#). If you use these data please cite:

*The High Time Resolution Universe Pulsar Survey - I. System Configuration and Initial Discoveries* 
M. J. Keith et al., 2010, Monthly Notices of the Royal Astronomical Society, vol. 409, pp. 619-627. DOI: 10.1111/j.1365-2966.2010.17325.x 

## The HTRU1 Batched Dataset

The HTRU1-BD consists of 60000 32x32 colour images in 2 classes: pulsar & non-pulsar. There are 50000 training images and 10000 test images. The HTRU1-BD is inspired by the [CIFAR-10 Dataset](http://www.cs.toronto.edu/~kriz/cifar.html).

The dataset is divided into five training batches and one test batch. Each training batch contains 10000 images. The test batch contains exactly 100 randomly-selected images from each class. The training batches contain the remaining images. These are in random order, but each training batches contains the same balance of pulsar and non-pulsar images. Between them the training batches contain 1096 true pulsars and 48904 non-pulsars. 

This is an imbalanced dataset.