# Multi-Label-Attack-Detection-for-Microgrids

This repository contains a multi-label deep learning-based attack detection approach for the AC microgrids distributed control. The test system is a modified IEEE 34-bus distribution system that includes 6 DGs and 9 loads. The DG output voltages, active-reactive power-sharing, and output frequencies are collected as features for attack detection.

InceptionTime and ResNet models are used to design the attack detector. Both feature residual connections are comprised of 1D convolutions and batch normalization. Inception has six residual blocks with max pooling and features a bottleneck layer while ResNet has three residual blocks with no pooling or bottleneck. The residual block layer connects to a global average pooling layer which then feeds to a dense fully connected network. The sigmoid function is employed at the output layer and the nonbinary values are transformed to binary using Matthew's correlation coefficient.

![IEEE34](https://user-images.githubusercontent.com/32277926/123474475-02ad0100-d5c8-11eb-914d-2573dca147bc.png)

![framework_deeplearning](https://user-images.githubusercontent.com/32277926/123473486-a09fcc00-d5c6-11eb-8c85-47ee783a517d.png)

# Citing this repository
Please cite this repository using:

@inproceedings{mohiuddin2021deep,
  title={Deep Learning Based Multi-Label Attack Detection for Distributed Control of AC Microgrids},
  author={Mohiuddin, Sheik and Fung, Sasha and Huang, Yu and Qi, Junjian and Tang, Yufei},
  booktitle={2021 IEEE International Conference on Communications, Control, and Computing Technologies for Smart Grids (SmartGridComm)},
  pages={},
  year={2021},
  organization={IEEE}
}


# Pulications
The following publications out of the IRES-FAU research group used/referred to this repository:
