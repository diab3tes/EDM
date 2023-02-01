
# Emotion Detection Using Machine Learning


Emotions Detection is an interesting blend of Psychology and Technology. Emotion detection enables machines to detect various emotions. The technique that helps machines and computers to be capable of detecting, expressing and understanding emotions is known as emotional intelligence. In order to understand and detect emotions, the first and foremost requirement for machine learning models is the availability of a dataset. Here, we will
Emotions Sensor Data Set Contain Top 23 730 English Words Classified Statistically into 7 Basic Emotion Disgust, Surprise ,Neutral ,Anger ,Sad ,Happy and Fear.





## Implementation process:

 - We are using a dataset which contains some text data along with the emotion expressed in a given text which is used as label. Training our data with the given dataset , our objective is to build a model which will predict the emotion of a text with a decent accuracy.


 - This Technology Helps to Build a Companion machines such as Robots, thus Robots Can be Friendly and Have The Ability to Recognize Users Emotions, reply and to Act Accordingly.


 


## TOOLS
- Programming Language: Python.
- Pandas 
- Matplotlib   
- Seaborn   
- Scikit Learn  
- IDE for implementation: Anaconda



## Dataset
Here we have 5517 data as our data set with two column. Column 1 contains the text and column 2 contains the emotion of the text as label. Here our target is to classify a sample text among the 6 emotion classes we used as labels such as Joy, anger, sadness, love, fear and surprise. Here using the CountVectorizer, TfidfVectorizer , we convert the text data into numerical data. After converting to numerical data we run 8 classification algorithm by fitting the data and creating models and checking all their accuracy.
## 
![](https://github.com/diab3tes/EDM/blob/main/Pictures/Dataset.png/234x300?text=App+Screenshot+Here)           |  ![](https://github.com/diab3tes/EDM/blob/main/Pictures/edm_data2.png/234x300?text=App+Screenshot+Here)
:-------------------------:|:-------------------------:


## Classification Algorithms

| Classifier | Test Accuracy     | 
| :-------- | :------- | 
| **Linear SVM** | **`80.37%`** | 
| **Gaussian Naïve Bayes** | **`41.48%`** | 
|**Logistic Regression**  | **`69.86%`** |
|**Decision tree**  | **`82.24%`** |
|**Random Forest**  | **`71.37%`** |
|**Gradiant Bossting**  | **`81.15%`** |
|**Bagging Classifer**  | **`78.26%`** |


## Result & Confusion Matrix

![App Screenshot](https://github.com/diab3tes/EDM/blob/main/Pictures/edm_result.png/468x300?text=App+Screenshot+Here)

