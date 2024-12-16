# Final-Year-Project
Project_Link :- https://drive.google.com/drive/folders/1RQhah-dzXtz-lm6Q4Dv4pXA3m73iBhJy?usp=sharing


REAL-TIME CROWD MONIORING WITH INTELLIGENCE ALERT

This repository hosts a real-time crowd monitoring system leveraging YOLO (You Only Look Once) object detection and Centroid Tracking algorithms. It enables accurate crowd counting, dynamic density analysis, and intelligent alerting for public safety and efficient crowd management.



FEATURES

Real-Time Detection & Tracking: Detects and tracks individuals in video feeds.

Dynamic Crowd Analysis: Monitors density and movement patterns.

Intelligent Alerts: Triggers alerts for overcrowding or anomalies.

Optimized Performance: Utilizes multithreading for faster processing.




PREREQUISTIES

Python 3.8+

NVIDIA GPU (optional for speed optimization)

Required Python libraries (install via requirements.txt).





INSTALLATION

Place the YOLO model weights (e.g., yolov8x.pt) in the models/ directory.




USAGE

Run the system with a video file or live feed:

python src/main.py --input video.mp4




TECHNOLOGIES USED

Python: Core programming language.

YOLO: Real-time object detection.

OpenCV: Video processing.

Centroid Tracking: Tracks individuals across frames.



RESULTS

Live Detection: Tracks individuals and overlays bounding boxes.

Alerts: Generates notifications for high crowd density.


Contact

For questions or contributions, contact: Kuppam Bharadwaj.
