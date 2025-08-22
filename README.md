Alzheimer's Disease Classifier
A Python AI project that classifies the severity of Alzheimer’s disease from MRI images using a CNN and SHAP for explainable predictions.  
The project predicts four levels:  
🟢 VeryMildDemented – Very mild cognitive decline  
🟡 MildDemented – Mild cognitive decline  
🟠 ModerateDemented – Moderate cognitive decline  
🔴 NonDemented – Healthy  

💡 Features
- CNN architecture with 2 convolutional blocks + global average pooling  
- Handles class imbalance with class weights  
- SHAP explainability to visualize model predictions  
- Beginner-friendly modular Python code  
- Automatic saving of SHAP images in shap_outputs/  

🧪 How to Run
1. Clone repo:  
git clone https://github.com/saif-emara/ALzheimer-Disease-Augmented.git  
cd ALzheimer-Disease-Augmented  
2. Install dependencies:  
pip install -r requirements.txt  
3. Run code:  
python main.py  
✅ Make sure DATA_DIR in main.py points to your dataset path, e.g.: "/kaggle/input/alzheimer-disease-dataset/Alzheimer_Dataset_V2"  

🗂️ File Structure
- main.py  
- requirements.txt  
- README.md  
- shap_outputs/ (auto-created)  
- dataset/ (not included, must download from Kaggle)  

📌 Notes
- Dataset not included due to size (363 MB), download from Kaggle  
- Educational project only, not for medical diagnosis  
- SHAP images saved automatically in shap_outputs/  

🧠 What I Learned
- CNN design and implementation in TensorFlow  
- Handling class imbalance  
- Explainable AI with SHAP  
- Modular Python coding  
- Visualizing predictions and heatmaps  

📷 Example Output
- SHAP heatmaps showing important regions  
- Predicted class: ModerateDemented  

## ✍️ Author
**Saif Emara**  
[GitHub](https://github.com/saif-emara) | [LinkedIn](https://www.linkedin.com/in/saif-emara-51a777377)

✨ Tagline
AI-powered MRI classifier 🧠 | Detect Alzheimer’s severity in 4️⃣ levels | Visual explanations with SHAP 🌈
