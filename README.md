# multitask-classification

We train 2 DNN classifiers on 2 different datasets and a single multitask classifier and examine their performance.

* Base model: Resnet20.
* Dataset 1: Fashion MNIST
* Dataset 2: Imagewoof
* Metrics: top-1 accuracy, Confusion Matrix

![](multitask_model.png "Multitask model")

### Metrics

Top-1 accuracy, %

| Model       | Fashion MNIST | Imagewoof |
|-------------|---------------|-----------|
| Single task | 87.96         | 65.74     |
| Multitask   | 81.67         | 62.28     |

### To do

1. Models aren't trained to their best since time shortage.
1. Training is slow, especially for multitask model. Can we take smaller model?
2. Use lr schedulers for multitask training to escape plateau.
