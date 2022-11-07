#  Is a patient falling from the bed or not?

- This project classifies patients falling from the bed or not (binary classification) by using deep learning models (ResNet) and fast.ai library. 

- This project used DuckDuckGo to search for images of "a patient falling from the bed photos" and "a patient in the bed photos" and saved them to this repository.
  - Data before cleaning: falling_or_not-before_correction/
  - Source code of Data Cleaning: https://colab.research.google.com/drive/1nHBV4XItcmBJf0S8EcL62nmqHuoKq0jy?usp=share_link
  - Data after cleaning (by human(myself)): falling_or_not-after-correction/

- This project is based on the project 'Is it a bird? Creating a model from your own data'(https://www.kaggle.com/code/jhoward/is-it-a-bird-creating-a-model-from-your-own-data) by Jeremy Howard, which is a resource of the lecture 1. Getting Started of 'Practical Deep Learning for Coders 2022' course(https://course.fast.ai/).

- **Introduction**:
  When I worked as a Registered Nurse in South Korea, one of my duties was to watch elderly patients not to fall from the bed, which can cause a mild injury up to death. The fall accident can happen anytime while a medical staff is working with other tasks for a while, even though the medical staff has been paying attention to the patient to prevent the fall. There are a lot of ways to prevent a patient's fall, one of them is detecting the patient's movements and alerting medical staff right before or when the patient is about to fall from the bed. This project is based on this concept, which can show the minimal performance.

- **Limitations**: 
  - Data: Some of images of a patient falling from the bed are correctly collected, however, some of them are not. Similarly, some of images of a patient in the bed are not collected correctly.
  - Performance: This project cannot perform an exact prediction on a patient's fall from the bed. 

- **Future Works**:
  - Data: After collecting images, the labels of the images should be reviewed by human or a healthcare providers. 
  - Performance: In the future work, the performance on predicting on a patient's fall from the bed can be imporved by using a multi-class classification, which is classifying a patient right before falling from the bed, falling from the bed, already fallen from the bed, in the bed.

### [Link to the source code of the project]()
