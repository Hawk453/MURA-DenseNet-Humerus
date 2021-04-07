# Code for the Research Paper on Humerus Abnormality Analysis
This repository contains an implementation of the 169-layers Densely Connected Convolutional Networks (DenseNet-169) model for the task of abnormality detection in musculoskeletal Radiographs on MURA dataset.
### Dataset: MURA v1.1
MURA (musculoskeletal radiographs) is a large dataset of bone X-rays.

### Performance of the models
#### MURA-DenseNet-v1.5-Humerus:
Kappa Score: 0.6587347649448636, AUROC: 0.916
<br>
Training on: Epoch: 10, Batch size: 32
<br>
Test accuracy: 0.83333

#### MURA-DenseNet-v1.6-Humerus:
Kappa Score: 0.6736740597878496, AUROC: 0.888
<br>
Training on: Epoch 12[Early Stopping], Batch size: 32
<br>
Test accuracy: 0.83680

#### MURA-DenseNet-v1.7-Humerus:
Kappa Score: 0.6800618238021638, AUROC: 0.911
<br>
Training on: Epoch: 12, Batch size: 32
<br>
Test accuracy: 0.84375

### Citation
@article{rajpurkar2018mura, title={MURA Dataset: Towards Radiologist-Level Abnormality Detection in Musculoskeletal Radiographs}, author={Rajpurkar, Pranav and Irvin, Jeremy and Bagul, Aarti and Ding, Daisy and Duan, Tony and Mehta, Hershel and Yang, Brandon and Zhu, Kaylie and Laird, Dillon and Ball, Robyn L and others}, year={2018} }

@inproceedings{huang2017densely, title={Densely connected convolutional networks}, author={Huang, Gao and Liu, Zhuang and van der Maaten, Laurens and Weinberger, Kilian Q }, booktitle={Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition}, year={2017} }

