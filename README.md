
## This is the image classification program to train and use a model 

# To work with this file and train your own model you need to import certain libraries:<br/>
<code>import numpy as np 
import tensorflow as tf 
import matplotlib.pyplot as plt 
from tensorflow import keras 
%matplotlib inline 
from tensorflow.keras.datasets import fashion_mnist 
from tensorflow.keras.models import Sequential 
from tensorflow.keras.layers import Dense, Dropout
from tensorflow.keras import utils</code>

## Once you got everything installed, you'll be able to use your dataset to see what you have inside: 

<code>
plt.figure()
plt.imshow(x_train[55])
plt.colorbar()
plt.grid(True)
</code>

![image](https://github.com/user-attachments/assets/a144f04e-6fdb-45fc-8f3d-d4f5d20b21c2)


# Feel free to use it and train it youself 
