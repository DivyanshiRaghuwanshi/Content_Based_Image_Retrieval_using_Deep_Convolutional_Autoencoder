# Content_Based_Image_Retrieval_using_Deep_Convolutional_Autoencoder
This project implements a deep convolutional autoencoder to perform content-based image retrieval (CBIR) on an animal image dataset. The model learns a compressed latent representation of the images, enabling efficient retrieval of similar images based on content rather than metadata or labels. The project demonstrates:

-> Preprocessing and loading an animal dataset
-> Building and training a convolutional autoencoder using TensorFlow/Keras
-> Extracting latent features for image retrieval
-> Using Euclidean distance in latent space to find similar images
-> Visualizing query images and top-k similar matches

**Model Architecture Diagram:**
![image](https://github.com/user-attachments/assets/88e9d0ea-e5be-42af-9606-ae477c6ee579)

This project uses the Animal Dataset for training; you can obtain it by running the following code-

import kagglehub

path = kagglehub.dataset_download("theaayushbajaj/cbir-dataset")

print("Path to dataset files:", path)

After training of model, input image provides to model for test-

![image](https://github.com/user-attachments/assets/a1604039-ab2e-44b1-b6dd-ff13b837c1af)

Recieved output from model is-

![image](https://github.com/user-attachments/assets/b7a87603-ab35-4da6-8211-3a66c1df0e05)



