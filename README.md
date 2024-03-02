#README
In this notebook, let us automate the inspection process by training top-view images of a casted submersible pump impeller using a Convolutional Neural Network (CNN) so that it can distinguish accurately between defect from the ok one.

We will break down into several steps:

Load the images and apply the data augmentation technique

Visualize the images

Training with validation: define the architecture, compile the model, model fitting and evaluation

Testing on unseen images

Make a conclusion

But if we take into account the cost of re-casting a product, we have to minimize the case of False Positive also, where the ok product is misclassified as defect. Therefore we can prioritize the F1 score which combines both Recall and Precision.

On test dataset, the model achieves a very good result as follow:

CONFUSION MATRIX:-

Accuracy: 99.44%
Recall: 99.78%
Precision: 99.34%
F1 score: 99.56%
