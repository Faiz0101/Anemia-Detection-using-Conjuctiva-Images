This repository contains code for detecting anemia using conjunctiva images. Anemia is a common blood disorder that affects millions of people worldwide. One of the key indicators of anemia is the appearance of the conjunctiva, the thin, transparent layer covering the white part of the eye. This project aims to develop a computer vision-based system to automatically detect anemia using images of the conjunctiva.




                                                                              Key Components:

Dataset: The dataset comprises conjunctiva images sourced from various repositories, encompassing both healthy and anemic individuals. These images are meticulously labeled and categorized into training, validation, and testing sets to facilitate model development and evaluation.

Preprocessing: A preprocessing pipeline is employed to standardize the images, including resizing, normalization, and augmentation techniques to enhance the robustness of the model.

Model Development: The core of the project lies in the creation of a deep learning model, specifically a convolutional neural network (CNN), trained on the preprocessed data. The model learns to differentiate between healthy and anemic conjunctiva patterns, enabling accurate classification.

Evaluation: The trained model undergoes rigorous evaluation using metrics such as accuracy, precision, recall, and F1-score to assess its performance on unseen data, ensuring its reliability in real-world scenarios.

Inference: The trained model can be deployed for inference, enabling healthcare professionals to input new conjunctiva images and obtain predictions regarding the presence of anemia.
