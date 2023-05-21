# Face-Mask-Recognition-CNN-MobileNetV2

• Face Mask Recognition and Detection model using Convolutional Neural Network (CNN) and MobileNetV2:
• Successfully loaded the dataset (both with and without mask) from Kaggle and done data preprocessing including resizing
image size, and performing one hot encoding on labels.
• Splitted the dataset into training and testing parts with sklearn and tensorflow; built a deep learning model by constructing
the training images and using pre-trained mobilenetv2; deployed and saved the model upon tweaking the hyper parameters.
• Performed the model evaluation and calculated the accuracy by making predictions on the testing set.
• Implemented the model on Jupyter notebook by reading the real time video framing and resizing it to the required frame
by calling the preprocessing function where the ROI of each image is extracted and determining if the person(s) is/are wearing
masks or not by displaying the result in a framed rectangular box in red (no-mask) and green (with mask).
• The scope of the project includes widening the system across traffic systems, eliminating the need to manually check the
helmet of riders over 2-wheelers.
