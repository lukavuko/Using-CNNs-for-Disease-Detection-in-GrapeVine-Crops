# Grape Vine Disease Detection

## An Innovative Computer Vision Technique for Future Drone Application

Welcome to our ML project for the Agorize, "AI in Business" competition!

**Our goal is to use convolutional network models for agricultural drone application to seamlessly and systematically survey vineyards.** Our specific project aims to prototype the monitoring of grapevine health. Drone scanning can help address localized vineyard issues like fungal diseases, water needs, and fertilizer needs to help optimize operations for the most high quality grapes. For now, our model only evaluates health in terms of disease, but we hope to eventually expand the dataset to use more "realistic" and "dirty" data with more health factors!

**Model design is very basic but works exceptionally well.** It's contains several convolutional layers using ReLu activations which are flattened and fed into a dense output layer with sigmoid activation intended to perform a simple binary classification of whether a leaf is healthy or not. It's packaged and available in the h5 file format.

![image](https://github.com/user-attachments/assets/8581e2b8-35ca-4cb6-ae2a-8a5cc98adaa0)


## Visualizing Model Outputs:

***Healthy***
  | | |
  | --- | --- |
  | ![image](https://github.com/user-attachments/assets/e353a255-e4e4-4a37-8b55-c35af3065289) | ![image](https://github.com/user-attachments/assets/8f6ba9c8-5501-4f2c-972e-67832cc3cc57) |


***Diseased***
  | | |
  | --- | --- |
  |  ![image](https://github.com/user-attachments/assets/39883076-99ff-4e9e-88b5-819f41039937) | ![image](https://github.com/user-attachments/assets/3d85c0d0-8206-4d96-a47d-7a56893f0aa8) |

## Acknowledgement

Thank you to the researchers below who developed the open source dataset that lets experiential learning projects like this take place:
- Hughes, D., & Salathé, M. (2015). **An open access repository of images on plant health to enable the development of mobile disease diagnostics.** *arXiv preprint arXiv:1511.08060.*
