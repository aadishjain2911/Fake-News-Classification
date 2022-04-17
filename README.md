# Fake-News-Classification
Content based Fake News classification using LSTM, Deep Learning in PyTorch
### Getting Started
Run the notebook in Google colab and add the unzipped dataset files in the realtime data. It will take a few hours to train the model.
### Description
* We have used **Recurrent Neural Networks** with **LSTM** architecture for binary classification of a real/fake news based on its content. 
* We used 200-dimensional glove data for word embeddings and the model architecture consists of the leading embedding layer, 1 LSTM layer, 2 Linear layers followed by a dropout layer
* We were able to achieve a **Training Accuracy of 86.43% Test Accuracy of 85.84%** with only 1000 samples
