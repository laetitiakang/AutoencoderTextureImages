# Texture Image Anomaly Detection using Autoencoder: Model Design, Training, and Distortion Analysis

May 2023 - Jun 2023May 2023 - Jun 2023
- Implemented an Autoencoder network for texture image anomaly detection.
- Designed and built the architecture of the Autoencoder model, consisting of convolutional and linear layers in PyTorch.
- Utilized Albumentations library for data augmentation, including random cropping, flipping, brightness/contrast alteration, and gamma correction.
- Partitioned a dataset of texture image tiles into training and test sets, ensuring an 80% - 20% split.
- Developed a training loop to optimize the Autoencoder model using the Adam optimizer and Mean Squared Error (MSE) loss function.
- Implemented functions to load texture image tiles, sample random training batches, and visualize reconstructed images.
- Incorporated distortion effects, such as sun flare, grid shuffle, and spatter, to evaluate the Autoencoder's performance on distorted images.
Conducted a statistical analysis by comparing the MSE values of the reconstructed images with and without distortions.
- Demonstrated the effectiveness of the designed Autoencoder network in the anomaly detection problem through the analysis of the results.
