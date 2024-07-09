# SDAE: Selective Deep Auto-Encoder for Unsupervised Feature Selection (AAAI 2024)
Paper link: https://ojs.aaai.org/index.php/AAAI/article/view/29123

## Abstract
In light of the advances in big data, high-dimensional datasets are often encountered. Incorporating them into data-driven models can enhance performance; however, this comes at the cost of high computation and the risk of overfitting, particularly due to abundant redundant features. Identifying an informative subset of the features helps in reducing the dimensionality and enhancing model interpretability. In this paper, we propose a novel framework for unsupervised feature selection, called Selective Deep Auto-Encoder (SDAE). It aims to reduce the number of features used in unlabeled datasets without compromising the quality of information obtained. It achieves this by selecting sufficient features - from the original feature set - capable of representing the entire feature space and reconstructing them. Architecturally, it leverages the use of highly nonlinear latent representations in deep Autoencoders and intrinsically learns, in an unsupervised fashion, the relevant and globally representative subset of features through a customized Selective Layer. Extensive experimental results on three high-dimensional public datasets have shown promising feature selection performance by SDAE in comparison to other existing state-of-the-art unsupervised feature selection methods.

## Environment requirements
* Python 3.9.13
* Tensorflow 2.10.0
* Keras 2.10.0
* Scikit-Learn 1.3.0


## How to Cite
If you find this code useful in your research, please consider citing our work:

Hassanieh, W. and Chehade, A. 2024. Selective Deep Autoencoder for Unsupervised Feature Selection. Proceedings of the AAAI Conference on Artificial Intelligence. 38, 11 (Mar. 2024), 12322-12330. DOI:https://doi.org/10.1609/aaai.v38i11.29123.

## Contacts
Wael Hassanieh - waelh@umich.edu, Abdallah Chehade - achehade@umich.edu
