# Fine-Tuning-ResNet50-Pretrained-on-ImageNet-for-CIFAR-10
We explored the process of fine-tuning a pretrained ResNet50 model on the CIFAR-10 dataset.

Read the blog post that explains this project: [Fine-Tuning ResNet50 pretrained on ImageNet for CIFAR-10](https://sidthoviti.com/fine-tuning-resnet50-pretrained-on-imagenet-for-cifar-10/)

## Hyperparameters
* Stochastic gradient descent (SGD) optimizer with a learning rate of 0.01.
* Momentum of 0.9, and a weight decay of 5e-4.
* Epochs 60

## Results
![Loss Plot](https://github.com/sidthoviti/Fine-Tuning-ResNet50-Pretrained-on-ImageNet-for-CIFAR-10/assets/96778922/f161b981-b4bc-4083-8aeb-e0efe3c8c1ed)
![Accuracy Plot](https://github.com/sidthoviti/Fine-Tuning-ResNet50-Pretrained-on-ImageNet-for-CIFAR-10/assets/96778922/af07fc7b-b17b-49aa-8956-013bcd7fcad5)
* Training Accuracy: The training accuracy steadily increases with each epoch, starting from 53.80% in the first epoch and reaching 90.64% in the final epoch. This indicates that the model is learning and improving its performance on the training data.

* Training Loss: The training loss gradually decreases over the epochs, starting from 1.3067 and decreasing to 0.2779. Lower training loss values indicate that the model is fitting the training data better.

* Testing Accuracy: The test accuracy also shows improvement throughout the epochs, starting from 69.60% and reaching 87.68% in the final epoch. This suggests that the model is generalizing well and performing better on unseen data.

* Test Loss: The test loss initially decreases and then fluctuates slightly, but overall, it remains relatively stable. It starts at 0.8660 and ends at 0.3625.
