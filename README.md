# Railway-Track-Fault-Detection-Journal

Accidents due to defective railway lines and derailments are common disasters that are observed frequently in Southeast Asian countries. It is imperative to run proper diagnosis over the detection of such faults to prevent such accidents. However, manual detection of such faults periodically can be both time-consuming and costly. In this paper, we have proposed a Deep Learning (DL)-based algorithm for automatic fault detection in railway tracks, which we termed an Ensembled Convolutional Autoencoder ResNet-based Recurrent Neural Network (ECARRNet). We compared its output with existing DL techniques in the form of several pre-trained DL models to investigate railway tracks and determine whether they are defective or not while considering commonly prevalent faults such as—defects in rails and fasteners. Moreover, we manually collected the images from different railway tracks situated in Bangladesh and made our dataset. After comparing our proposed model with the existing models, we found that our proposed architecture has produced the highest accuracy among all the previously existing state-of-the-art (SOTA) architecture, with an accuracy of 93.28% on the full dataset. Additionally, we split our dataset into two parts having two different types of faults, which are fasteners and rails. We ran the models on those two separate datasets, obtaining accuracies of 98.59% and 92.06% on rail and fastener, respectively. Model explainability techniques like Grad-CAM and LIME were used to validate the result of the models, where our proposed model ECARRNet was seen to correctly classify and detect the regions of faulty railways effectively compared to the previously existing transfer learning models.

Please cite our paper and dataset - 

paper link - https://www.mdpi.com/2673-2688/5/2/24#:~:text=An%20ensembled%20DL%20architecture%2C%20ECARRNet,predictive%20performance%20than%20existing%20SOTA.

Dataset1 - https://www.kaggle.com/datasets/ashikadnan/railway-track-fault-detection-dataset2fastener

Dataset2 - https://www.kaggle.com/datasets/salmaneunus/railway-track-fault-detection

