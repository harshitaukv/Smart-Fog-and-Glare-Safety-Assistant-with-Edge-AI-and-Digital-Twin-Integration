Smart Fog and Glare Safety Assistant with Edge AI and Digital Twin Integration

Enhancing Road Safety through Vision-Based AI and Real-Time Environment Simulation

Overview:
Smart Fog and Glare Safety Assistant is an AI-driven system designed to improve visibility and driver awareness during challenging weather conditions such as fog, glare, or low light.

This project leverages YOLOv8 (You Only Look Once) object detection and digital twin simulation concepts to analyze real-time road footage, enhance visual clarity using contrast improvement (CLAHE), and detect road objects for safer navigation.

Key Features:
* Edge AI Integration– Runs lightweight YOLOv8 models on edge devices for real-time detection.
* Fog & Glare Reduction– Uses Contrast Limited Adaptive Histogram Equalization (CLAHE) for improved visibility.
* Real-Time Object Detection– Detects vehicles, pedestrians, and obstacles using YOLOv8.
* Digital Twin Concept– Processed video data can be linked to a virtual simulation for analytics and autonomous testing.
* Offline Capability– Processes videos locally without relying on cloud connectivity.

Technologies Used:

| Category             | Tools / Libraries                                                  |
| -------------------- | ------------------------------------------------------------------ |
| AI Model             | [YOLOv8 (Ultralytics)](https://github.com/ultralytics/ultralytics) |
| Programming Language | Python 3                                                           |
| Computer Vision      | OpenCV                                                             |
| Visualization        | Matplotlib                                                         |
| Environment          | Google Colab                                                       |
| Integration Concept  | Digital Twin, Edge AI                                              |

System Architecture:

  Video Input
     ↓
Contrast Enhancement (CLAHE)
     ↓
Object Detection (YOLOv8)
     ↓
Annotated Output Video
     ↓
Digital Twin / Analytics Dashboard (Future Integration)

Setup & Installation

Google Colab execution:

Step 1: Install Dependencies
Step 2: Upload a Video File
Step 3: Run the Detection & Enhancement Script
Step 4: Download the Processed Output

Output Example:
After processing, you will get an annotated video (`processed_output.avi`) where:
Visibility is enhanced through contrast adjustment.
Objects such as cars, pedestrians, and road signs are detected and labeled.
The output is suitable for digital twin simulation or safety analysis.

Future Scope
* Integration with real-time IoT sensors for adaptive brightness and speed control.
* Digital Twin dashboard for traffic simulation and safety analytics.
* Deployment on Edge AI devices like NVIDIA Jetson Nano or Raspberry Pi.
* Advanced fog removal algorithms using deep learning (DehazeNet, CycleGAN).



Would you like me to make this README visually formatted for GitHub (with emojis, sections, and clickable badges like “Open in Colab” or “View Demo”)? I can generate that next.
