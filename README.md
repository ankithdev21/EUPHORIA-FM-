# Euphoria-Fm
<h2>Description</h2>
This system combines mood recognition through facial recognition and song recommendation to develop a mood-adaptive song recommendation system. The system recognizes the user's mood and recommends songs accordingly.

Output is in the form of a Search query in youtube

<h2>Libraries and modues used</h2>
Implemented using Python 3.1.,  OpenCV and NumPy, Streamlit library , AV , Mediapipe , Keras , Webbrowser ,OS
<ul>
<li>streamlit_webrtc: A Streamlit component for building WebRTC powered applications with real-time video and streaming capabilities. </li>
<li>streamlit_streamer: A Streamlit component for building live applications with low latency and high quality video and audio streaming.</li>
<li>av: A Python library for manipulating audio and video frames, providing high-level and low-level APIs for understanding, decoding, and managing media.</li>
<li>cv2: OpenCV (Open Source Computer Vision Library) is a computer vision and machine learning software that provides many image and video functions and algorithms.</li>
<li>mediapipe: A cross-platform, customizable framework for creating machine learning pipelines for image, video, and audio analysis, including prebuilt models and pipelines for face detection, hand tracking, pose prediction, and more.</li>
<li>vkeras: A high-level neural network API written in Python that can run on TensorFlow, CNTK, or Theano, providing users with easy-to-use and flexible tools for building and deep learning models.</li>
<li>viwebbrowser: A module that provides advanced links to open and view web pages in a user's web browser and provides easy programmatic access to web content.</li>
</ul>
<h2>Workings</h2>
Web App takes input from a live video stream or an image and detects the facial landmarks, such as the position of the eyes, nose, and mouth(distance between lips). It then uses machine learning algorithms, such as Viola Jones, to classify the emotions based on the movement and position of these facial landmarks. 
Viola Jones algorithms detects emotions and gives output as an standardized matrix for a given mood.
NumPy is used to transform the matrix and make it into an emotion
Emotions detected are happy, sad, angry, fear , surprise or neutral. 
The web app utilizes the predictions made by model based on the predicted mood(s) of the user. The module uses a standardized query for searching songs in YouTube.

<h2>Output</h2>
<img src="https://github.com/Fhini/Euphoria-Fm/assets/118623264/9af6eb83-0740-40c2-b82d-cfa5b2d24ae1">
<p>App Interface </p>
<img src="https://github.com/Fhini/Euphoria-Fm/assets/118623264/3c50d238-1560-4b07-a931-648e54b55ff2">
<p>Mood Detection</p>
<img src="https://github.com/Fhini/Euphoria-Fm/assets/118623264/1fd82e60-39f5-4b0c-a35c-292175942c64">
<p>Search query result</p>
