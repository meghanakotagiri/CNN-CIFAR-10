# CNN-CIFAR-10
To fine tune moderately deep CNN so that it fits well to CIFAR-10 dataset
AIM:To fine tune moderately deep CNN so that it fits well to CIFAR-10 dataset

Base Architecture of the model: The neural network has 2 convolution layers and 2 fully connected layers, followed by a softmax layer. The first convolution layer has 64 filters each of size 55. It is followed by a max pooling layer of size 22. The second convolution layer also has 64 filters each of size 5*5. This layer is also followed by a max pool layer. The size of the first fully connected layer is 256 and followed by another fully connected layer of size 128.
![alt text](https://github.com/meghanakotagiri/CNN-CIFAR-10/blob/master/model.png)
Various parameters of the base model were varied to fine tune the CNN so that it fits the CIFAR-10 dataset well. 

Please refer to the file [AMP Assignment-1 Report.pdf](https://github.com/meghanakotagiri/CNN-CIFAR-10/blob/master/AMP%20Assignment-1%20Report.pdf) for the different model variants that we have experimented with.

Collaborators: Meghana Kotagiri(meghanakotagiri) Neha Gaddam(nehareddyg) 
