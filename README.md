#  Is a patient falling from the bed or not?

- This project classifies patients falling from the bed or not (binary classification) by using deep learning models (ResNet) and fast.ai library. 
  - [Project(1): How to Download Data from Internet Search to local computer](https://github.com/positive235/patient-falling-binary-classification/blob/main/Is_patient_falling_how_to_download_data.ipynb) 
  - Project(2): Is a Patient Falling from the Bed or not? - Before Data Cleaning (**In Progress**)
  - Project(3): Is a Patient Falling from the Bed or not? - After Data Cleaning (**In Progress**)
  
- This project used DuckDuckGo to search for images of "a patient falling from the bed photos" and "a patient in the bed photos" and saved them to this repository.
  - Data before cleaning: [falling_or_not-before_correction/](https://github.com/positive235/patient-falling-binary-classification/tree/main/falling_or_not-before_correction)
  - [Source code of Data Cleaning](https://colab.research.google.com/drive/1nHBV4XItcmBJf0S8EcL62nmqHuoKq0jy?usp=share_link)
  - Data after cleaning (by human(myself)): [falling_or_not-after-correction/](https://github.com/positive235/patient-falling-binary-classification/tree/main/falling_or_not-after_correction)
  - [Test Set Data (chosen from falling_or_not-after-correction/)](https://github.com/positive235/patient-falling-binary-classification/tree/main/test_set)
    - [Source code of setting test set from cleaned data](https://colab.research.google.com/drive/1uFIkJTM9C4O_InxwKopGQhtCiEHj24ny?usp=share_link)
  - Data excluding Test set data (**In Progress**)
    - 'Data before cleaning' excluding images in test_set/ folder
    - ['Data after cleaning' excluding images in test_set/ folder](https://github.com/positive235/patient-falling-binary-classification/tree/main/falling_or_not-after_correction_training) 

- This project is based on the project 'Is it a bird? Creating a model from your own data'(https://www.kaggle.com/code/jhoward/is-it-a-bird-creating-a-model-from-your-own-data) by Jeremy Howard, which is a resource of the lecture 1. Getting Started of 'Practical Deep Learning for Coders 2022' course(https://course.fast.ai/).

- **Introduction**:
  When I worked as a Registered Nurse in South Korea, one of my duties was to watch elderly patients not to fall from the bed, which can cause a mild injury up to death. The fall accident can happen anytime while a medical staff is working with other tasks for a while, even though the medical staff has been paying attention to the patient to prevent the fall. There are a lot of ways to prevent a patient's fall, one of them is detecting the patient's movements and alerting medical staff right before or when the patient is about to fall from the bed. This project is based on this concept, which can show the minimal performance.

- **Limitations before data cleaning**: 
  - Data: Some of images of a patient falling from the bed are correctly collected, however, some of them are not. Similarly, some of images of a patient in the bed are not collected correctly.
  - Performance: This project cannot perform an exact prediction on a patient's fall from the bed. 

- **Improvements after data cleaning**:
  - Data: After collecting images, the labels of the images were reviewed by human (myself).
  - Performance: (**In Progress**)
  
- **Note**: How to Remove All .svn Directories (https://stackoverflow.com/questions/1294590/how-to-remove-all-svn-directories-from-my-application-directories)
```
find . -name .svn -exec rm -rf '{}' \;
```
