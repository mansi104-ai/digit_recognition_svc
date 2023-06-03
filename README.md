# digit_recognition_svc
The Code has two parts:

1) Taking random integers using randint and recognize the number
2) Drawing the tkinter page and taking input from the user to recognize the number using KNN and SVM classification

To access the first part , the code is written in file named SVC.ipynb which shows 4 randomly drawn number at the instance,
using SVM library the number will be recognized and the predicted label will be shown!

To access the second part , the code is written in file named in GUI.ipynb and SVM_MODEL(TRAINING). In GUI.ipynb , tkinter has been used to take the input 
from the user and using the training models stored in knn_model.gzip , the digit is recognized.

All the training and testing models from mnist dataset have been added.
Though the code is used to predict single digits only but work going on for multiple digits as well!
