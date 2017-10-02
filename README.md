Transfer Learning 
===================
This repository contains a model that can classify between dog and cat.  This model have used the **VGG** model and it's pre-trained weights  to make work easier and computationally cheaper . VGG model have been **fine tuned** by popping the last dense layer ( which were have 1000 possible outputs  ) and add another dense layer ( which have 2 possible outputs  ) to make that model. 

Dependencies
===================
* Keras 2.0.8
* Tenserflow
* Numpy
* Matplotlib
* Pickle

