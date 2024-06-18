# COVID-19 Classification using CT Scan 
  * With the outbreak of the COVID-19 pandemic, the need for rapid and accurate detection of the virus became paramount. Machine learning and deep learning techniques have played a crucial role in developing sophisticated systems to aid healthcare professionals in diagnosing COVID-19 efficiently. This project leverages CT scan images to differentiate between COVID-19 infected lungs and non-COVID-19 lungs, thus assisting in early detection and treatment.

  * The analysis of a CT scan image reveals the presence or absence of COVID-19 based on the input image. The model is built using two different architectures, VGG16 and Xception, which are well-known convolutional neural network models in the field of image classification.

# Dataset
* The dataset is taken from Kaggle. It includes labeled CT scan images for both COVID-19 positive and negative cases.
* Link: https://www.kaggle.com/datasets/plameneduardo/sarscov2-ctscan-dataset

# Model Architectures
# VGG16
  * VGG16 is a convolutional neural network model known for its simplicity and depth. It consists of 16 layers with weights, including convolutional layers, fully connected layers, and max pooling layers.
  * Accuracy: The model achieved an accuracy of 87% in detecting COVID-19 from CT scan images.
# Xception
  * Xception, which stands for Extreme Inception, is a deep learning model that relies on depthwise separable convolutions, making it more efficient and effective in image classification tasks.
  * Accuracy: The model achieved an accuracy of 92% in detecting COVID-19 from CT scan images.
    
# Algorithm Comparison
![image](https://github.com/Athikabilanvenkatesan/COVID-19-CT-SCAN-CLASSIFICATION/assets/113780724/d0b3c12a-2d7f-439e-bda0-98da65bbc79d)

Based on the accuracy metrics, the Xception model outperforms the VGG16 model in detecting COVID-19 from CT scan images.

# Conclusion
* For this project, the Xception model is used for the development of the COVID-19 detection system due to its higher accuracy of 92%. This system can significantly aid healthcare providers in diagnosing COVID-19, thus facilitating timely and appropriate medical interventions.

* By implementing this COVID-19 detection system, we can contribute to better management and control of the pandemic, providing a valuable tool for the healthcare industry.
