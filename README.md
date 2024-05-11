[![GitHub license](https://img.shields.io/github/license/SINGHxTUSHAR/AutoMark.svg)](https://github.com/SINGHxTUSHAR/AutoMark/blob/master/LICENSE)
[![GitHub contributors](https://img.shields.io/github/contributors/SINGHxTUSHAR/AutoMark.svg)](https://GitHub.com/SINGHxTUSHAR/AutoMark/graphs/contributors/)
[![GitHub issues](https://img.shields.io/github/issues/SINGHxTUSHAR/AutoMark.svg)](https://GitHub.com/SINGHxTUSHAR/AutoMark/issues/)
[![GitHub pull-requests](https://img.shields.io/github/issues-pr/SINGHxTUSHAR/AutoMark.svg)](https://GitHub.com/SINGHxTUSHAR/AutoMark/pulls/)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)


[![GitHub watchers](https://img.shields.io/github/watchers/SINGHxTUSHAR/AutoMark.svg?style=social&label=Watch&maxAge=2592000)](https://GitHub.com/SINGHxTUSHAR/AutoMark/watchers/)
[![GitHub forks](https://img.shields.io/github/forks/SINGHxTUSHAR/AutoMark.svg?style=social&label=Fork&maxAge=2592000)](https://GitHub.com/SINGHxTUSHAR/AutoMark/network/)
[![GitHub stars](https://img.shields.io/github/stars/SINGHxTUSHAR/AutoMark.svg?style=social&label=Star&maxAge=2592000)](https://GitHub.com/SINGHxTUSHAR/AutoMark/stargazers/)

[![Open in Visual Studio Code](https://img.shields.io/static/v1?logo=visualstudiocode&label=&message=Open%20in%20Visual%20Studio%20Code&labelColor=2c2c32&color=007acc&logoColor=007acc)](https://open.vscode.dev/SINGHxTUSHAR/AutoMark)

# AutoMark 🙋🏻‍♂️📋:
AutoMark is a smart Attendance system that uses the OpenCV and Haar-Cascade Classifier to mark the attendance of the students.
![Designer (1)](https://github.com/SINGHxTUSHAR/AutoMark/assets/113624520/b6778527-0c5e-4eff-b816-80ac06baaa04)

This project implements a smart attendance system for students using OpenCV (Open Source Computer Vision Library) and a pre-trained Haar cascade classifier. Here's a breakdown of the functionalities:
### `System Components:`
* Camera: Captures real-time video feed of the students.
* OpenCV Libraries: Used for image processing tasks like frame grabbing, face detection, and drawing bounding boxes.
* Haar Cascade Classifier: A pre-trained model that efficiently detects frontal human faces within the video frames.
* Student Database: Stores student information like IDs, names, and potentially facial images (optional for enhanced recognition).
* Attendance Marking System: Logs attendance data, typically with timestamps and student IDs. This can be a simple text file, a spreadsheet, or integrated with existing attendance management software.

### `Working Process:`
* Real-time Video Capture: The system continuously captures video frames from the camera.
* Face Detection: OpenCV utilizes the Haar cascade classifier to identify and locate faces within each frame.
* Student Recognition (Optional): If the system stores student facial data, additional algorithms (not necessarily Haar cascade) might be used to recognize specific students within the detected faces.
* Attendance Marking: Based on detected faces (and potentially recognized students), the system marks attendance in the database. This might involve recording timestamps and student IDs (or names).
* Visualization (Optional): The system can display the video feed with bounding boxes around the detected faces for real-time monitoring purposes.

### `Benefits:`
* Automated Attendance: Eliminates the need for manual attendance checks, saving time and reducing errors.
* Scalability: The system can handle multiple students simultaneously.
* Reduced Contact (Optional): If facial recognition is implemented, students might not need to physically interact with a device to register attendance.
* Cost-effective: Leverages open-source libraries like OpenCV, making it a budget-friendly solution.

### `Limitations:`
* Haar cascade limitations: The pre-trained model might struggle with angled faces, poor lighting conditions, or occlusions (e.g., hats, masks).
* Privacy Concerns: Storing student facial data raises privacy considerations that need to be addressed with proper security measures and user consent.


## Commands ✍️:
* This will be used to add face to dataset and face will be recorded via webcam.
```bash
python Add_faces.py
```
* Record attendance of added face , press 'o' to record attendance and it will create csv file corresponding to date present , name and timestamp will be recorded.
```bash
python test.py
```
* Attendance will be displayed here and can be downloaded in csv format.
```bash
streamlit run app.py
```

## Output 📁:
For more output images visit: <a href="https://github.com/SINGHxTUSHAR/AutoMark/tree/main/Output"> Link </a>
![out_1](https://github.com/SINGHxTUSHAR/AutoMark/assets/113624520/d433ea2c-dfad-47cd-a149-0d497ff4c87f)
![out_2](https://github.com/SINGHxTUSHAR/AutoMark/assets/113624520/05a13127-9cb0-46b7-868a-9de3e8edc325)
![out_6](https://github.com/SINGHxTUSHAR/AutoMark/assets/113624520/51cf88ca-0315-46fd-959e-5d3cd3130eb1)


## Reference 🧧:
* Classifier <a href="https://docs.opencv.org/3.4/db/d28/tutorial_cascade_classifier.html"> Documentation </a>
* Streamlit <a href="https://docs.streamlit.io/"> Documentation </a>
* Research Paper <a href="https://ieeexplore.ieee.org/document/8776934"> Documentation </a>


## Requirements💻 :

Ensure you have the following dependencies installed:

- Python (version 3.9.x || 3.12.x)
- IDE: VS-CODE or collab
- Virtual-environment(venv)
- Other dependencies (refer to the requirements.txt)

You can install the required Python packages using:

```bash
pip install -r requirements.txt
```

## Setup 💿:

- Clone the repository:
```bash
git clone https://github.com/SINGHxTUSHAR/AutoMark.git
cd AutoMark
```
- Create a virtual environment (optional but recommended):
```bash
python -m venv venv
```
- Activate the virtual environment:
  - On Windows:
   ```bash
   venv\Scripts\activate
   ```
  - On macOS/Linux:
  ```bash
  source venv/bin/activate
  ```

## Contributing 📌:
If you'd like to contribute to this project, please follow the standard GitHub fork and pull request process. Contributions, issues, and feature requests are welcome!

## Suggestion 🚀: 
If you have any suggestions for me related to this project, feel free to contact me at tusharsinghrawat.delhi@gmail.com or <a href="https://www.linkedin.com/in/singhxtushar/">LinkedIn</a>.

## License 📝:
This project is licensed under the <a href="https://github.com/SINGHxTUSHAR/AutoMark/blob/main/LICENSE">MIT License</a> - see the LICENSE file for details.
