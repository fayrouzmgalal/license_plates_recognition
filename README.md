# license_plates_recognition
# License Plate Detection and Recognition 🚗🔍

A deep learning pipeline for **automatic detection** and **OCR recognition** of Arabic license plates using YOLOv8 and PaddleOCR. Designed for complex real-world scenarios, including low-resolution and night-time images.

---

## 🔧 Project Structure

 images: https://app.roboflow.com/fayrouz-tfojw/arabic-license-plates-7jt56/2
 
 ## 🧠 Model Overview

| Component     | Model Used      | Description                          |
|---------------|------------------|--------------------------------------|
| Detection     | YOLOv8n          | Detects license plates in full images |
| OCR           | PaddleOCR v3.0.0   | Extracts readable text from plates    |
| Reasoning     | VLLM             | (Optional) Could be used to post-process / verify outputs with LLM |

---

