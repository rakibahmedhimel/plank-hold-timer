# Plank Repetition Count with Computer Vision

This project uses machine learning and computer vision to count the number of seconds you hold a plank position in real-time. 
It uses Mediapipe for pose estimation and a Random Forest Classifier for posture detection.

## Features:
- Real-time plank hold timer.
- Voice feedback for posture correction.
- Accurate counting with a guide image to maintain the correct plank posture.
- The model can detect "plank" vs. "incorrect posture."

## Technologies Used:
- **Python 3.x**
- **Mediapipe**: For pose detection.
- **OpenCV**: For video processing.
- **scikit-learn**: For the Random Forest Classifier.
- **pyttsx3**: For voice feedback.
- **pygame**: For optional background music.

## Files in the Repository:
- `pose_plank_dataset.csv`: Dataset containing pose landmarks for plank detection.
- `pose_plank_classifier.pkl`: The trained Random Forest model for posture detection.
- `main.ipynb`: Jupyter Notebook with code for testing the plank model.

## How to Run:
1. **Clone the repository**:
   git clone https://github.com/rakibahmedhimel/plank-repetition-count.git
2. **Install the required dependencies:**
   pip install -r requirements.txt
3. **Test the model:**
   Open the main.ipynb file and run the code in Jupyter Notebook to test the model with your video or webcam footage.
   If you prefer to run it outside Jupyter, you can use the main.py script (if you create one based on the notebook).

## Model Overview:
The model uses pose landmarks captured from a video and classifies the pose as either "plank" or "incorrect posture". 
It also provides real-time feedback for the user and tracks how long they maintain the plank.

## Demo Video:
Watch the demo video showcasing the plank hold timer in the asset folder.
