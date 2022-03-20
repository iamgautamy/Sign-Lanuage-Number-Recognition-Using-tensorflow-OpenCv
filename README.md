# Sign-Lanuage-Number-Recognition-Using-tensorflow-OpenCv
This is a TensorFlow implementation for numbers in sign language identification from scratch using CNN layers.
The model first subtracts the background and uses hand segmentation and contour detection to recognize the signs.
This was made in Tensorflow Version 2.8.0, Python 3.9 under Anaconda Virtual Environment

The model is trained on Several Images created by me .

# Layers Used:
tf.keras.layers.Rescaling(1./255),

tf.keras.layers.Conv2D(32, 3, activation='relu'),

tf.keras.layers.MaxPooling2D(),

tf.keras.layers.Conv2D(32, 3, activation='relu'),

tf.keras.layers.MaxPooling2D(),

tf.keras.layers.Conv2D(32, 3, activation='relu'),

tf.keras.layers.MaxPooling2D(),

tf.keras.layers.Flatten(),

tf.keras.layers.Dense(128, activation='relu'),

tf.keras.layers.Dense(num_classes)

# Accuracy and Confidence of Model
Model shows an approx of 80% accuracy on both training and validation dataset And has mean confidence on faces over 80%
