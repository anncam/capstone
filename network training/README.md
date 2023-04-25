## Neural network training

This folder contains resources I used for training neural networks. Since I was only able to train models on a mini-ImageNet dataset consisting of 100,000 images vs. the full ImageNet which is 1 million images, I only linked the source of the mini set. 

I used a [PyTorch](https://github.com/pytorch/examples/tree/main/imagenet) GitHub repository that provided the examples and tools to train neural networks on ImageNet. The main.py file required torch and torchvision be installed. Then when running the main.py file you can set conditions specifying which model you would like to run. You can also set parameters like batch size and worker number which were two parameters I used in my slurms. 

Below is an example slurm job I used to train a resnet50 model on the mini-ImageNet. I have blocked out certion personal information and removed the folder path. 

![image](https://user-images.githubusercontent.com/64801054/234148909-0aac73fc-517a-41bc-90d7-b39553c84da5.png)


Mini ImageNet download source: https://www.kaggle.com/datasets/arjunashok33/miniimagenet

PyTorch neural network repository: https://github.com/pytorch/examples/tree/main/imagenet
