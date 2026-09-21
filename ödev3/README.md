# STOP Sign Detection with YOLO11

This project was prepared for Yıldız Rover Support Team Assignment 3.

The aim of the project is to detect STOP traffic signs using a deep learning based object detection model.

In the previous assignment, STOP signs were detected using red color detection with OpenCV. However, this method could also detect other red objects. In this project, a YOLO model was trained so that the system can learn the visual features of a STOP sign instead of only using its color.

---

## Model

YOLO11n was selected for this project.

YOLO is a single-stage object detection model. It can detect the class and location of objects in an image in one process, which makes it suitable for real-time applications such as rover systems.

The pretrained model used:

```python
YOLO("yolo11n.pt")
