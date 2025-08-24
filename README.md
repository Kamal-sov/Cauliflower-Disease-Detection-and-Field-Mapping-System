# Cauliflower-Disease-Detection-and-Field-Mapping-System
# 🌱 Cauliflower Disease Detection using YOLO Models
--------------------------------------------------------------------------------------------------------------------------------------
This project presents a **deep learning-based solution** for detecting and managing diseases in cauliflower plants.  
Using **YOLOv8, YOLOv9, and YOLOv11**, the system classifies plant health conditions (Healthy, Black Rot, Downy Mildew, Bacterial Spot Rot) and generates an **interactive field map** for farmers to take timely actions.

--------------------------------------------------------------------------------------------------------------------------------------

## 📌 Features
- ✅ Trained **YOLOv8, YOLOv9, YOLOv11** for plant disease detection  
- ✅ Achieved high accuracy (mAP@0.5 up to **97%**)  
- ✅ Works **offline**, no internet or high-end GPU required  
- ✅ Generates a **field map** highlighting diseased & healthy plants  
- ✅ Secure **login & authentication** system for user access  
- ✅ Results stored in **SQL database** for future reference  

--------------------------------------------------------------------------------------------------------------------------------------

## 🛠️ System Architecture
1. **Authentication System** – User login/registration  
2. **Image Capture** – Field images tagged with row/column  
3. **Disease Detection** – YOLO models identify plant condition  
4. **Database Storage** – Predictions saved in SQL  
5. **Visualization** – Interactive HTML-based field map  
6. **Feedback** – Farmers validate or comment on results  

--------------------------------------------------------------------------------------------------------------------------------------

## 📂 Dataset
- Collected cauliflower plant images covering:  
  - 🌿 Healthy  
  - 🍂 Black Rot  
  - 🍃 Downy Mildew  
  - 🍁 Bacterial Spot Rot  
- Dataset size: ~642 images  
- Data augmentation techniques applied for better generalization  

--------------------------------------------------------------------------------------------------------------------------------------

## 📊 Results
| Metric                | YOLOv8 | YOLOv9 | YOLOv11 |
|------------------------|--------|--------|---------|
| Optimal F1 Score       | 0.98   | 0.96   | 0.96    |
| mAP@0.5                | 0.970  | 0.976  | 0.970   |
| Precision@1.0          | 0.868  | 0.861  | 0.861   |
| Recall@0.0 Confidence  | 0.98   | 0.99   | 0.99    |

- YOLOv8 → Best **F1 score** (0.98)  
- YOLOv9 → Best **mAP@0.5** (0.976)  
- YOLOv11 → Balanced performance  
--------------------------------------------------------------------------------------------------------------------------------------


## 🚀 Future Directions
- Real-time disease detection with edge devices  
- Scaling to other crops (tomato, wheat, lettuce, etc.)  
- Integration with IoT (drones, smart cameras, sensors)  
- Automated interventions using robotics (sprayers, drones)  
- Synthetic data generation for larger datasets  
- Mobile app + cloud support for farmers  
<img width="1044" height="2454" alt="Project Pipeline - visual selection" src="https://github.com/user-attachments/assets/2c265727-a461-4355-958e-1a9b035bf167" />

--------------------------------------------------------------------------------------------------------------------------------------
## License
This project is released under the MIT License. You are free to use, modify, and distribute it with attribution.

## 📦 Installation & Usage
### 1️⃣ Clone the repository
```bash
git clone https://github.com/your-username/cauliflower-disease-detection.git
cd cauliflower-disease-detection

