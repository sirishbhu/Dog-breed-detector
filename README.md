[image1]: ./images/sample_dog_output.png "Sample Output"

## Project Overview

The project is a part of Udacity's Data Science Nanodegree.In this project,we will be given a dog's photo and the output will be the breed of the dog.If instead of dog,the image of a human will be given the output will be the most resembling breed of the dog.

![Sample Output][image1]

### Libraries

The libraries used in this project are as follows-  
1.sklearn  
2.keras  
3.numpy  
4.glob  
5.random  
6.opencv  
7.matplotlib  
8.tqdm  
9.PIL

### Files

#### dog_app.ipynb -Our main code notebook  

#### bottleneck features- For storing pre-trained models  like VGG-16 and ResNet-50 so that we don't need to train our model from scratch.  

#### haarcascades- For storing pre-trained models to detect human faces.

#### images- For storing images to check performance of our model.  

#### requirements- For storing requirements and dependencies according to OS. 

#### saved_models- For storing trained CNN models.  

#### extract_bottleneck_features.py- For extracting bottleneck features of the specified pre-trained model.  

### Results

First,we achieved an accuracy of 6% using our own CNN model made from scratch which was very bad.Then, using VGG-16 pre-trained model we achieved an accuracy of 42% which was also bad.  
The final CNN model using transfer learning from Resnet-50 gave a fair enough accuracy of 82% and was able to predict the breeds almost crrectly for the given samples.

### Acknowledgements

The credit for the dataset and code template goes to udacity.  

