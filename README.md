✋ CS449 Gesture-Based Control
📝 What is This All About?
Hey! This project is a really cool system that lets you control your computer with just your hand gestures! It's a project for the CS449/549 course that uses your webcam to recognize hand movements and translate them into commands like moving the mouse, clicking, and even scrolling. It's like something out of a sci-fi movie!

🚀 What Can It Do?
Mouse Control: Move your hand, and the mouse cursor follows along.

Clicking: Use a simple hand gesture to perform a click.

Scrolling: Scroll up or down a page with a thumbs-up or thumbs-down gesture.

Interactive Interface: There's a basic on-screen interface with buttons you can "click" with your hand.

⚙️ What's Under the Hood?
This project is built using some awesome Python libraries. Here's what we've got:

OpenCV: A powerful library for computer vision that handles all the webcam magic.

MediaPipe: This is the core of the project! It's a framework that gives us all the hand-tracking and gesture recognition features.

PyAutoGUI: This library lets the script control your mouse and keyboard, so we can actually move the cursor and scroll.

🛠️ How to Get Started
Ready to give it a try? Here's how to get it running on your machine.

Clone the repo:

git clone https://github.com/kutluhaan/CS449GestureBasedControl.git
cd CS449GestureBasedControl

Install the dependencies:
You can install everything you need using pip.

pip install mediapipe opencv-python pyautogui pyngrok

Run the script:
You'll need to run the Jupyter Notebook file.

jupyter notebook CS449-GestureBasedControlHomework.ipynb

Launch the camera:
Once the notebook is open, just run all the cells. Your webcam should turn on, and you'll see a window with the gesture control interface.

📸 What It Looks Like!
(This is where you'd add a cool GIF or a video of the system in action! It would make the project so much more exciting for people to check out.)

Example:

🙏 A Big Thank You!
MediaPipe: For their incredible hand-tracking solution! It's the key to making this project work.

OpenCV and PyAutoGUI: For providing the tools we needed to bring this project to life!
