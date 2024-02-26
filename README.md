# Voice-Analysis-For-Parkinson-s-Disease
## Dataset

The dataset used for training the models is the Parkinson Speech Dataset with Multiple Types of Sound Recordings from UC Irvine, which can be found [here](https://www.openml.org/d/1488).

## Models

### 1. Basic Model

The basic model architecture consists of a simple feedforward neural network with two hidden layers. The model is trained on MFCC (Mel-frequency cepstral coefficients) features extracted from voice recordings. 

### 2. Improved Model

The improved model includes modifications to the architecture, such as increasing the number of units in the hidden layers and training for more epochs. Additionally, the learning rate of the Adam optimizer is adjusted to optimize performance.
