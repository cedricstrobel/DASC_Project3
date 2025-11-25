# Repository Structure

This repository contains all files for **DASC 41103 – Project 3: Applying CNNs**.  
Below is an overview of every file and folder included in the project and what each one represents.

ML_3/
│
├── DASC41103_Project3_ApplyingCNN.pdf
├── ML_Project3_1_2_3.ipynb
├── Group_28_CNN_FullModel.ph
├── Project_3_Powerpoint.pptx
├── README.md
└── dataset/
├── hogs/
└── no_hogs_random/

yaml
Copy code

---

## File & Folder Descriptions

### **📄 DASC41103_Project3_ApplyingCNN.pdf**
The official project instructions provided by the instructor.  
Includes the assignment description, requirements, deliverables, and grading rubric.

---

### **📓 ML_Project3_1_2_3.ipynb**
The main Jupyter notebook for the project.  
This notebook contains:
- Dataset loading and preprocessing  
- Image transformations (resize to 500×500, normalization, augmentation)  
- CNN architecture definition  
- Model training, tuning, and evaluation  
- Final reflection answers  

This is the core implementation file for the entire project.

---

### **💾 Group_28_CNN_FullModel.ph**
The saved **full PyTorch CNN model**, exported after training.  
This file is used by the instructor to evaluate your model on unseen test images.

---

### **📊 Project_3_Powerpoint.pptx**
The presentation slides for the project.  
Summarizes:
- Dataset creation  
- Model architecture  
- Training results  
- Evaluation  
- Key takeaways and reflections  

Used in the 15-minute recorded presentation submission.

---

### **📘 README.md**
The repository overview file.  
Explains the project purpose, structure, and how to navigate the repository.

---

## Dataset Folder

dataset/
├── hogs/
└── no_hogs_random/

css
Copy code

### **🐗 hogs/**
Images that **contain the official Razorback logo**.  
Used as the positive class (`0`) in the binary classifier.

### **🚫 no_hogs_random/**
Images that **do NOT contain the official Razorback logo**.  
Used as the negative class (`1`).

These two folders make up the full custom image dataset used to train and evaluate the CNN.

---

## Summary

This repository includes:
- The project instructions  
- The full project notebook  
- The saved trained model  
- Presentation slides  
- A complete labeled image dataset  
- A clear README describing everything  

Everything required for the assignment is included and organized for easy review.
