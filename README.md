This is a code that classificates an image as a cat or a dog.

For the moment, it is unfunctionnal. A fix will be made soon.

The way it works is:
  It imports the following libraries:
    os, ImageDataGenerator from tensorflow.keras.preprocessing.image, Sequential from tensorflow.keras.models and all of the following; Conv2D, MaxPooling2D, Flatten, Dense, Input from tensorflow.keras.layers

  It uses images from a folder (supposedly should be with the main file) to train and verify itself. It then shows its output, the true class of the image and the image itself.

  After that is done, it saves the model as a separate file for potential use in other projects.

Everything is done within the confines of PyCharm on Python version 3.12
