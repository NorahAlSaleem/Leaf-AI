# Leaf AI 🌿 - Smart Plant Identification & Care System

**Leaf AI** is a web-based intelligent application designed to bridge the gap between technology and nature. It utilizes Deep Learning, specifically **MobileNet V2 with Transfer Learning**, to identify plant species and detect common plant diseases from user-uploaded images with high accuracy (**95.95%**).

Beyond identification, the platform serves as a comprehensive agricultural knowledge hub tailored to regional conditions in Saudi Arabia, aligning with **Saudi Vision 2030**[cite: 1].

---

## ✨ Features
- **Automated Image Recognition:** Upload or capture leaf/plant photos to identify species instantly[cite: 1].
- **Disease Detection & Diagnosis:** Identify plant disorders and get tailored treatment recommendations[cite: 1].
- **Comprehensive Database:** Access detailed care guides including watering schedules, soil selection, fertilization, and sunlight exposure[cite: 1].
- **Text Search:** Search for plant metadata directly by name or category without uploading an image[cite: 1].
- **Bilingual Interface:** Fully responsive UI supporting both Arabic (RTL) and English[cite: 1].
- **Personalized Profiles:** Track user activity, saved favorites, and search history[cite: 1].

---

## 🛠️ Tech Stack

### Frontend:
- HTML5, CSS3, JavaScript[cite: 1]
- Responsive UI / Bilingual Layout (Arabic RTL support)[cite: 1]

### Backend & AI Inference:
- Python[cite: 1]
- MobileNet V2 (TensorFlow/Keras)[cite: 1]
- OpenCV (Image Preprocessing & Augmentation)[cite: 1]

### Database:
- MySQL RDBMS (`leaf_ai_db`)[cite: 1]

---

## 📊 Model Performance
The model was trained using extensive datasets and evaluated against validation sets, achieving optimal convergence[cite: 1]:
- **Final Accuracy:** 95.95%[cite: 1]
- **Final Loss:** 0.1237[cite: 1]

---

## 🗄️ Database Architecture
The backend is driven by a relational schema optimized with referential integrity (`ON DELETE CASCADE`), consisting of core tables[cite: 1]:
- `users` & `user_preferences`[cite: 1]
- `plants`, `plant_image`, & `plant_care`[cite: 1]
- `diseases` & `treatment`[cite: 1]
- `image_uploads` & `identification_results`[cite: 1]

---

## 👥 Prepared By:
- **Alia Manaa Al Hishlan**[cite: 1]
- **Fatimah Rabeallah Alsharif**[cite: 1]
- **Nourah Hadi Al Saleem**[cite: 1]
- **Rimas Hadi Al Sulai**[cite: 1]
- **Sarah Salman AlHarbi**[cite: 1]

**Supervisor:** Dr. Hajar Hameed Addeen  
*Department of Computer Science, College of Computer Science and Information Systems, Najran University (2025/2026)*[cite: 1].
