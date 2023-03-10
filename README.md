# Hyperspectral-Image-Classification

Hyperspectral Image (HSI) classification using Convolutional Neural Networks (CNN) is widely found in the current literature. Approaches vary from using SVMs to 2D CNNs, 3D CNNs, 3D-2D CNNs, FuSENets. Besides 3D-2D CNNs and FuSENet, the other approaches do not consider both the spectral and spatial features together for HSI classification task, thereby resulting in poor performances. 3D CNNs are computationally heavy and are not widely used, while 2D CNNs do not consider multi-resolution processing of images, and only limits itself to the spatial features. Even though 3D-2D CNNs try to model the spectral and spatial features their performance seems limited when applied over multiple dataset. 
Overall a better model is achieved that can classify multi-resolution HSI data with high accuracy. Experiments performed with SpectralNET on benchmark dataset, i.e. Kennedy Space Center, Botswana etc Scenes confirm the superiority of proposed SpectralNET with respect to the state-of-the-art methods.

Dataset : https://rslab.ut.ac.ir/data
