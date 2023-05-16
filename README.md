# Human-Activity-recognition
This project focuses on recognizing human activities using the UCF-11 dataset. It involves two main components: data preprocessing and human activity recognition using the ResNet-50 model. The project achieves an accuracy of 97% in classifying images into their respective activity classes.

### Dataset
The UCF-11 dataset is used for this project. It contains videos of human activities from 11 different classes. In the data preprocessing step, the videos are sampled into frames. Specifically, 2200 frames are selected for each class. The dataset is then divided into training and test sets.

### Data Preprocessing
The data preprocessing step involves converting the video data into frames. The dataset is carefully selected to include 6 specific classes. The videos are sampled, and 2200 frames are extracted for each class. The frames are then split into training and test sets.

### Human Activity Recognition
For the task of human activity recognition, the ResNet-50 model is employed. This model is widely used for image classification tasks due to its deep architecture and outstanding performance. The implementation of the model utilizes several libraries such as TensorFlow, NumPy, Pandas, and Matplotlib.

### Accuracy
The human activity recognition model achieves an impressive accuracy of 97% in classifying images into their respective activity classes. This high accuracy demonstrates the effectiveness of the ResNet-50 model and the quality of the dataset used.

### Dependencies
The following dependencies are required to run the project:

TensorFlow  
NumPy    
Pandas   
Matplotlib   
Please make sure to have these libraries installed before running the code.
