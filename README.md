## Deep Learning Image Classification Project on Brain Cancer

## Case Description
The purpose is to train a model to classify X-ray image of three brain cancers. They are brain glioma, brain Menin, and brain tumor. For each of the brain cancers, there are 2004 images to train the model.

## Technology: Python, Tensorflow, Keras
## Data Science Method: Image Display, Deep Learning Modeling, Confusion Matrix, Multi-class Evaluation.


## The first 40 sample images from training files

![image](https://github.com/user-attachments/assets/b731748f-e4d9-45bb-986b-56814ec14c4a)



## Deep Learning code walks through:
1.	Split the train image files into training set and validation set with validation split as 20%. 
2.	The model is trained based on a pretrained model called ResNet50. 
3.	The architect: it contains s hidden layers. Each of them would have 100 neurons and a 50% dropout.
4.	Set up early stopping and check pointer and include it in callbacks.
5.	Set step per epoch as 1 and epochs as 8. 


## Observation Vs Predictions of 40 images from the testing files

![image](https://github.com/user-attachments/assets/f7697f2c-4d2b-451d-aa58-6bdddc68e921)


## Model Evaluation
1.	Training accuracy was 77%, and validating accuracy was 75%, and the testing accuracy was 73.9%. The model is slightly overfit and has an acceptable accuracy.
2.	The model is good at predicting brain tumor over brain glioma and brain menin.

![image](https://github.com/user-attachments/assets/a5f923a3-33c6-432b-bd9a-9c3e53b8aca9)

![image](https://github.com/user-attachments/assets/9b188057-493f-4417-8326-acc3b25bc48e)

## The End
## Thanks for reading
