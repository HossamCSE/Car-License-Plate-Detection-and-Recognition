# Car License Plate Detection and Recognition 🚗🔍

This project uses YOLOv8 for **automatic car license plate detection** and EasyOCR for **text recognition** of plate numbers.

---

## 📌 Features

- Train YOLOv8 on a custom license plate dataset.
- Detect car plates in new images.
- Automatically crop detected plates.
- Extract plate numbers using OCR (EasyOCR).
- Save results (plate number + confidence) into a CSV file.

---
## Tools & Technologies Used
-Python 3.8+ — Programming language

-YOLOv8 (Ultralytics) — Object detection model

-EasyOCR — OCR engine to extract text from images

-OpenCV — For image reading, cropping, and saving

-Pandas — To manage OCR outputs and save them as CSV

-Kaggle Datasets — Used to get the license plate dataset


## 🛠️ Installation

1. Clone this repo:
   ```bash
   git clone https://github.com/your_username/Car-License-Plate-Detection-and-Recognition.git
   cd Car-License-Plate-Detection-and-Recognition
