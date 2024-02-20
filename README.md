
# Air Mouse 🖐️🖱️
Air Mouse is an innovative human-computer interaction device that leverages a computer’s camera to interpret hand gestures and control the user interface.

# Inspiration 💡
Our team was inspired by the intuitive gesture recognition technology found in Apple Pro Vision, Meta Quest, and various VR headsets. We aimed to bring this natural interaction to everyday computing.

# Features 🌟
Gesture Recognition: Air Mouse captures hand gestures using the computer’s camera and translates them into cursor movements and UI control.
Server-Client Architecture: The system is built with a server-client model. The server, written in Python, uses TensorFlow and MediaPipe to process the video feed and generate a hand skeleton mesh. The client, written in React.js, handles the user interface.
Challenges and Solutions 🚧
Translating complex hand gestures into precise cursor actions was a significant challenge. We tackled this by:

Developing a robust set of rules based on spatial data from the hand’s skeleton mesh.
Implementing exponential smoothing to reduce noise and jitter, making cursor movement more predictable and user-friendly.

# Accomplishments 🏆
We’re proud to have built a system that accurately tracks hand movements and translates them into cursor actions. This enhances user experience and promotes a cleaner, touch-free computing environment.

# Built With 🛠️

Computer Vision
CSS
CV
Flask
Git
HTML
JavaScript
MediaPipe
OpenCV
Python
React
TensorFlow
We learned a lot about gesture recognition technology, TensorFlow, MediaPipe, React.js, and server-client architecture design during this project. We’re excited to continue improving Air Mouse and can’t wait to see where it goes next! 
