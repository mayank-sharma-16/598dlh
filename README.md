Based on the paper: https://academic.oup.com/bioinformatics/article/36/4/1279/5569881

### Summary

This notebook successfully replicates the paper *DeepMSPeptide: peptide detectability prediction using deep learning* (2020), which trains a convolutional neural network on amino acid sequences in protein samples to predict the intrinsic detectability of peptides [3]. This approach outperforms all previous models across most statistical metrics, including those approaches that use physiochemical properties. After validating the results of the paper, this notebook performs ablation experiments to identify the impacts of different parts of the model. The original authors uploaded code to https://github.com/vsegurar/DeepMSPeptide. 

CS 598 - Deep Learning for Healthcare, Team 155 - Mayank Sharma

This notebook requires no additional installations or instructions. Simply run it in Google Colab as is. This can run in Jupyter as well, although configuration may be needed to adjust to local environments.

Python version used is 3.10.12
The requirements.txt file is included in the repository in case of future version conflicts in Google Colab. The default installation for requirements is

``` pip install -r requirements.txt ```