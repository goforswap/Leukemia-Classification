# Leukemia Classification

To implement Deep Learning through Convolutional Neural Network in order to determine whether a patient has acute lymphoblastic leukemia (ALL) or not.

The dataset on which I implemented the model consists of 3256 Peripheral Blood Smear (PBS) images which plays a vital role in the initial screening of cancer from non-cancer cases. These images are of 89 patients that are suspected of ALL.

The dataset consists of images of Benign and Malignant acute lymphoblastic leukemia (ALL).

The Benign class comprises of hematogones, where as the Malignant Class comprises of ALL group with three subtypes of malignant lymphoblasts: Early Pre-B, Pre-B, and Pro-B ALL.

The dataset consists of two types of Images, that is Original PBS images and Segmented PBS images.

All the images were taken by using a Zeiss camera in a microscope with a 100x magnification and saved as JPG files. The images are of the size of 224x224 RGB images.

The no. of Images in the Dataset :-
➢ Benign – 504 Images
➢ Early – 985 Images
➢ Pre – 963 Images
➢ Pro – 804 Images

Thus, there are 3256 Original PBS images & 3256 Segmented PBS images.

STEPS FOR THE IMPLEMENTATION:
Step - 1: Importing Necessary Libraries
Step - 2: Loading the Dataset
Step - 3: Data Pre-Processing
Step - 4: Splitting the Dataset
Step - 5: Normalization and Transformation
Step - 6: Visualizing the Data
Step - 7: Building & Compiling the Model
Step - 8: Building the Model
Step - 9: Plotting the Model
Step - 10: Visualizing the Performance of the Model
Step - 11: Evaluating the Model
Step - 12: Prediction on the Test Set using the Trained Model


Our model achieved a 97.7% accuracy & 6.63% loss on training set and provide a 77.45% accuracy on testing set, given that we only run it for 15 epochs. It is also noticed that the above implementation is done on Original Set. On the Segmented Set, model achieved a 100% accuracy & 0.001% loss on training set and provide an 81.59% accuracy on testing set when running for 25 epochs. On both the Dataset Implementation, it is found that the model has trouble in predicting correct ‘Benign’ class images as compared to different classes.
