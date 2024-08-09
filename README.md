# Projet8
The aim of this project (project 8 part 2) is to create a POC on a recent method of anomaly detection on images.

The selected algorithm is FastFlow [(https://arxiv.org/abs/2111.07677)](https://arxiv.org/abs/2111.07677) an unsupervised anomaly detection method on images, as implemented in the anomalib library [(https://anomalib.readthedocs.io/en/v1.1.0/)](https://anomalib.readthedocs.io/en/v1.1.0/)

This algorithm is tested on the BTAD dataset* that can be downloaded from here :
[https://www.kaggle.com/datasets/thtuan/btad-beantech-anomaly-detection](https://www.kaggle.com/datasets/thtuan/btad-beantech-anomaly-detection)

*BTAD : BeanTech Anomaly Detection dataset from :
P. Mishra, R. Verk, D. Fornasier, C. Piciarelli, G.L. Foresti
"VT-ADL: A Vision Transformer Network for Image Anomaly Detection and Localization"
30th IEEE/IES International Symposium on Industrial Electronics (ISIE)
Kyoto, Japan, June 20-23, 2021

## Setup
The [P.O.C. notebook](POC_FastFlow.ipynb) has been made to run on google collab. To do so, save BTAD data on google drive and open the notebook on collab.

By default the data must be saved into a folder named `'/content/drive/MyDrive/OC - Projets/Projet 8/'`. This work_folder can be changed by modifying the first cell of the notebook.

Data can also be obtained directly with the anomalib dataloader, but this relies on the ssl certificate of this site to be up to date, which is not always true.