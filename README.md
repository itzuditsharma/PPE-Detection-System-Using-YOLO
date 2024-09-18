# PPE-Detection-System-Using-YOLO
This project implements a Personal Protective Equipment (PPE) detection system using the YOLO (You Only Look Once) object detection model.

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
