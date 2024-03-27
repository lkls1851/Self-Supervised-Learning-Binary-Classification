# Self-Supervised-Learning-Binary-Classification

In this method, we use Resnet-18 backbone for feature extraction and add a projection head on top of encoder. This head will project the extracted features and help in contrastive learning, which is the crux of SSL.
We use CosineEmbeddingLoss as our loss function instead of BCE, because Coosine Embedding focusses more on embedding and contrast based learning. </br>

1. JPG : Directory created which has two sub directories: Positive and Negative
2. Positive : Contains Non Lensed Images
3. Negative : Contains Lensed Images
4. 'encoder.pth' : Trained weights of encoder

</br>
ROC AUC: 0.8823529411764706
