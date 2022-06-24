# Facial-detection-from-different-angles
# Project Description
This project uses OpenCV's Face Detection Neural Network to detect faces in images.
Uses DeIT(Data efficient Image transformer) model to train the KDEF,JAFFE and CK+ datasets to effectively recognize emotion from different angles.
# File Description
"Emotion_recognition_different_angles.ipynb" jupyter notebook file contains the whole implementation of training the model
"KDEF_preprocessing.py" - preprocessing of the KDEF dataset
"jaffe_proprocessing.py" - preprocesing of the Jaffe dataset
"face_detection.py" - Extract faces from the set of images
# Dependencies required
Timm(Pytorch image models) Library --- pip install timm
Pytorch version 1.8.1 --- pip install torch==1.8.1
