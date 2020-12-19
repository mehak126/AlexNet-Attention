# AlexNet Attention

An implementation of attention layers to the AlexNet model for ELL881 Fundamentals of Deep Learning.

**Attention Model Architecture**

Attention layers were added after the 4th and 5th convolution layers of the AlexNet model. The compatibility function can be either the ‘dot product’ (dp) or the ‘parameterised compatibility’ (pc) function, as described in the paper 'Learn to Pay Attention' ([link](https://arxiv.org/abs/1804.02391)). Similarly, the final classification can be done either by concatenation (concat) of descriptors or by averaging the scores from different levels (indep).

**Dataset**

The models were trained on a subset of the CIFAR-10 image dataset. 1000 images from the dataset with equal samples from each category were randomly selected. The validation set was of size 300 and the test set contained 500 images.

**Attention Map Visualisation**

A side by side comparison of the original images and their attention heat maps at different layers for each attention model trained is shown below. Some other images are available in the ‘images’ folder.

<img width="762" alt="1" src="https://user-images.githubusercontent.com/25842821/102684990-35ce9c00-4203-11eb-8f14-f59f1a367972.png">

<img width="762" alt="2" src="https://user-images.githubusercontent.com/25842821/102684998-3cf5aa00-4203-11eb-98d5-d893fd4951aa.png">

<img width="762" alt="3" src="https://user-images.githubusercontent.com/25842821/102685000-4121c780-4203-11eb-955c-01a6fbfd036a.png">

<img width="762" alt="4" src="https://user-images.githubusercontent.com/25842821/102685002-441cb800-4203-11eb-82ed-daba4d455f50.png">

