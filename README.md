# RockPaperScissors

## Files :

### **1)** **trainer.ipynb**
This file contains the CNN model, and code for training and testing the model, after which it saves the model to a file named ___model.h5___, which we will be using later for prediction.

**The model :**
````python
Input -> Conv2D -> MaxPool2D -> Conv2D -> MaxPool2D -> Conv2D -> MaxPool2D -> Flatten -> Dense -> Dropout -> Dense(Output layer)
````


### **1)** **game.ipynb**
It contains the openCV implementation of real-time data collection for training and testing, as well as the logic for rock, paper, scissors as well. 
