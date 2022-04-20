# Generating-Adversarial-Perturbations-using-Generative-Model

In this project we present a trainable generative model to fool pre-trained models by creating slightly perturbed images which resembles natural images. We present a deep neural network that transforms images to adversarial perturbations and the model can produce universal perturbations of fixed magnitude and able to produce non-targeted attacks on input images, and hence fool the classifier network.We used ResNet generator to create perturbations and ResNet18 as classifier model, that is to be fooled.The experiments were carried out on TinyImageNet dataset and the model achieves moderate fooling ratios with small perturbation norms.

# Model Architecture 

![](https://user-images.githubusercontent.com/80224279/164212670-2987ed3f-9835-4dd8-bf3a-839d2a61ffd9.png)


# Model and Hyper Parameters

Dataset : TinyImageNet

Model to be Fooled/ Classification network : ResNet18

Optimizer : Adam

learning rate = 0.0002

Cross entropy as loss function = 

![](https://user-images.githubusercontent.com/80224279/164213319-3d5e71a3-3456-492b-a895-d73ba76083a5.png)

Epsilon : 10, 15 and 20

# Results 

![](https://user-images.githubusercontent.com/80224279/164212910-fae7943f-64b3-493a-a4cd-a740d994e75e.png)

![](https://user-images.githubusercontent.com/80224279/164213286-2601721d-73b6-4f73-8a61-b2f4c1f920f9.png)
