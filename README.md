# 🖼️ License Plate Detection and OCR with YOLOv5 + Tesseract

This project performs license plate detection and optical character recognition (OCR) on **static vehicle images** using YOLOv5 and Tesseract.

## 📦 Overview
Given an input image of a vehicle, this pipeline detects the license plate and extracts its text content using deep learning and OCR.

## 🔍 Workflow
1. Load an image of a vehicle.
2. Detect the license plate using a YOLOv5 model.
3. Crop the detected plate region from the image.
4. Apply Tesseract OCR to recognize text from the cropped plate.
5. Display or save the annotated image with detection and OCR results.

## 🧰 Tools Used
- **YOLOv5** for object detection
- **OpenCV** for image processing
- **Tesseract OCR** (via `pytesseract`) for text recognition
- Python (NumPy, Matplotlib)

## 🚀 How to Use
1. Clone this repository.
2. Install the requirements using `pip install -r requirements.txt`.
3. Load an image via the notebook or script.
4. Run the detection and OCR pipeline.
5. View the annotated output image with the plate text.

## 🧠 Notes
- This project is designed for single image inputs (no video or real-time feed).
- Works best with high-resolution images where plates are clearly visible.

---

🔍 Great for image-based vehicle monitoring, reporting applications, or OCR testing.
