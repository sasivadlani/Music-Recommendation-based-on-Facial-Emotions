# Music-Recommendation-based-on-Facial-Emotions
This project uses facial emotion recognition to recommend music based on the user's current mood. The project includes three main components: data processing, emotion recognition, and music recommendation.

## Data Processing

To start, download the FER2013 dataset from [FER2013](https://www.kaggle.com/deadskull7/fer2013). Then, install all the dependencies imported in Data Processing.ipynb and run all the commands. This will create a folder for training and testing the model.

## Emotion Recognition

Next, install all the dependencies imported in Emotion Recognition.ipynb and run all the commands. This will create a model and train the data that we have extracted earlier. If you have model.h5 and model.json files, you can skip the training part and directly run the model.

## Music Recommendation

Finally, install all the dependencies in Music Recommendation.ipynb and run all the commands. This will take a picture from the webcam, detect the emotion, and give it to the music recommendation system. Note that the current model can detect happy and surprise emotions well, but less accurately detects sad, fear, and angry emotions.

### Improving Accuracy
You can change and train the model to improve the accuracy by tweaking the model parameters or using a different machine learning algorithm.
You can train the model further to improve the accuracy. Feel free to modify the project and experiment with your own data to create a more accurate and personalized music recommendation system.
