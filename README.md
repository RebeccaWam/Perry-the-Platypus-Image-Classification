# Perry-the-Platypus-Image-Classification
Image classification using the Perry the Platypus dataset from Kaggle.

Done by Rebecca Wam and Megan Michael

# Areas of Improvement
From Professor Kevin Gold
- This project is a struggle because of the small training data size.
- Could tinker with the parameters of the CNN model, since it's not even improving in training loss as you train, especially learning rate and batch size (both of which were left at their defaults). In general, networks should be able to at least overfit the training data, or else something's not set right.
- In general, you can only support more parameters to learn with more training data.  So probably, the CNN is too ambitious in how deep it is; there just isn't the data to support learning a complex model.  This is especially true because the key feature, the brown hat, has a good chance of being recognized by something simple like a "brown blob detector."  But if the network's too complex, it may not find a simple solution without a lot of data.
- Could make the heatmap code more comprehensible.
- Sometimes it makes sense to perform "early stopping" where you stop at the point in training where validation loss starts getting worse (because of overfitting).  It looks like this might have helped your VGG16 model.
- Could take more steps to get the CNN working instead of leaving it in its initial nonfunctional state.


