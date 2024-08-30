# Auto-Segmentation-of-X-Ray-Images
The primary objective of this project is the development and training of a deep neural network, based on existing architectures, commonly used for other computer vision tasks (e.g. UNet, VGGnet, etc.) The training dataset consists of real-world X-ray images (raw and segmented), and the results will be benchmarked against manually labeled datasets.

**Data:**

Google Drive: https://drive.google.com/drive/folders/1bQDVcgdc5M4Ch7Yw1J5mpZqRUZlW2Dmp?usp=drive_link

We use various pre-trained models provided by the [**segmentation_models_pytorch**](https://github.com/qubvel-org/segmentation_models.pytorch) library, especially focusing on the ResNeXt and VGGNet for automating the segmentation of X-ray images. For this purpose as a first task, the dataset is examined and tried to be segmented with different network architectures. As a Second task, different studies were conducted on model training and testing to compare the performance of models in different scenarios (e.g. training on smaller image size, training with fewer data, noised test data, transfer Learning for bigger resolution images) of segmentation of X-ray images.
