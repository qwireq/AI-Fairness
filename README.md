#  Fair Loss with Benefit and Utility functions

## Deep Learning architecture for measuring and mitigating the fairness level of the model prediction trained on an unfair dataset

## Description
The script trains a neural network with fairness constraint injection. The fairness is based on the “Benefit” and “Utility” notions taken from the field of mathematical economics. Using these notions we could estimate the “degree of fairness” of some resource distributed among different classes (for example, amnesty). The software is tested using the COMPAS recidivism dataset.

Using the tau variable the user could control the degree of inequlity, while variable alpha controls the rate of inequality drop.

## How to run:
The script will ideally work in Google Colab notebook, however, it is also could be run on different platforms just some lines of code connected with Google Colab should be removed, and the path to the folder with the dataset should be changed. The user just needs to run the script, the COMPAS dataset will be downloaded automatically.

## Dependencies:
Anaconda, Python 3.6, PyTorch, NumPy, OS, SYS, Pandas, Sklearn, Random, URLLib, Keras

## Author:
  Dias Issa,
  Artificial Intelligence and Machine Learning Laboratory (AIM Lab, https://slsp.kaist.ac.kr/xe/), 
  School of Electrical Engineering,
  Korea Advanced Institute of Science and Technology (KAIST),
  Daejeon, Korea,
  dias.issa@kaist.ac.kr;

## Used material:
Dataset generation code was taken from the following repository: 
https://github.com/mbilalzafar/fair-classification/tree/master/disparate_mistreatment

  
