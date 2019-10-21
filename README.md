# Emojinator
  A simple Emoji Classifier for humans. It will detect the type of Emoji based on the gestures made by our hand using Convolution Neural Network.

# Code Requirements: 
  You can install Conda for python which resolves all the dependencies for machine learning.

# Description:
  Emojis are ideograms and smileys used in electronic messages and web pages. Emoji exist in various genres, including facial expressions, common objects, places and types of weather, and animals. They are much like emoticons, but emoji are actual pictures instead of typographics.

# Functionalities:
  1. Filters to detect hand.
  2. CNN for training the model.

# Python Implementation:
  Network Used- Convolutional Neural Network.
  
# Procedure:
  1. First, you have to create a gesture database. For that, run CreateGest.py. Enter the gesture name and you will get 2 frames displayed. Look at the contour frame and adjust your hand to make sure that you capture the features of your hand. Press 'c' for capturing the images. It will take 1200 images of one gesture. Try moving your hand a little within the frame to make sure that your model doesn't overfit at the time of training.
  2. Repeat this for all the features you want.
  3. Run CreateCSV.py for converting the images to a CSV file
  4. If you want to train the model, run 'TrainEmojinator.py'
  5. Finally, run Emojinator.py for testing your model via webcam.
