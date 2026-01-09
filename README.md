# AI Trace Finder 🔍  
**Forensic Scanner Source Identification using AI**

AI Trace Finder is an intelligent forensic system that identifies the **origin scanner** of digital documents by analyzing **scanner-specific noise patterns**. The project combines **image forensics**, **feature extraction**, and **hybrid deep learning** to support reliable source attribution in digital investigations.

---

## 🚀 Features
- Detects scanner source from scanned images  
- Uses noise residual & texture-based features  
- Hybrid model: **CNN + Machine Learning**  
- Supports **Flatfield, Official, and Wikipedia** document types  
- Streamlit-based interactive interface  
- Useful for **digital forensics & document authentication**

---

## 🧠 How It Works
1. **Image Preprocessing** – noise extraction & normalization  
2. **Feature Extraction** – statistical + texture features  
3. **Deep Learning** – CNN learns scanner noise patterns  
4. **Hybrid Classification** – CNN features + ML classifier  
5. **Prediction** – outputs the most likely scanner source  

---

## 🗂 Dataset
The dataset contains scanned documents from different sources:
- **Flatfield Images** – used to capture scanner noise patterns  
- **Official Documents** – real-world scanned files  
- **Wikipedia Prints** – controlled document scans  

Each category helps the model learn **distinct scanner fingerprints**.

---

## 🛠 Tech Stack
- **Python**  
- **TensorFlow / Keras**  
- **Scikit-learn**  
- **OpenCV**  
- **NumPy, Pandas**  
- **Streamlit**  

---

## ▶️ How to Run
```bash
git clone https://github.com/your-username/ai-trace-finder.git
cd ai-trace-finder
pip install -r requirements.txt
streamlit run app.py
