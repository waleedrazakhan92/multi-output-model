# multi-output-model
An implementation of a Multi-Head model with one branch for an Autoencoder training and the other for classification. Effective in situations where you need multiple models for the same dataset. 
Training both the autoencoder and the classifier at the same time, save both computational cost and the time to train two models. 
For experimentation the *Intel Image Classification* dataset is downloaded, via code, in the notebook. But if you find the link broken, you can download the same dataset from https://www.kaggle.com/puneet6060/intel-image-classification .
For faster training, please make sure that the *runtime* is set to "GPU".

Please see the .ipynb file for model training code. 

# Instructions
1. Place the dataset and set the path to variable "path_dataset".
2. Set the batch size to a value that easily fits in the gpu memory.  
3. Set the image size to a desired value. Make sure that it is in the power of 2, i.e (64,128,256,512).
4. Start the training.

**Note** All the code is tested in google colab with both tensorflow 1.14 and 2.0. 
