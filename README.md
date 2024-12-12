# CNN-for-image-classification

For the implementation, our team used Python Programming language with Tensorflow and
Keras. This was due to TensorFlow and Keras simplify building and training CNNs, support data
augmentation, give pre-trained models for transfer learning and can integrate easily with tools like
Matplotlib for visualizing training and validation metrics.

Chosen Data set: RealWaste from UCI Machine Learning Repository.

![Screenshot 2024-12-11 092656](https://github.com/user-attachments/assets/6bca0bf0-1329-4ea2-b3ca-7c92f807f4d5)

The RealWaste dataset is a collection of high-quality color images of waste materials captured in
a landfill environment. Created as part of an honors thesis, the dataset was developed to explore how
convolutional neural networks (CNNs) perform when trained on images of waste in their authentic,
unprocessed forms compared to pristine or laboratory-controlled examples.
The dataset contains 524x524 resolution images, categorized into distinct classes based on the
material type present. It includes the following classes and respective image counts:


| **Category**            | **Number of Images** |
|--------------------------|-----------------------|
| Cardboard               | 461                   |
| Food Organics           | 411                   |
| Glass                   | 420                   |
| Metal                   | 790                   |
| Miscellaneous Trash     | 495                   |
| Paper                   | 500                   |
| Plastic                 | 921                   |
| Textile Trash           | 318                   |
| Vegetation              | 436                   |

 Our obejctive is to create a simple CNN that can classify the images into these 9 categories.
