# Generative Adversarial Reinforcement Learning for Object Localization

In the image below, the results of the 1024 test images can be found:

![1024 Test Images](test_images.jpg)

The red bounding boxes denote the output of the algorithm, whereas the green brounding boxes are the ground truth data. 

The IoU and the accuracy performance of the algorithm on the whole test set is given below: 

| Mean of IoU Values        | 0.8526 |
| Variance of IoU Values    | 0.0214 |
| Accuracy (threshold 0.7)  | 0.9023 |
| Accuracy (threshold 0.8)  | 0.7900 |
| Accuracy (threshold 0.9)  | 0.5078 |

The accuracy is defined as the ratio of the images on which the agent has achieved IoU score over a certain threshold. It can be observed that %51 of the examples have an IoU greater than 0.9 and more than %90 of them have IoU > 0.7.
