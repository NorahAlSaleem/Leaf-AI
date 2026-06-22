# Leaf AI — Smart Plant Identification & Care System 🌿🤖

The official repository for **Leaf AI**, a comprehensive Graduation Project developed at **Najran University** that utilizes Artificial Intelligence and Deep Learning to bridge the gap between complex botanical taxonomy and everyday plant care management.

---

## 📌 Project Overview
**Leaf AI** is an intelligent web ecosystem designed to simplify plant management for non-specialists. By leveraging advanced **Convolutional Neural Networks (CNNs)**, the platform processes user-uploaded foliage imagery to identify plant species automatically. Beyond classification, the system cross-references recognized species with a dedicated agricultural knowledge base to deliver real-time, automated care profiles (including scientific names, temperature tolerances, soil preferences, and irrigation metrics).

### Key Technical Milestones:
- **High-Accuracy Computer Vision:** End-to-end automated image resizing, scaling, and classification optimized for structural leaf venation and morphological patterns.
- **Dynamic Care Automation:** Immediate routing from successful model inference to distinct agricultural guidelines (Watering schedules, Soil composition, Sun exposure limits).
- **Agile Development Life Cycle:** Engineered following structured **Agile Methodology** constraints, moving seamlessly across iterative planning, sprint cycles, and rigorous system deployment stages.

---

## 🛠️ System Architecture & Tech Stack
The ecosystem integrates standard modern data science and application pipelines:
- **Deep Learning Framework:** Python 3.9+, TensorFlow / Keras (CNN Architecture)
- **Image Preprocessing:** OpenCV, NumPy, Pillow (PIL)
- **Database Engine:** Persistent relational storage tracking plant metadata matrices.
- **Project Methodology:** Agile Software Development Model (Sprints, Testing, and Continuous Validation).

---

## ⚙️ How the Computational Pipeline Works

### 1. Data Capture & Preprocessing
User images are uploaded via the web interface. The backend normalizes the imagery, applying targeted dimensions and dynamic normalization scales to secure robust input quality regardless of the capture device's environment.

### 2. Deep Learning Classification (CNN)
The structural layers of the Convolutional Neural Network pull distinct micro-features (edges, color distributions, and shapes) out of the visual matrices. Fully-connected activation functions then process these parameters to predict the target plant category with statistical precision.

### 3. Care Metadata Extraction
Once identified, the application maps the prediction class to its matching database record, instantly populating the client user profile with granular environmental metrics.

---

## 👥 Graduation Project Team & Credits
Developed under the academic supervision of **Dr. Hajar Hameed Addeen**, Department of Computer Science, College of Computer Science and Information Systems, **Najran University**.

### Research & Engineering Team:
* **Nourah Hadi Al Saleem**  
* **Alia Manaa Al Hishlan** 
* **Fatimah Rabeallah Alsharif**  
* **Rimas Hadi Al Sulai**  
* **Sarah Salman AlHarbi**  

---

## 📋 Document Reference
The underlying software parameters, empirical validation data, and comprehensive architecture workflows are fully documented in the academic report:
- `graduation_project2_report (1).pdf` *(Official Graduation Project Hub)*
