# Lung cancer Detection 
- Here we have hundreds of images of lungs which are cancerous as well as non-cancerous.
- These images are 1st labelled manually using a csv file provided in which coordinates of tumorms in the 
image were given and we manullay using those coordinates classified them into cancerous and non-cancerous
and then distributed into test and train set.
- Images are then fitted into convolutional neural network to get accuracy and then validation is performed. 
- After running the model for about 20+20+5 epochs we got a accuracy of 95.5% with validation accuracy of 85%.
Libraries used:
from keras.models import Sequential
from keras.layers import Conv2D
from keras.layers import MaxPooling2D
from keras.layers import Flatten
from keras.layers import Dense
import matplotlib.pyplot as plt
from PIL import Image
from IPython.display import Image
from keras.preprocessing.image import ImageDataGenerator
import numpy as np
from keras.preprocessing import image
