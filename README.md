Classification problem to clasify whether cell is Infected or Uninfected by malaria. 

The dataset contains 2 folders 
- Infected 
- Uninfected

And a total of 27,558 images with 23,146 and 4,412 images respectively as training and test set.

Originally uploaded on the official NIH Website: https://ceb.nlm.nih.gov/repositories/malaria-datasets/ and was downloaded from https://www.kaggle.com/iarunava/cell-images-for-detecting-malaria.

An accuracy of 96.51% on training set and 94.93% on testing set was obtained over 10 epochs by using Keras ImageDataGenerator for Data Augmentation and preprocessing to specific shape as sizes of images varied.

Training was done on Google Colab with GPU Runtime.

-weights = modelcell.h5

-model = modelcell.json
