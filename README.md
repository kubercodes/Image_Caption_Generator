
# Image Caption Generator

Project Information
The objective of the project is to predict the captions for the input image. The dataset consists of 8k images and 5 captions for each image. The features are extracted from both the image and the text captions for input. The features will be concatenated to predict the next word of the caption. CNN is used for image and LSTM is used for text. BLEU Score is used as a metric to evaluate the performance of the trained model.

Download link: https://www.kaggle.com/adityajn105/flickr8k

Environment: Kaggle

Libraries
numpy
matplotlib
keras
tensorflow
nltk
Neural Network
VGG16 Network
CNN-LSTM Network

# Results

BLEU-1 Score: 0.546204 BLEU-2 Score: 0.320844

![image_1](https://user-images.githubusercontent.com/72246104/159900922-c4130869-bba4-44af-81a2-968ae02b7a40.PNG)

![image_2](https://user-images.githubusercontent.com/72246104/159900968-ec103d85-4ffd-4e64-9cb1-783c1399c40e.PNG)
![image_3](https://user-images.githubusercontent.com/72246104/159900979-a504abdd-b91a-41ce-a361-4efe5a08b07d.PNG)

![image_4](https://user-images.githubusercontent.com/72246104/159900988-cd3c2f0b-3796-46a1-b4e1-8f61dd56a6ab.PNG)
