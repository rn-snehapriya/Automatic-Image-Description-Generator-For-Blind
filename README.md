# Automatic-Image-Description-Generator-For-Blind

This project generates description about an image which is very much useful for visually impaired people where image descriptions can be read out, enabling them to get a better sense of their surroundings. 

### Description of the Project:
- Initially all the required libraries of Tensor Flow and others are imported.
- Then the dataset containing the images and their respective captions are loaded.
- Then the dataset is divided into train, test data. Here we can give any new image as testing as well.
- Then loading 50 layer Residual Network Model and getting the summary of the model.
- Then the image is preprocessed, where all the images are resized to same size to have consistency in the images.
- Then loading image_id and respective caption in a dataframe.
- Then loading all captions and split each captions stored in 'sentences' and storing them in 'words' as list of list.
- Then the captions are padded.
- Then the images, captions are all fitted into a LSTM model.
- Finally with the model, one can generate the caption/description of any image.

Dataset: https://www.kaggle.com/datasets/shadabhussain/flickr8k
