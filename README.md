# tomato_disease_classification

Took the datasetfrom: <br>
https://www.kaggle.com/datasets/arjuntejaswi/plant-village

About the Dataset:
- The dataset has 10 classes.
- Total 16000 images(after augmentation)

Methodology:
1. Used split_folder to get train, test and validation split of 80%, 10% and 10% accordingly.
2. Used ImageDataGenerator to augment images.
3. Used tensorflow to build the sequential model.
4. The architecture is CNN with 1 Conv2D layer followed by a Maxpooling layer.
5. All the hidden layers have "relu" as activation function.
6. Output layer uses "softmax" activation function to get the confidence while classifying images.
7. A flatten layer to prepare it for the dense layer.
8. There were 10 classes including the Healthy leaves.
9. Optimizer is used "adam".
