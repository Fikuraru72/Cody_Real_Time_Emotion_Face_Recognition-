# Real_Time_Emotion_Face_Recognition

## About
This project identifies emotions on a person's face into 7 categories (neutral, happy, angry, sad, fear, surprise, disgust) in realtime, using deep convolutional neural networks (CNN). The model is trained using [```FER-2013```](https://www.kaggle.com/datasets/msambare/fer2013) and [```CK+```](https://www.kaggle.com/datasets/davilsena/ckdataset/code?datasetId=2820176&sortBy=voteCount) from kaggle and datasets that have been cleaned with casecade face detection. This project use for cody mobile app for journaling and gamification based on emotion.

## Depedencies 
- Python 3.7 or latter
- TesonFlow
- OpenCV
- Keras
- Mathplotlib
- Seaborn
- Sckit-learn

## Data Preperation 
In the data preperation dataset of [```FER-2013```](https://www.kaggle.com/datasets/msambare/fer2013) and [```CK+```](https://www.kaggle.com/datasets/davilsena/ckdataset/code?datasetId=2820176&sortBy=voteCount), face detection is performed using casecade from open cv and haarcascade_frontalface_alt.xml to clean dirty or inappropriate image datasets.

## Dataset 
The dataset uses the previously cleaned FER-2013 and CK+ and optimizes the distribution of the dataset in each category in the train and test data.
### Dataset Distribution
#### Train 
![image](https://github.com/user-attachments/assets/730b181a-a2ed-4037-8836-e7ea5cf92681)

#### Test 
![image](https://github.com/user-attachments/assets/6efebe31-be94-4d33-a255-1bd3e0c19b93)

## Sample Images 
![image](https://github.com/user-attachments/assets/a541ee83-1fea-4f89-b187-9852d2869335)

## Result
### Acuuration over epoch 
![image](https://github.com/user-attachments/assets/48dbf0ac-a8c8-45d8-b944-144e23b3100e)

### Model Accuration
![image](https://github.com/user-attachments/assets/31956b5f-64f9-4ab9-86bf-8d017e2617eb)

### Confusion Matrix 
![image](https://github.com/user-attachments/assets/a91a3e17-0866-483e-9f81-8fbd6ee65499)

### Test Model 
![image](https://github.com/user-attachments/assets/8725796c-d4bd-4a1b-a75c-878219ee5749)

## Usage 
- Clone Repository
  
      git clone https://github.com/Fikuraru72/Cody_Real_Time_Emotion_Face_Recognition-.git
      cd Cody_Real_Time_Emotion_Face_Recognition-
- If wanna clean dataset run file ```clean_datase.ipyb``` for data preporation
- If wanna run train model run file '''cody.ipyb''' for the main proggram

