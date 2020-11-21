# CNN with Spatial Pyramid Pooling application in dynamically recognizing human gestures

**The Final Report is in `COMP_562_Final_Project.pdf`.**

## Abstract
In this paper, we propose a new approach to recognize handpose (rock, paper, scissors) which has a better accuracy andsmaller model size compared to existing models. We designa CNN model with 5 layers, specially designed kernel size tobest fit the image in our dataset, and a Spatial Pyramid Poolinglayer. We explicitly test the dataset with five different existingmodels representing the latest technology in the field andcompare the result with our approach. The result shows a greatprecision, efficiency, and compatibility in terms of testing accuracyand model size. The trained model is used to applied inthe computer camera and can detect hand shape in a real-timeenvironment.

## Structure
All image used in the paper are in img/ folder.

All model training results and model (.pth) are in each folder within data/

The data cleaning and training process can be seen in the jupyter notebook file under data/ folder. The entire training process is done through Google Colab so there are some cells in the .ipynb file with strange code style (ex. "!mkdir ....").

* Notice: Some model exceeds Github's max size, and thus not uploaded in this repo.