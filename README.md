# Metal-Part-Segregation-CNN

- The project is a vision-based project, implementing segregation of welded metal part on the basis of their precision, utilizing CNN for object detection, OpenCV and an industrial-grade webcam.
- It also includes an advanced automatic conveyor belt system with integrated proximity sensors and an encoder, seamlessly interfaced with Siemens-LOGO8-PLC and SCADA for efficient control.

## Overview

In the manufacturing and construction industries, weld quality is a critical parameter that directly affects the durability and safety of metal structures. Traditional methods of inspecting weld quality often involve manual examination, which can be time-consuming, subjective, and prone to human error. To address these challenges, I proposed an automated system that leverages the capabilities of Convolutional Neural Networks (CNN) and automated conveyor belt system to accurately classify welded metal parts based on their welding quality. This system is designed to automate the inspection process, ensuring higher accuracy, consistency, and efficiency in quality control operations.

## System Description

The core of the system is a CNN model that performs binary classification to distinguish between 'welded properly' and 'not welded properly' conditions. The CNN model is built using TensorFlow and Keras, incorporating several convolutional layers to extract meaningful features from images of welded joints. These layers are followed by max pooling layers to reduce dimensionality, and dense layers for classification.

To enhance the model's robustness and its ability to generalize across various welding scenarios, we employ data augmentation techniques. Using Keras' ImageDataGenerator, the training dataset is augmented in real-time with transformations such as rotations, width and height shifts, shear transformations, zoom, and horizontal flips. These augmentations simulate different photographic conditions and perspectives, preparing the model to accurately evaluate weld quality under diverse conditions.


## Technologies and Tools

- TensorFlow & Keras
- OpenCV
- Python
- PLC Programming
- Siemens-LOGO8-PLC

### Edge Detection and Bounding Box Calculation
![WhatsApp Image 2024-02-19 at 23 18 48 (2)](https://github.com/Prajyot9501/Metal-Part-Segregation-CNN/assets/60104217/f8f4f3fd-854f-4bdf-aae4-ea33a4119700)

### Collection of different metal parts for training and testing the model
![Metal-parts](https://github.com/Prajyot9501/Metal-Part-Segregation-CNN/assets/60104217/1518e644-b2ed-4813-a65d-5a5fbd7760f8)

### Conveyer Belt system with PLC
![WhatsApp Image 2024-02-19 at 23 18 48](https://github.com/Prajyot9501/Metal-Part-Segregation-CNN/assets/60104217/5fd9ca63-bf98-4a87-b1bc-abf015de90b8)

### PLC's FBD for DC motor's operation
![WhatsApp Image 2024-02-22 at 16 14 59](https://github.com/Prajyot9501/Metal-Part-Segregation-CNN/assets/60104217/44333ed9-d89d-4833-818b-9e2c18e8fb47)



