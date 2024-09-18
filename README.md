# PPE-Detection-System-Using-YOLO
This project implements a Personal Protective Equipment (PPE) detection system using the YOLO (You Only Look Once) object detection model.
The system is capable of identifying whether individuals are wearing essential PPE such as hard hats, masks, and safety vests, as well as detecting when PPE is missing.

## Features:
**Real-time Object Detection:** Detects PPE in live video streams or pre-recorded video files.

**YOLO Model:** Utilizes a pre-trained YOLO model (ppe.pt) for fast and accurate detection.

**Class Labels:** Identifies multiple PPE classes including:
- Hardhat
- Mask
- NO-Hardhat
- NO-Mask
- NO-Safety Vest
- Safety Vest
- Person
- Safety Cone
- Machinery
- Vehicle

**Visual Feedback:** Highlights detected objects with color-coded bounding boxes:
* Red: Missing PPE (NO-Hardhat, NO-Mask, NO-Safety Vest)
* Green: Correct PPE usage (Hardhat, Mask, Safety Vest)
* Blue: Other detected objects (Person, Vehicle, Machinery)

**Confidence Scores:** Displays confidence level for each detection.

## Requirements:
* Python 3.x
* OpenCV
* Ultralytics YOLOv8
* cvzone
* Math

## Outputs 
![image](https://github.com/user-attachments/assets/66ddc813-2ca8-4aaa-9a99-adabb6f44221)

![image](https://github.com/user-attachments/assets/925d89b6-73a8-4b88-8610-f7cf5f0abd2f)

