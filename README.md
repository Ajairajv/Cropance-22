# Cropance-22

# Cotton Leaf Disease Prediction using Flutter APK
This project aims to detect and classify the diseases present in cotton leaves and plants using image processing and deep learning techniques. The proposed solution employs a real-time dataset, including multiple photographs of sick cotton leaves, diseased cotton plants, and their corresponding fresh leaves and fresh cotton plants. The dataset contains 313 diseased cotton leaf images, 453 fresh cotton leaf images, 843 diseased cotton plant images, and 448 fresh cotton plant images.

## Algorithm Used
The project employs Convolutional Neural Networks (CNN) to process images. CNN is a deep learning method for image classification, and it can learn features directly from the image data. The CNN architecture used in this project includes Conv2D and Max pooling layers. We also used transfer learning, a technique of reusing pre-trained models to solve new problems.

## Proposed Solution
The proposed solution follows the following approach:

## Image pre-processing: 
High-quality and high-resolution photos are required during this stage. The photographs have been cropped, scaled, and augmented using a data augmentation approach to eliminate any noisy material.

## Image segmentation: 
The process of breaking up a digital image into several parts. This allows for easy identification of the model's contaminated parts by removing the affected pixel region from the leaf.
 
## Feature extraction: 
This step involves taking some of the damaged leaf's key features and extracting them. It generates colored structures and converts the color value from the RGB components of the cotton leaf image's defective areas. We can train our neural network using this feature.

The model is trained on the real-time dataset, and the accuracy is measured using test data. Once the model is trained, it is converted to tflite model to be used in mobile applications. 

![image](https://user-images.githubusercontent.com/87579782/219725778-72c13999-767c-44f8-be7f-6933c447f107.png)


![image](https://user-images.githubusercontent.com/87579782/219725647-e7b6172e-0d51-4ffc-b7bd-1e0e4db6649b.png)


## Usage
This project includes a Flutter APK that allows the model to be executed on both iOS and Android. When a cotton leaf is scanned, it indicates whether it is infected or not. To display the identification of the type of data that we enter, labels text files with class names need to be generated.

## Output
![image](https://user-images.githubusercontent.com/87579782/219725351-c05145bb-a6bb-40f4-9b74-a369738611b4.png)

![image](https://user-images.githubusercontent.com/87579782/219725496-a85a5485-5cbb-4184-af7a-0ecad5a8ecdc.png)

## Conclusion
The proposed solution offers an efficient and effective approach to detect and classify the diseases present in cotton leaves and plants. It can help farmers and researchers identify diseases in their crops and take appropriate measures to control and prevent them.
