# Bangla-Sign-Language-Detection 
Bangla Sign Language Recognition
Bangla sign recognition system is developed based on a deep learning approach named LSTM. As a feature extractor, Mediapipe Holistic is also used in this system. This system is able to work on static and dynamic both types of gestures and recognize simple and complex signs.

**Mediapipe Holistic**
Mediapipe Holistic extracts feature from a person's face, body, hand, and finger positions. Mediapipe Holistic uses specific points to monitor our facial expressions and hand movements. Mediapipe Holistic generates landmarks to detect the face, body, and hand. As a result, redundant information is automatically removed from the picture or frame of a video. This system saves space because it only requires a few points to be saved. It does not introduce displacement due to lighting or distance.

 

 

**LSTM Architecture**
Recurrent Neural Networks in particular may learn long-term dependencies. Unlike conventional convolutional neural networks, LSTM has backpropagation. A forget gate, a cell, an input gate, and an output gate make up a basic LSTM unit. Three gates regulate the flow of data into and out of the cell, which also has a long-term storage capacity. LSTMs do a great job of categorizing, evaluating, and generating predictions based on time series data because key events in a time series may have unexpected latency. In Bangla sign language, a complex sign consists of several patterns and gestures. There is almost always a connection between recent and previous moves. In order to remember the previous one for a while, the LSTM architecture was used.


![image](https://github.com/user-attachments/assets/c3a30a65-17f0-4500-b317-33b14df10cb0)

 



![Uploading image.png…]()


**Work Procedure**



![Uploading image.png…]()

