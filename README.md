
# AI Image Detector

This repository contains the code and documentation for an AI Image Detector project, developed to distinguish between real and AI-generated images using deep learning techniques. The project introduces a new dataset, CIFAKE, and employs various Convolutional Neural Network (CNN) architectures to achieve high classification accuracy.


## Introduction
AI-generated images are now so realistic that distinguishing them from real photos has become challenging. This project introduces a novel dataset, CIFAKE, and deep learning models to enhance detection accuracy, ensuring data authenticity.
## Dataset

 - [CIFAKE Dataset](https://www.kaggle.com/datasets/birdy654/cifake-real-and-ai-generated-synthetic-images)

60,000 real images from CIFAR-10.
60,000 AI-generated images using latent diffusion models.
Categories include: airplane, automobile, bird, cat, deer, dog, frog, horse, ship, and truck.



## Technologies Used

- Python
- TensorFlow/Keras
- Latent Diffusion Models
- CIFAR-10 Dataset


## Methodology
We used and fine-tuned pre-trained CNN models:

- ResNet50V2 
- EfficientNetV2B0
- EfficientNetB7

Training Setup: 
- Batch size: 128
- Learning Rate: 0.001
- Epochs: 20
The models were tailored for binary classification to distinguish between real and AI-generated images.
## Results
- EfficientNetB7 and EfficientNetV2B0 achieved a remarkable accuracy of 97.51%.
- Models demonstrated high precision and recall, validating their reliability in AI image detection.
## Future Work
- Experimenting with attention-based models.
- Expanding the dataset with more complex synthetic images.
- Developing explainable AI techniques for better interpretability.
## Authors

- [Sajid Hasan]()
- [Tabassum Tara Lamia](https://github.com/taralamia)
- [Parvez Ahammed](https://github.com/piru72)
- [Ashraf Shuvo]()

