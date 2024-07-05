# medical_image_classification
Detecting racial and gender bias on the medical images and their metadata.
And preventing this bias with bias mitigation.

In the algorithm phase: a multi-layer perceptron is used for tabular data and resnet-18 for the images.

To detect bias, a balanced dataset was used. The model was trained only on male data and 
tested on separate test sets containing either only male or only female data.
Then this method was repeatedly used for the model that trained only female data.
