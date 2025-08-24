# 🧠 PCOS Detection Using Deep Learning

This repository contains our B.Tech 3rd-year project on detecting Polycystic Ovary Syndrome (PCOS) using a deep learning model based on **YOLOv5**. The project aims to automate the detection of follicular cysts from ultrasound images to assist in diagnosing PCOS.

## 📌 Project Overview

Polycystic Ovary Syndrome (PCOS) is a common hormonal disorder in women of reproductive age, often leading to complications such as infertility, obesity, insulin resistance, and mental health issues. Traditional diagnosis using ultrasound relies on manual detection, which can be slow and error-prone.

To address this, we trained a YOLOv5 object detection model that identifies and counts ovarian cysts from ultrasound images and classifies the result as **PCOS Positive** or **PCOS Negative** based on cyst count.

---

## 🚀 Key Features

- Real-time cyst detection using **YOLOv5**
- Classification based on cyst count threshold
- Supports annotated custom datasets in YOLO format
- Trained on a dataset of 3,500+ ultrasound images
- Model performance:  
  - Precision: **0.80+**  
  - Recall: **0.90+**  
  - mAP@0.5: **0.94+**

---

## 🛠️ Technologies Used

- **YOLOv5** (Ultralytics)
- **Python 3.8+**
- **Google Colab**
- **PyTorch**
- **Roboflow** (for annotation & augmentation)
- **OpenCV** & **Matplotlib** (for image processing & visualization)

---

## 📁 Dataset & Annotation

- Public ultrasound image dataset from **Kaggle**
- Manual annotation using **Roboflow**
- Exported in YOLO format (.txt and .yaml)
- Data Augmentation: flipping, rotation, brightness adjustment, etc.
-  we have uploaded the dataset in kaggle (link):https://www.kaggle.com/datasets/bhargavidimple/pcos-ultrasound-images-and-annotation-files

---

## 📊 Results

| Model   | Images | Precision | Recall | mAP@0.5 | mAP@0.5:0.95 |
|---------|--------|-----------|--------|---------|---------------|
| YOLOv5  | 529    | 0.80      | 0.91   | 0.94    | 0.71          |
| YOLOv8  | 706    | 0.80      | 0.88   | 0.93    | 0.71          |

---

## 🔍 Applications

- Clinical Decision Support for doctors
- Rural/remote diagnosis via telemedicine
- Integration into mobile health apps

---

## 📈 Future Scope

- Increase dataset diversity and size
- Combine image + patient metadata
- Use Vision-Language models for detailed diagnosis
- Clinical trials for real-world deployment

---

## 👥 Team

- G. Bhargavi (N200878)  
- K. Harshitha (N200373)  
- Ch. Rajeswari (N200427)  
- B. Chetan (N200518)  
- Sk. Akhil (N200145)  

**Mentor:** Y. Kalavathi, Dept. of CSE, RGUKT Nuzvid

---

## 📚 References

1. [IEEE Access Paper on PCOS Detection](https://doi.org/10.1109/ACCESS.2023.3304536)  
2. [Ultralytics YOLOv5 GitHub](https://github.com/ultralytics/yolov5)

---

> 🔒 Note: Patient data and personal information are handled securely and not included in this repository.
