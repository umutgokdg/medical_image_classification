# medical_image_classification
First of all, due to ethical concerns, the dataset used in this project will not be shared directly.
The link to the dataset and the studies conducted on this dataset are provided:
https://data.mendeley.com/datasets/zr7vgbcyr2/1

Detecting racial and gender bias on the medical images and their metadata.
And preventing this bias with bias mitigation.

In the algorithm phase: A multi-layer perceptron is used for tabular data and 
ResNet-18 for the images, and these are combined in a multimodal model.

To detect bias, a balanced dataset was used. The model was trained only on male data and 
tested on separate test sets containing either only male or only female data.
Then this method was repeatedly used for the model that trained only female data.
