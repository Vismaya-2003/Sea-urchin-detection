# Sea Urchin Detection

## Overview
Welcome to the Sea Urchin Detection repository. This project is a proof-of-concept model developed in collaboration with the National Institute of Ocean Technology (NIOT) for detecting sea urchins in underwater images. Utilizing advanced deep learning techniques, this model aims to enhance marine ecosystem monitoring and conservation efforts.

## Key Features

- **Model Architecture:**
  - Custom Convolutional Neural Network (CNN) designed for image classification.
  - Includes multiple convolutional and max-pooling layers to capture spatial hierarchies.
  - Finalized with fully connected layers for classifying images into 'urchins' and 'not-urchins'.

- **Real-Time Model Implementation:**
  - Optimized for low-latency processing to enable real-time detection during underwater missions.
  - Integrated with an onboard camera and processing unit for live video feed analysis.
  - Uses GPU acceleration for high-resolution video streams.
  - Tested in simulated underwater environments with further validation ongoing.

## Dataset

The dataset used for training the model was created with the following steps:

1. **Data Collection:**
   - Extensive underwater footage was provided by NIOT from various marine environments.
   - Footage was segmented into individual frames for detailed analysis.

2. **Data Annotation:**
   - Marine biologists and data annotators manually labeled each image to identify sea urchins.
   - The dataset includes diverse underwater scenes, capturing different species, conditions, and lighting scenarios.

3. **Preprocessing:**
   - Images were preprocessed to normalize lighting variations and enhance contrast.

**Note:** The full dataset is not included in this repository due to size and licensing constraints. For access to the dataset, please refer to the [NIOT Data Access Instructions](#) or contact the dataset provider.

## Proof of Concept

This model is presented as a prototype to demonstrate the feasibility of AI in marine species detection. While promising, further refinement, additional data, and tuning are recommended for production-level deployment.

## Application

- **Integration:**
  - Can be integrated into marine monitoring systems to assist researchers and conservationists.
  - Helps track sea urchin populations, identify ecological patterns, and support conservation strategies.

- **Future Work:**
  - Expanding the model to detect a broader range of marine species.
  - Improving performance and accuracy based on real-world testing.


