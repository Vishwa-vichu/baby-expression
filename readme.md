Baby Expression Detection using Keras and OpenCV

This project is aimed at detecting four major expressions of babies namely Angry, Smile, Cry, and Sleep using Keras and OpenCV.
Requirements

To run this project, you will need:

    Python 3.x
    Keras
    OpenCV
    Numpy
    Pandas

Installation

Clone this repository to your local machine using:

bash

git clone https://github.com/sriraj66/expresion-baby

Dataset

The dataset used in this project is a combination of different publicly available datasets of baby images. The dataset contains 4 folders for each expression category and has a total of 10,000 images.
Usage

The main file of the project is baby_expression_detection.py which contains the code for training the model and detecting expressions. The file can be run using the following command:

bash

python baby_expression_detection.py

The program will first train the model on the dataset and then will start the webcam to detect expressions in real-time.
Results

The model achieves an accuracy of 85% on the test set. The expressions can be detected in real-time with an average FPS of 25.
Credits

This project was inspired by the following research paper:

    Deep Learning-Based Real-Time Infant Facial Expression Recognition

License

This project is licensed under the MIT License. Feel free to use and modify the code as per your requirements.
