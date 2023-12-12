# Fake_News_Detection_Using_Deep_Learning
This is a Jupyter notebook that demonstrates how to use Python libraries and TensorFlow to build a model that can classify news articles as real or fake.

__Data Preparation__:
The notebook shows how to load, merge, clean, and visualize two datasets of real and fake news articles, and how to split them into training and testing sets.

__Model Building:__ The notebook explains how to use an embedding layer and two LSTM layers to create a sequential model that can process text inputs and output a binary prediction.

__Model Evaluation:__ The notebook displays the accuracy and loss curves of the model on the training and testing data, and shows how to generate a classification report and a confusion matrix.

__Model Performance:__


                   precision  recall   f1-score   support

        Fake         0.96      0.75      0.84      5858
        Real         0.78      0.96      0.86      5367

    accuracy                             0.85     11225
    macro avg        0.87      0.86      0.85     11225
    weighted avg     0.87      0.85      0.85     11225

Overall Performance:

![image](https://github.com/mohammedtareeq786/Fake_News_Detection_Using_Deep_Learning/assets/133824825/31a0af6b-d16f-4c6d-8a8f-9ceabaad407b) 

![image](https://github.com/mohammedtareeq786/Fake_News_Detection_Using_Deep_Learning/assets/133824825/1cc56212-db88-435a-ae57-5a4982b26a0e)


Accuracy: The overall accuracy of the model is 85%, which means it correctly classifies 85% of the instances, regardless of the class.

Macro Average: The macro average for precision, recall, and F1-score is around 0.86-0.87, which does not take class imbalance into account.

Weighted Average: The weighted average takes the support of each class into account and is also around 0.85-0.87, indicating consistent performance across classes.

