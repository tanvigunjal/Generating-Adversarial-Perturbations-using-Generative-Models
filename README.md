# Generating-Adversarial-Perturbations-using-Generative-Model

In this project we present a trainable generative model to fool pre-trained models by creating slightly perturbed images which resembles natural images. We present a deep neural network that transforms images to adversarial perturbations and the model can produce universal perturbations of fixed magnitude and able to produce non-targeted attacks on input images, and hence fool the classifier network.We used ResNet generator to create perturbations and ResNet18 as classifier model, that is to be fooled.The experiments were carried out on TinyImageNet dataset and the model achieves moderate fooling ratios with small perturbation norms.

# Model and Hyper Parameters
Dataset : TinyImageNet
Model to be Fooled/ Classification network : ResNet18
Optimizer : Adam
learning rate = 0.0002
Cross entropy as loss function

![image](https://user-images.githubusercontent.com/80224279/164211220-e431be81-e281-4c08-9306-8584ae87ddf6.png)

Epsilon : 10, 15 and 20
