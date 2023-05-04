# Exploring-the-MLP-Mixer-Architecture for Image Classification: Performance Evaluation, Tuning, and Ablation Study on MNIST Dataset

This repository contains the code and research paper for the research I conducted titled: "Exploring the MLP-Mixer Architecture for Image Classification: Performance Evaluation, Tuning, and Ablation Study on MNIST Dataset".


# Introduction 

The research paper "MLP-Mixer: An all-MLP Architecture for Vision" proposes a novel approach to computer vision tasks using only multi-layer perceptrons (MLPs). In this study, I have reproduced and analyzed the MLP-Mixer architecture proposed in the paper, with a focus on image classification using the MNIST dataset. I have then compared the performance of the MLP-Mixer model with CNN and simple MLP baselines, and conduct an ablation study to determine the impact of different components of the MLP-Mixer model.


# Contents

All of the code used for the implementation, training, and evaluation of the MLP-Mixer and baseline models is included as a Jupyter Notebook (.ipynb) file. This notebook was run on Google Colab Pro, which provided additional computational resources for the training process. The code is included in the repository as mlp_mixer_study.ipynb file 

# Results

The experiments demonstrated that the MLP-Mixer model outperformed the baseline models (MLP and CNN) on theMNIST dataset, achieving an accuracy of 97.79% with the best hyperparameters: a patch size of (14, 14), a dimension of 128, and 10 layers. This indicates that the MLP-Mixer architecture is a promising approach for image classification tasks. The ablation study revealed the significance of both token and channel mixers in the MLP-Mixer architecture. Removing either led to a decrease in model performance, with the channel mixer having a more pronounced effect on the results.

# Conclusion

Hence, the experiments show that the MLP-Mixer model outperforms the CNN and simple MLP baselines, achieving state-of-the-art performance on the MNIST dataset. The ablation study reveals that both components of the MLP-Mixer model, channel mixing layer and token mixing layer, contributes towards the improvement of model's performance.

# Code Citation 

The code for loading MNIST dataset and to train and validate a simple MLP model was referred from : https://github.com/CSCfi/machine-learning-scripts/blob/master/notebooks/pytorch-mnist-mlp.ipynb 


