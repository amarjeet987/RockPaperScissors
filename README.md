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
**1)** After cloning the repository, open and run the __game.ipynb__ file.<br>
**2)** Follow the instructions for training the model, when done, close the file.<br>
**3)** Open the __train.ipynb__ file and start training the model on the dataset, it will take a while, go for a walk or something.<br>
**4)** Feel free to play around with the model, and when done, close the file.<br>
**5)** Open the __game.ipynb__ file, start the game, ENJOY!!!


Check out <a href = "https://drive.google.com/open?id=1FbpNejynJtUHkln9xuOlq8GOvXkLeWJz">this</a> link for the demo to see how it works.
