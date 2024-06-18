<h1>GestureCanvas</h1>
Aim of this project is to create an interactive and intuitive drawing application that leverages computer vision techniques to recognize hand gestures and allow users to draw freehand on a virtual canvas using their hand movements. The project demonstrates the integration of various libraries and techniques, including OpenCV for video processing, MediaPipe for hand tracking, and gesture recognition algorithms.

<h2>Requirements:</h2>
1.	OpenCV (cv2) library for image and video processing
<br>2.	NumPy library for numerical operations
<br>3.	MediaPipe library for hand tracking

<h2>Project Overview:</h2>
The project follows the following steps: 
<br>
<h3>Use the Application </h3>
Two windows will open: "Output" and "Paint".
<br>The "Output" window shows the video feed from your webcam, with hand landmarks detected and drawn.
<br>The "Paint" window is the canvas where you can draw using your hand gestures.
<h3>Drawing </h3>
To draw on the canvas, hold up your hand in front of the webcam.
<br>Bring your index finger and thumb close together (within 30 pixels distance) to start drawing.
<br>Move your index finger while keeping your thumb close to draw lines on the canvas.
<h3>Changing Colors</h3> 
On the top of the "Paint" window, there are rectangles representing different colors (Clear, Blue, Green, Red, Yellow).
<br>Point your index finger at the desired color rectangle to change the drawing color.
<h3>Clearing the Canvas</h3> 
To clear the canvas, point your index finger at the "Clear" rectangle on the top of the "Paint" window.
<h3>Exit</h3>
To exit the application, press the 'q' key while either of the windows ("Output" or "Paint") is in focus.

<h2>Usage</h2>
1.Install Dependencies 
<br>2.Install OpenCV (cv2) library
<br>3.Install NumPy library
<br>4.Install MediaPipe library
  <br>Set up the Project 
<br>5.Save the provided code in a Python file (e.g., hand_drawing.py).
  <br>Run the Script 
<br>6.Open a terminal or command prompt.
  <br>Navigate to the directory where you saved the hand_drawing.py file.
  <br>Run the script by typing python hand_drawing.py and pressing Enter.
