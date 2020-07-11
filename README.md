# Scene Recognition Using Deep Learning
I have implemented indoor scene recognition of 67 indoor scene categories using deep learning technology. 

## Description 
Scene recognition is mainly classified into 2 i.e indoor scenes and outdoor scenes. The model that performs well for outdoor does not usually performs better for indoor scenes. Therefore, this is currently a challenging problem. 
To recognize indoor scenes I have used Convolution Neural Netowrk. This is a special type of Artificial Neural Network commonly used for visual computation. I have make use of technolgy of Transfer learning and utilized the pretrained weights on resnet30 and resnet50 to train CNN specifically for the given dataset. The model was first trained on training data and later achieved 87% accuracy in recognizing scenes of test data. 

## Dataset
The dataset was taken from this(http://web.mit.edu/torralba/www/indoor.html) link. The data consists of total of 67 indoor scene categories. Each category consists of atleat 100 images. 
## Technologies
- Deep Learning
  - Convolutional Neural Network (CNN)
- Google Colab
## Libraries
- fastai

