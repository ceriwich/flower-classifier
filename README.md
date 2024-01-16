# flower-classifier
Web application employing a CNN for image classification of flowers for a limited number of species.

Code taken from https://thecleverprogrammer.com/2020/11/24/flower-recognition-with-python/

Data taken from https://www.kaggle.com/datasets/alxmamaev/flowers-recognition?resource=download

The data contains 4242 images of flowers divided into 5 classes: chamomile, tulip, rose, sunflower, and dandelion.

The collection of images is based on scraped data from flickr, google images, and yandex images

Model was built, compiled, and trained according to the tutorial by TheCleverProgrammer. The main deviation is that the model was trained over 4 iterations of 16 epochs. Meaning that there were 4 different calls of the fit() function. Before and after the set of epochs, the model was loaded, then saved back to the file `flowerModel.keras`. 
