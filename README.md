AirWrite Assistant

AirWrite Assistant is a small Python app that lets you write letters, words and simple math expressions in the air using your hand. It tracks your fingertip with Mediapipe, draws on a canvas using OpenCV and predicts what you wrote with a trained model. It can also solve basic maths following BODMAS rules.

how to run

install the needed libraries first:

pip install opencv-python mediapipe numpy tensorflow


then just run:

python airwrite_ai_assistant.py


press s to save and predict a letter, c to clear, space to add a space, enter to evaluate, and q to quit.

used libraries

opencv for video and drawing
mediapipe for hand tracking
tensorflow/keras for prediction
numpy for image handling
