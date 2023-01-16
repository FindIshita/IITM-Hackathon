# IITM-Hackathon

## Problem Statement

Concrete cracking is a major issue in Bridge Engineering. Detection of cracks facilitates the design, construction and maintenance of bridges effectively.

## Dataset Link

 https://cutt.ly/PS_1_dataset
 
## Deep Learning framework:
Tensorflow has been used to build the model in this project. We have used the transfer learning technique with MobileNet being the backbone model. The last two layers of the pretrained model has been removed and a softmax layer has been added for classification in between two classes, Crack Detected and Crack Not Detected.
 
## Evaluation Matrics

* Precision : 0.9999573826789856
* Recall : 0.9999574422836304
* F1 Score : 0.9999573826789856

## Plots

![precision](https://user-images.githubusercontent.com/87298712/212745294-a5399c24-c80b-44a4-a8fd-a25571b73ee6.jpg)

![recall](https://user-images.githubusercontent.com/87298712/212745369-a61ad474-3237-43f9-942d-ad1ca1986a34.jpg)

![f1](https://user-images.githubusercontent.com/87298712/212745228-35292d78-a233-4a62-afa8-79c341f936d7.jpg)

## Prediction

![predict](https://user-images.githubusercontent.com/87298712/212745341-1b03244b-5523-46da-81c6-2baff55a651f.jpg)
