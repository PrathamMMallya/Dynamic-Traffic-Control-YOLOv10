# Dynamic-Traffic-Control-YOLOv10

This repository contains the implementation of a dynamic traffic control system using the YOLO v10 model for real-time vehicle detection and classification. The project optimizes traffic light timings based on current traffic conditions, improving flow management and reducing congestion.

## Features
- Real-time vehicle detection using YOLO v10.
- Dynamic traffic signal adjustment based on detected vehicle types.
- Enhanced traffic management to reduce congestion and improve emergency response.

## Prerequisites
- Python 3.x
- `opencv-python`, `numpy`, `ultralytics`, `cvzone` libraries

## Installation and Setup

### Steps:
1. Open the command prompt (cmd) and navigate to the location where you want to clone the repository.
2. Run the command to clone the repository:
   ```bash
   git clone https://github.com/PrathamMMallya/Dynamic-Traffic-Control-YOLOv10.git
3.  Install the required libraries:
     ```bash
     pip install opencv-python numpy ultralytics cvzone
4.  Change the directory to the cloned repository:
      ```bash
      cd Dynamic-Traffic-Control-YOLOv10
5. In the Create Zones.py file, replace the video_path with the path to your video_trial.mp4.
6. In the main.py file, replace the video_path with the path to your video_trial.mp4.
7. Run main.py
    ```bash
    python main.py
  Note: If an AttributeError occurs, proceed to the next steps.

8. If the error persists, upgrade the ultralytics package:
   ```bash
   pip install --upgrade ultralytics
9.If the error continues, download the yolov10n.pt file from Hugging Face and place it in the Dynamic-Traffic-Control-YOLOv10 folder.

10. Run main.py again
    ```bash
    python main.py
Usage
Ensure the paths in Create Zones.py and main.py are set to your desired video file.
Run the project using the steps above to see the dynamic traffic control system in action.

Troubleshooting
If you encounter any errors related to model loading or missing dependencies, ensure all libraries are correctly installed and the yolov10n.pt file is in the right directory.

 

