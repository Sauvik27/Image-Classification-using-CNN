# Object-Classification
Multiclass classification of images using CNN in TensorFlow2.2.0 and Keras.

* Requirement :
  *  Tensorflow2.0
  *  Keras
  *  Matplotlib

Abstract:
Object classification is the way we can detect various objects with the help of deep learning, this can be helpful when we take a picture and the machine tries to detect and classify the object where all the work is done by the machine rather than having a human who detects and classify the objects. Traditional object detection methods are built on handcrafted features and shallow trainable architectures. With the rapid development in deep learning, more powerful tools, which are able to learn semantic, high-level, deeper features, are introduced to address the problems existing in traditional architectures. 


Dataset:
The tiny images dataset is a collection of 32 × 32 color images obtained by searching various online image search engines for all the non-abstract English nouns and noun phrases in the WordNet lexical database. Each image in the dataset has a very noisy label, which is the search keyword used to find it. For supervised tuning, we use the CIFAR-10 dataset, which is a labeled subset of the 80 million tiny images, containing 60,000 images. It contains ten classes: airplane, automobile, bird, cat, deer, dog, frog, horse, ship, and truck. Each class contains exactly 6,000 images in which the dominant object in the image is of that class.


Here we get an accuracy of 86.73% in the train set.
& accuracy of 75.85% in the test set.
Also, another point to be noticed is that the results on the training set are a bit better than the results on the test set, which indicates that the model might be over-fitting a bit.
