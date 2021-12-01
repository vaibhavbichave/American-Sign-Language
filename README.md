# American Sign Language 

## Table of Content
  * [Introduction](#introduction)
  * [Motivation](#motivation)
  * [Installation](#installation)
  * [Directory Tree](#directory-tree)
  * [Result](#result)
  * [Future scope of project](#future-scope)


## Introduction
American Sign Language (ASL) is a complete, complex language that employs signs made with the hands and other movements, including facial expressions and postures of the body. It is the first language of many deaf North Americans, and one of several communication options available to deaf people. ASL is said to be the fourth most commonly used language in the United States.

## Motivation
Sign language is based on the idea that sight is the most useful tool a deaf person has to communicate and receive information. Thus, American Sign Language uses hand shape, position, and movement; body movements; gestures; facial expressions; and other visual cues to form its words. 

## Installation
The Code is written in Python 3.6.10. If you don't have Python installed you can find it [here](https://www.python.org/downloads/). If you are using a lower version of Python you can upgrade using the pip package, ensuring you have the latest version of pip. To install the required packages and libraries, run this command in the project directory after [cloning](https://www.howtogeek.com/451360/how-to-clone-a-github-repository/) the repository:
```bash
pip install -r requirements.txt
```

## Directory Tree 
```
├── images
│   ├── amer_sign2.png
|   ├── amer_sign3.png
|   ├── american_sign_language.PNG
|   ├── test1.jpeg
|   ├── test2.jpeg
├── input
│   ├── sign_mnist_test.csv
│   ├── sign_mnist_train.csv
├── model
│   ├── SVM_model
│   ├── forest_model
│   ├── kneighbors_model
│   ├── logistic_model
│   ├── naive_bayes_model
│   ├── tree_model
├── README.md
├── Sign Language MNIST.ipynb
├── Testing.ipynb
├── requirements.txt

```

## Technologies Used

![](https://forthebadge.com/images/badges/made-with-python.svg)

[<img target="_blank" src="https://upload.wikimedia.org/wikipedia/commons/3/31/NumPy_logo_2020.svg" width=200>](https://numpy.org/doc/) [<img target="_blank" src="https://upload.wikimedia.org/wikipedia/commons/e/ed/Pandas_logo.svg" width=200>](https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.html)
[<img target="_blank" src="https://upload.wikimedia.org/wikipedia/commons/8/84/Matplotlib_icon.svg" width=100>](https://matplotlib.org/)
[<img target="_blank" src="https://scikit-learn.org/stable/_static/scikit-learn-logo-small.png" width=200>](https://scikit-learn.org/stable/) 
[<img target="_blank" src="https://www.vectorlogo.zone/logos/opencv/opencv-icon.svg" width=100>](https://opencv.org/) 

## Result
<br>

||ML Model|	Train Accuracy|Test Accuracy|
|---|---|---|---|
1	|Support Vector Machine	| 1.000 | 0.854 |
2	|K-Nearest Neighbors    | 0.999 | 0.815 |
3	|Random Forest	        | 1.000 | 0.805 |
4	|Logistic Regression  	| 0.999 | 0.685 |
5	|Naive Bayes	          | 0.797 | 0.630 |
6	|Decision Tree          | 0.995 | 0.431 |
<br>

## For Training Sample 

Actual Label : D
<br>
![image](https://user-images.githubusercontent.com/79131292/144254545-9ac7145f-42fe-4719-9a46-f4ce0cd576d5.png)

## For Testing Sample 

Actual Label : C
<br>
Predicted Label : C
<br>
![image](https://user-images.githubusercontent.com/79131292/144255277-6f2eb1e0-3817-4c83-9c95-d2fa77323841.png)


Actual Label : A
<br>
Predicted Label : A
<br>
![image](https://user-images.githubusercontent.com/79131292/144255493-5212f7e5-3a59-4388-85ca-635670e0388b.png)

## Future Scope
* Front-End 
* Use multiple Algorithms
* We can develop a complete product that will help the speech and hearing impaired people, and thereby reduce the communication gap.
