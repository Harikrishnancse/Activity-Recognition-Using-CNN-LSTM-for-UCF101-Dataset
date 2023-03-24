# Activity Recognition using CNN-LSTM Model for UCF-101 Dataset

      Human activity recognition is a task of detecting and classifying human actions from video data. One popular dataset used for this task is the UCF-101 dataset, which contains 13,320 videos of 101 different human action categories.
      Convolutional Neural Networks (CNNs) and Long Short-Term Memory (LSTM) networks are commonly used for activity recognition tasks. CNNs are powerful at capturing spatial features, while LSTMs can capture temporal dynamics in video data.
     To use CNN-LSTM for human activity recognition on the UCF-101 dataset, you can follow these steps:

##          1. Preprocess the data:

                      Resize the videos to a fixed size, extract frames from the videos, and split the data into training and testing sets.
                      
##          2. Extract features: 

                      Pass the frames through a pre-trained CNN, such as VGG16, and extract features from the last convolutional layer. These features will be used as inputs to the LSTM network.
                      
##         3. Build the LSTM network: 

                      The LSTM network should take the features extracted from the CNN as input and learn to classify the human activities. You can experiment with different architectures and hyperparameters to find the best model.
                      
##          4. Train the model:

                      Train the LSTM network on the training data using backpropagation through time (BPTT) and optimize the model using an appropriate loss function.
                      
##          5. Evaluate the model:

                      Evaluate the model on the testing data and calculate the accuracy and other performance metrics.

Some additional techniques that can improve the performance of CNN-LSTM models for human activity recognition include data augmentation, transfer learning, and ensembling multiple models.

Overall, CNN-LSTM is a powerful approach for human activity recognition on the UCF-101 dataset and can achieve high levels of accuracy with the right architecture and training approach.
