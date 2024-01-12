# Criminal Face Recognition Project

## Overview
This project is a Criminal Face Recognition system that utilizes OpenCV for facial detection, Tkinter for the frontend interface, and Excel for record-keeping. The system identifies faces of criminals from a predefined database and updates an Excel file with the relevant data, including the timestamp of detection.

## Features
- Face detection using Haar Cascade Classifier (harassed frontalface default.xml file).
- Real-time face recognition from images or videos.
- Integration with an Excel sheet for logging criminal data and detection timestamps.
- Tkinter-based frontend for user-friendly interaction.

## Technologies Used
- Python
- OpenCV
- Tkinter
- Excel

## Setup Instructions
1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/your-username/criminal-face-recognition.git


Install the required dependencies:

bash
Copy code
pip install -r requirements.txt
Run the application:

bash
Copy code
python main.py
## Usage
Launch the application.
Load the criminal database.
Provide an image or video for face detection.
The system will identify and update the Excel file with criminal data and the timestamp of detection.
Directory Structure
src/: Contains the source code files.
data/: Placeholder for the criminal database and Excel file.
images/: Sample images for testing face detection.
## Acknowledgments
The Haar Cascade Classifier used for facial detection is based on the harassed frontalface default.xml file from OpenCV.
Tkinter is used for creating the frontend interface.
## Contribution Guidelines
Feel free to contribute by forking the repository and creating a pull request. Bug reports, feature requests, and feedback are welcome.

## License
This project is licensed under the MIT License.
