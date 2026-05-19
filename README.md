# Gesture-and-Voice-controlled-Virtual-Mouse-Project
 A gesture and voice-controlled virtual mouse lets users control a computer without a physical mouse by using hand movements (via a camera) and voice commands to perform actions like moving the cursor, clicking and opening apps.

 
Installation, Setup, and Execution
Step 1: Create a virtual environment using the following command
	>> conda create --name gest python=3.8.5
	
Step 2: Activate the virtual environment using the following command
	>>conda activate gest
	
Step 3: Install the rquired libaries  using the following command 
	>>pip install -r requirements.txt
	
Step 4: Instal PyAudio and pywin32 libraries using the following commands
	>>conda install PyAudio
	>>conda install pywin32

Step 5: Use the following command to run the Gesture Controller
	>>python Gesture_Controller.py
	
Step 6: Use the following command to run the Voice based control
	>>python Wesley.py
