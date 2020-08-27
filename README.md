# AUTO-TAG IMAGES OF THE GALA WITH DEEP LEARNING

# Project Summary 
The purpose of this project is to build an image auto-tagging model to classify images of the gala nights into 4 categories: Food, misc, Attire, Decoration & Signage.

# Dataset
The dataset can be found in [Hackathon](https://www.hackathon.com/event/auto-tag-images-of-the-gala-with-deep-learning-5e5ce1601c1c92001b638422).
The dataset consists of:
- 2 folders: 'Test Images' and 'Train Images' containing JPG images to train and test
- 2 csv files: 'test' and 'train' csv files containing information about images and their corresponding labels

# Process
1. Data Preprocessing
- Import csv data with image names and their corresponding label
- Function to load, resize images and append their corresponding labels 
2. Data Exploration
- Labels Distribution
- Show random images of each category
3. Build classification models with PCA and No PCA
- Random Forest
- Logistic Regression
- XGBoost
4. Build deep learning model using TensorFlow
- Build model from scratch
- Build model with pre-trained model VGG16
5. Predictions on test data of all models
