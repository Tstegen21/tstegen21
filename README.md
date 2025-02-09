
Rendered

Fall & PPE Detection using Computer Vision
This project demonstrates a modular system that performs real-time fall detection and PPE (Personal Protective Equipment) detection using computer vision and video processing. Both detection pipelines are integrated into a single graphical user interface (GUI) to make it easy to test and compare the functionalities.

Please review all the steps below before running the project.

Prerequisites
Python 3.8 or later is required.
Ensure you have pip installed.
(Optional) It is recommended to use a virtual environment to avoid dependency conflicts.
Setup & Run
1️⃣ Create a Virtual Environment (Recommended)
# On Windows (Command Prompt)
python -m venv venv
venv\Scripts\activate

# On macOS/Linux
python3 -m venv venv
source venv/bin/activate
2️⃣ Install Dependencies
bash
Copy
Edit
pip install -r requirements.txt
3️⃣ Run the Application
The main entry point of the application is located at src/main.py. Run the following command:

bash
Copy
Edit
python src/main.py
4️⃣ Using the Application
Selecting a Video:
Click the 📂 Select Video button to choose a local video file or paste a YouTube URL into the text field.

Starting Detection:
Click ▶ Start PPE Detection to begin PPE detection or ⚠︎ Start Fall Detection to begin fall detection.

Stopping Detection:
Press 't' on your keyboard to stop detection or click the ⏹ Stop button in the GUI.

Exiting the Application:
Close the GUI window or the OpenCV display window to exit the application.

Additional Notes
The system uses YOLO-based models for both detection tasks. Ensure that the required model weight files are available in the weights/ directory.
If you encounter issues with missing dependencies, double-check that your requirements.txt is up to date.
Using a virtual environment helps prevent conflicts between the dependencies of different projects.
Now you're all set to run the Fall & PPE Detection system! 🚀
