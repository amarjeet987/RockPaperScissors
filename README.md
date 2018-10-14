# RockPaperScissors

## Files :

### **1)** **trainer.ipynb**
This file contains the CNN model, and code for training and testing the model, after which it saves the model to a file named __model.h5__, which we will be using later for prediction.

**The model :**
````python
Input -> Conv2D -> MaxPool2D -> Conv2D -> MaxPool2D -> Conv2D -> MaxPool2D -> Flatten -> Dense -> Dropout -> Dense(Output layer)
````


### **2)** **game.ipynb**
It contains the openCV implementation of real-time data collection for training and testing, as well as the logic for rock, paper, scissors as well. 

## How to proceed :
**1)** After cloning the repository, open and run the __game.ipynb__ file.
