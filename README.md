
# Deep Learning-Based Fovea Detection in Retinal Images for AMD Diagnosis

This project focuses on building and evaluating a deep learning model for bounding box regression, specifically for detecting fovea locations in retinal images. The goal is to accurately predict the center coordinates of fovea locations based on images, which is crucial in ophthalmology for assessing conditions like Age-related Macular Degeneration (AMD).


- We used the [AMD dataset](https://amd.grand-challenge.org/), which contains images along with their corresponding fovea coordinates (center points) as labels.

- Built a convolutional neural network (CNN) model using PyTorch. The architecture includes several convolutional layers followed by fully connected layers to regress the fovea coordinates. It employs multiple convolutional layers with increasing filter sizes, utilizing ReLU activations and pooling operations to extract features from the input images.

- Implemented a training loop that trains the model over several epochs, evaluates performance on a validation dataset, and adjusts learning rates as needed.
## Results
### The results are shown in the following screenshot:
![download](https://github.com/user-attachments/assets/e4473057-2620-4220-b013-ea02ed27c7e2)
