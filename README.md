# flower-classifier-transfer-learning

This notebook is best used on google colab for a free GPU. 

It runs through how to create a very accurate flower classifier using transfer learning & training data augmentation on tensorFlow.  

### Steps

1. We download a flowers dataset and mobileNetv2 from google.

2. Next we split the dataset into training and validation sets.

3. We create a generator that will randomly rotate, zoom, flip and shift the training data as it goes into the model for training.

4. We initialise a new model by creating a softmax layer at the end of mobileNet with the number of classes in the flower dataset.

4. We train the model.

5. Plot the results.

