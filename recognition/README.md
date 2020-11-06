# Recognition Problems
# Classify laterality (left or right sided knee) of the OAI AKOA knee data set
* Student Name: Xu Jianliang
* Student No. 45855537
* Student E-mail: s4585553@student.uq.edu.au

## File specification
* dataProcess.py is the file to Process the raw data, create two folders and write photos of the left knee and the right knee into the two folders respectively.
* train.py is the file to train the dataset，here we use DenseNet as base net, and the weights of ImageNet, then we train the last seven layers.
* predict.py is the file to predict the results of the test data.

## Requirment:
Version: Tensorflow >=2.20

## Algorithm:
### DenseNet
![image](https://github.com/Alexu0506/PatternFlow/blob/topic-recognition/recognition/p1.png)
* 5-layer dense block with a growth rate of k=4. Each layer takes all preceding feature-maps as input.  

List several advantages of densenet:
1. Reduced vanishing gradient
2. Enhanced feature delivery
3. More effective use of features
4. To some extent, the number of parameters is reduced
