# Protest Activity Detection and Perceived Violence Estimation from Social Media Images

Implementation of the model used in the paper [Protest Activity Detection and Perceived Violence Estimation from Social Media Images](https://arxiv.org/abs/1709.06204) by Donghyeon Won, Zachary C. Steinert-Threlkeld, Jungseock Joo.

### Contents
[Requirements](#requirements)   
[Usage](#usage)

### Requirements   
[Pytorch](http://pytorch.org/)   
[NumPy](http://www.numpy.org/)   
[pandas](https://pandas.pydata.org/)   
[scikit-learn](http://scikit-learn.org/)   

### UCLA Protest Image Dataset   
![alt text](https://raw.githubusercontent.com/wondonghyeon/protest-detection-violence-estimation/blob/master/files/1-d.png)
You will need to download our UCLA Protest Image Dataset to train the model. Please e-mail me if you want to download our dataset! (You can find my e-mail address in the paper.)

#### Dataset Statistics


### Model
#### Architecture   
We fine-tuned ImageNet pretrained (ResNet50)[https://arxiv.org/abs/1512.03385] to our data. You can download the our trained model from (here)[https://www.dropbox.com/s/hak8bp8zw8q6zfg/protest-model.pth.tar?dl=0].  
##### Performance

### Usage   
#### Training   
#### Evaluation
