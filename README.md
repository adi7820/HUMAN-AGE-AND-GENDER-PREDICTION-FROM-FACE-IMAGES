# HUMAN-AGE-AND-GENDER-PREDICTION-FROM-FACE-IMAGES

# INTRODUCTION & MOTIVATION
Age and gender data are critical for a variety of real-world applications, including social understanding, biometrics, identity verification, video surveillance, human-computer interface, electronic customers, crowd behaviour analysis, online advertising, item recommendation, and many others.
Despite its widespread use, accurately estimating age and gender from face photographs is a difficult problem to solve, owing to the numerous sources of intra-class variances in people's facial images, which limits the applicability of these models in real-world applications.
From face photos, we offer a deep learning framework for simultaneously predicting age and gender. We employ an attentional convolutional network based on the hypothesis that specific local regions of the face provide more distinct signals regarding an individual's age and gender (for example, a male's beard and moustache, and wrinkles around the eyes and mouth for age).
We utilise a single model with a multi-task learning technique to simultaneously predict both gender and age bucket since guessing age and gender from faces is similar. Also, because we can better estimate someone's age if we know their gender, we supplement the age-prediction branch with the projected gender output.
SWISH activation function by Google’s brain team will be used for further improvement in the accuracy of the model. Swish has properties One-sided confinement at zero, smoothness, and non-monotonicity that can play a role Observed effectiveness of swish and similar activation functions.
Motivation: The main motive behind to work on this project to get a first-hand experience in deep learning project in image and video processing and grasp as much knowledge as possible and learn so many amazing things via this project.

To execute this application we need some pre-requisites like required enviorment to be setup and necessary libraries must be installed.
About enviorment:
To run the following codes we need a platform which can run .ipynb files like Jupyter and Google Colab.
Enviorment: PYTHON 3.6+

Required Libraries need to be installed:
- Numpy
- Pandas
- Seaborn
- Tensorflow
- tqdm
- PIL
- OpenCV
- tkinter
How to run ?
1. IVP 4.0, 4.1, 4.2 and 4.3 are used to train different model of age and gender.
2. Keep all the trained models (.h5) in one place.
3. Where GUI 3.1.py or Final Run GUI.ipynb is an UI execution file.
4. Through user interface we can upload and generate the desired output.
exe file : dist/GUI.exe

DATASET: https://susanqq.github.io/UTKFace/

# OUTPUT
![image](https://user-images.githubusercontent.com/25850136/188214379-af0750da-5bf2-4fc7-986f-a5bae04d4013.png)
![image](https://user-images.githubusercontent.com/25850136/188214451-9b60171e-ce73-4026-bb43-b43e0fa26c72.png)
### Fig1. Prediction results of face image using both SWISH and ReLU (Actual Age: 31)

![image](https://user-images.githubusercontent.com/25850136/188215347-f3d3fc3c-fa92-4a62-a2f7-0e452a0027ab.png)
### Fig2. Ensemble Model

![image](https://user-images.githubusercontent.com/25850136/188215518-6d607cb5-30f7-4f63-830b-d30bf14be9b6.png)
### Fig3. Accuracy Graph
![image](https://user-images.githubusercontent.com/25850136/188215700-d2072936-19ca-44c2-98a3-beb8dded88b3.png)
### Fig4. Loss Graph

![image](https://user-images.githubusercontent.com/25850136/188215845-6bcf2e42-ad2f-4507-85b4-04e269b38e8c.png)
### Fig5 Prediction Image

# RESULT

In this project, we offer a multi-task learning framework for predicting age and gender from face photos at the same time. Our model is based on ensemble method, model was trained and evaluated using the UTK-Face dataset, which contains a huge number of faces of various ages, genders, and races. We show that the ensemble model's prediction accuracy (for both age and gender prediction tasks) outperforms the separated models in experimental experiments.
We also showed that by choosing the right activation function make effect on the result of prediction and can improve accuracy.
Recent deep neural network models can accurately evaluate human face photos, recognising the person's age, gender, and emotional state, among other things. These models, however, typically operate like black boxes due to their complicated non-linear structure, and it was unclear until recently why they arrived at their predictions.
On the tough UTK-Face dataset, we tested different image pre-processing, model initialization, and architecture options and explained how they affect performance. The UTK-Face data set, we achieve state-of-the-art gender categorization performance using a mix of modest pre-processing techniques.



https://user-images.githubusercontent.com/25850136/188217749-08ba2194-4848-4df3-a231-5c5f8af1ee9d.mp4


