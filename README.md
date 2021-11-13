# Transfer Learning

The Transfer Learning technique's idea is to take advantage of these high-performance pre-trained neural networks, developed by many machine learning experts and trained by large-scale datasets, and then use them for our own purposes. In other words, we can apply pre-trained neural networks' knowledge to a dataset it has never seen before.
<p align="center"><img src="https://user-images.githubusercontent.com/3027146/141642154-0071c737-37fc-4d5a-80cc-9b4254ddbf88.jpeg" width="600"></p>

# Perform Transfer Learning with TensorFlow Hub

In the repo, we will use TensorFlow Hub to do Transfer Learning. In transfer learning, we reuse parts of an already trained model and change the final layer, or several layers, of the model, and then retrain those layers on our own dataset.

We will perform transfer learning with the MobileNet_V2 and Inception Model to create a CNN that uses Inception and MobleNet as the pretrained model to classify the images from the Flowers dataset. Then comparing the accuracy we get with Inception v3 to the accuracy of MobileNet v2.

## Plot Model Predictions
<p align="center"><img src="https://user-images.githubusercontent.com/3027146/141642209-fc16fbf6-e2c9-4e42-90e1-73bfbdc8ca0f.png" width="600"></p>
