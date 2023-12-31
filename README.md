<h1><center>Facial Emotion Recognition</center></h1>

<img width="1440" alt="Screenshot 2023-09-19 at 9 31 19 PM" src="https://github.com/SHANJAY975/Face_Emotion/assets/55045545/c828a9c7-fcea-46ef-938c-9984bea20b19">


**Facial emotion recognition is a cutting-edge technology that uses artificial intelligence and computer algorithms to analyze facial expressions to understand human emotions. Its various uses cut across a range of industries, from improving commercial customer service to advancing the understanding and management of mental illness.**

**Facial emotion detection in the business world can improve customer relations by assessing mood during talks and enabling businesses to customize their responses to customer emotions. It assists in determining user happiness, forecasting consumer behavior, and improving marketing plans.**

**In the realm of mental health, this technology plays a transformative role by assisting clinicians in identifying and monitoring patients' emotional states. It can be used to detect signs of depression, anxiety, or other mental health conditions through subtle facial cues, enabling timely interventions and personalized treatment plans.**

**Facial emotion recognition epitomizes the fusion of AI and human emotions, unlocking a myriad of possibilities to improve our lives, from the commercial realm to the healthcare sector.**

# Getting Started
These instructions will get this model up and running. Follow them to make use of the model to recognize facial emotions using custom images. This model can also be used as facial emotion recognition part of projects with broader applications
# Prerequisites
Install these prerequisites before proceeding-
```
pip install scikit-learn-intelex
```
```
pip3 install tensorflow
```
```
pip3 install keras
```
```
pip3 install numpy
```
```
pip3 install sklearn
```
```
pip3 install pandas
```
```
pip3 install matplotlib
```

# Cloning 
First step is to Clone the repository
```
git clone https://github.com/SHANJAY975/Face_Emotion
```
# Dataset
```
https://www.kaggle.com/datasets/deadskull7/fer2013
```
# Running on Local Machine:
* Navigate to the cloned directory
* Open .ipynb using Jupter lab
  <img width="1153" alt="RUN ALL" src="https://github.com/SHANJAY975/Face_Emotion/assets/55045545/4780ed5e-1229-405b-b2ab-dfe12e751ec2">
* Click cells > Run All

# Running on Intel Devcloud:
* Convert cloned Folder into zip file
* Open Jupter lab in Devcloud
```http://jupyter.oneapi.devcloud.intel.com/```
* Create a new folder
  <img width="1440" alt="Folder" src="https://github.com/SHANJAY975/Face_Emotion/assets/55045545/ecebed2c-e989-4d51-8f46-36a560b51792">

* Upload zip file into the folder
  <img width="1440" alt="Upload" src="https://github.com/SHANJAY975/Face_Emotion/assets/55045545/6dbf5fbc-cff1-40c8-b4f7-075e381a2047">
* Open Terminal
  <img width="1440" alt="Terminal" src="https://github.com/SHANJAY975/Face_Emotion/assets/55045545/0c698529-ed2b-4d6b-9e5a-f92e2c811504">
* Navigate to Created folder
  ```cd <Folder_name>```
* Unzip the uploaded file
  ```unzip Face_Emotion.zip```
* Open Face_emotion.ipynb file
<img width="1440" alt="run" src="https://github.com/SHANJAY975/Face_Emotion/assets/55045545/5b6dac68-c90d-4b43-b93e-2af24839e9ce">

# Visualizing Loss

<img width="545" alt="Screenshot 2023-09-20 at 12 12 09 PM" src="https://github.com/SHANJAY975/Face_Emotion/assets/55045545/c7185d24-3e17-4c6c-a62c-5122cc0ff2a8">

# Visualizing Accuracy
<img width="564" alt="Screenshot 2023-09-20 at 12 13 11 PM" src="https://github.com/SHANJAY975/Face_Emotion/assets/55045545/52348e12-8aa9-41a9-8880-e15570f3e994">

# Getting the Confusion Matrix 
<img width="982" alt="Screenshot 2023-09-20 at 12 12 45 PM" src="https://github.com/SHANJAY975/Face_Emotion/assets/55045545/f3950d49-b145-43da-b210-59f43d6933e1">

# Predictions
<img width="968" alt="Screenshot 2023-09-20 at 12 13 35 PM" src="https://github.com/SHANJAY975/Face_Emotion/assets/55045545/9f3daacf-768f-4cbd-8b21-224c854425d0">

# PreTrained Model 
* To use Pretrained model run the following code
* Importng the Libraries
```import tensorflow as tf
   from tensorflow.keras.models import load_model
```
* Loading the model
```
model = load_model('best_model.h5')
```
* Make predictions using the loaded model
```
predictions = model.predict(sample_data)
```
