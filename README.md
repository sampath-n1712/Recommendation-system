# Recommendation-system using emotion detection
download FER2013 dataset
<br />https://www.kaggle.com/msambare/fer2013
<br />In the same folder, create a new folder named data and save the test and train folders in it.



Packages need to be installed
<br />pip install numpy
<br />pip install opencv-python
<br />pip install keras
<br />pip install tensorflow
<br />pip install pillow


To train Emotion detector model
<br />Run TrainEmotionDetector.py

After Training , you will find the trained model structure and weights are stored in your project directory. emotion_model.json emotion_model.h5
<br />copy these two files, create model folder in your project directory and paste it.

To run your emotion detection file
<br />Run TestEmotionDetector.py
<br />You can either take your live camera feed or paste the path of the video by commenting the other out.

To analyse the model
<br />Run EvaluateEmotionDetector.py

Music recom system to be added
