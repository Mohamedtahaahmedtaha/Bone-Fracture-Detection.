# Bone-Fracture-Detection.
# 🦴 Bone Fracture Detection with YOLOv8

This project applies YOLOv8 object detection to identify bone fractures in X-ray images as part of a medical imaging challenge.

 Dataset

The dataset used is from Kaggle:  
**Bone Fracture Detection (YOLOv8 format)**  
It includes labeled X-ray images with multiple classes of fractures such as:
- elbow positive  
- fingers positive  
- forearm fracture  
- humerus  
- shoulder fracture  
- wrist positive

## ⚙️ Model & Training Details

- **Model Used**: `YOLOv8n` (nano version)
- **Input Image Size**: 640x640
- **Epochs Trained**: **5 only**  
 Training was limited to 5 epochs due to resource constraints on Google Colab.*
- **Batch Size**: 8  
- **Optimizer**: SGD (default in YOLOv8)
- **Loss Function**: Built-in YOLO loss for object detection

- Sample output images include bounding boxes focused on fracture areas (if any were detected).

##  Future Work

- Increase the number of epochs (e.g. 50+)
- Experiment with YOLOv8s or YOLOv8m
- Perform image preprocessing or contrast enhancement
- Tune hyperparameters for better generalization

---

##  Notes

This work demonstrates a baseline training setup for fracture detection using YOLOv8 with limited computational resources.

