# Nebula Classification using MobileNetV2

### The model is based on the MobileNetV2 architecture, a lightweight convolutional neural network that has been pre-trained on a large image dataset. 

### The main tasks performed by the code include:

1. Importing necessary libraries, including TensorFlow, Keras, Pandas, NumPy, and Matplotlib.
2. Loading and preprocessing image data using the ImageDataGenerator for training and validation.
3. Defining the mobile_model, which includes a MobileNetV2 base with additional fully connected layers for classification.
4. Compiling the model with categorical cross-entropy loss and Adam optimizer.
5. Training the model on the nebulae dataset for 100 epochs and recording the training history.
6. Plotting the training and validation accuracy and loss over epochs for performance analysis.
7. Implementing image predictions on new, unseen nebula images using the trained model.
8. Displaying the test image along with the predicted class label.

The model's goal is to accurately classify different types of nebulae, showcasing the power of deep learning in astronomy and astrophysics research. Feel free to explore the code, use the dataset for your projects, and make improvements to the model's architecture or training process.

The final accuracy of the model on the validation set is approximately 78.57%



```
project
│   README.md
│   nebula.ipynb   
│
└───data
│   │   bubble
│   │   crab
│   │   dark
│   │   helix
│   │   planetary
│   │   ring
│   │   tarantula
```




![Untitled design (1)](https://github.com/allelbhagya/nebula/assets/80905783/b8d0870c-cb80-4003-9304-9906a3b7066e)
