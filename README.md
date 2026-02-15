# AI-FireDrone
AI-based autonomous drone for early fire detection and environmental monitoring. Trained model included for research purposes.

# AI-FireDrone: Autonomous Fire Detection Drone

## Overview
AI-FireDrone is an AI-based autonomous drone system designed for **early fire detection** and **environmental monitoring**. This system integrates **computer vision**, **intelligent decision-making**, and **autonomous flight** to monitor large areas efficiently, ensuring rapid response to fires and minimizing potential environmental damage. 

By combining AI, engineering, and environmental science, this project demonstrates practical applications of technology to protect **lives, property, and ecosystems**.

## Features
- Real-time fire detection using YOLOv8
- Autonomous monitoring without human intervention
- Environmental safety and disaster prevention
- Visualization of detection results with annotated images

## Dataset
- Dataset used: [Continuous Fire Detection Dataset v6](https://roboflow.com/) via Roboflow
- **Note:** Dataset must be downloaded manually and placed in `/content/continuous_fire-6/`  

## Getting Started

1. Clone this repository:
   ```bash
   git clone https://github.com/<your-username>/AI-FireDrone.git
   cd AI-FireDrone
   
2. Install required packages:

```bash
pip install -r requirements.txt

	3.	Open the Jupyter Notebook to train or evaluate the model:

	•	/notebooks/FireDrone_AI_Training.ipynb

	4.	Instructions to run YOLO training (inside notebook or terminal):

yolo task=detect mode=train model=yolov8s.pt data=/content/continuous_fire-6/data.yaml epochs=80 imgsz=640 plots=True


**Key points:**
1. Always **close a code block** with triple backticks ``` after your commands.
2. Don’t mix code and normal text inside the same triple backticks. Keep text outside.

---

If you want, I can rewrite your **entire README snippet** so all the numbered steps and commands are formatted **cleanly** without GitHub thinking it’s all bash commands.  

Do you want me to do that?
