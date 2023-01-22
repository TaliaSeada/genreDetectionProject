# Genre Detection Project
Predicting Song Genres using Machine Learning and Convolutional Neural Networks.  

In this study, we present a method for predicting the genre of a given song using convolutional neural networks (CNNs). Music genre classification is a 
challenging task due to the complex and subjective nature of music. 
However, it is an important problem with many practical applications, such as music recommendation systems and playlist generation. To address this problem, 
trained a CNN model on a dataset of songs labeled with their corresponding genres. Our model achieved an impressive accuracy of 86% on the test set,
demonstrating the effectiveness of CNNs for music genre classification.

For this project, we sought out data that was not overly simple and that could be processed in multiple ways. We chose to work with music data because it 
can be processed directly from the audio files and also using features extracted from the audio. After searching for datasets, we came across the FMA
repository which contained a large amount of song data in the form of both audio and extracted features such as chromagram and spectral centroid.
While we did not have time to train on raw audio, we were able to achieve good results using only the extracted features. 

We found that using deep learning methods yielded better results than using traditional machine learning methods for this complex problem. During the 
fine-tuning process, we experimented with altering the network structure by adding or removing layers. We observed that the imbalanced nature of the 
data greatly impacted the results. To address this, we attempted to balance the data and found that it significantly improved the accuracy of our networks. It 
is possible that with more data for under-represented genres, the models would perform even better without the need for manual data balancing.

Results: </br>
The model that performed the best on the test set achieved a success rate of 89.5%. It was evident that by balancing the data and implementing 
regularization techniques, the model's performance was improved.

![image](https://user-images.githubusercontent.com/78349342/213909186-c40d1694-bff5-46ae-8602-3803630e663f.png)

![image](https://user-images.githubusercontent.com/78349342/213909194-55b9244e-86be-4b7a-aea4-3284358eb3ba.png)

![image](https://user-images.githubusercontent.com/78349342/213909173-0c429a53-027d-47a8-a676-de0d132fa45d.png)
