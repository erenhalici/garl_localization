# Generative Adversarial Reinforcement Learning for Object Localization

Below, the results for running training and running the [algorithm](https://ieeexplore.ieee.org/document/8451788) on the [Stanford Cars Dataset](https://ai.stanford.edu/~jkrause/cars/car_dataset.html) and [CelebA Dataset](http://mmlab.ie.cuhk.edu.hk/projects/CelebA.html) can be found. In both cases, the datasets have been split into training, validation and test sets. Here, the results on the 1024 test images for both datasets are being shown. (Please download the files in order to see them in full size.)

## Stanford Cars

![1024 Test Images (Stanford Cars)](test_index_stanford.jpg)

The red bounding boxes denote the output of the algorithm, whereas the green brounding boxes are the ground truth data. 

The IoU and the accuracy performance of the algorithm on the whole test set is given below: 

| Metric                    | Value  |
| ------------------------- |:------:|
| Mean of IoU Values        | 0.8526 |
| Variance of IoU Values    | 0.0214 |
| Accuracy (threshold 0.7)  | 0.9023 |
| Accuracy (threshold 0.8)  | 0.7900 |
| Accuracy (threshold 0.9)  | 0.5078 |

The accuracy is defined as the ratio of the images on which the agent has achieved IoU score over a certain threshold. It can be observed that %51 of the examples have an IoU greater than 0.9 and more than %90 of them have IoU > 0.7.

## CelebA

![1024 Test Images (CelebA)](test_index_celeba.jpg)

The IoU and the accuracy performance of the algorithm on the whole test set is given below: 

| Metric                    | Value  |
| ------------------------- |:------:|
| Mean of IoU Values        | 0.6442 |
| Variance of IoU Values    | 0.0728 |
| Accuracy (threshold 0.5)  | 0.7598 |
| Accuracy (threshold 0.6)  | 0.6953 |
| Accuracy (threshold 0.7)  | 0.5850 |
| Accuracy (threshold 0.8)  | 0.3730 |
| Accuracy (threshold 0.9)  | 0.1035 |
