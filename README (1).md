# 🧠 Multi-Stage Brain Disease Classification Using MRI and Hybrid CNN

This project implements a two-stage deep learning pipeline for classifying brain-related diseases using MRI scans. It starts by detecting **brain tumors** using **T2-weighted MRIs**. If no tumor is found, it moves on to assess the likelihood and stage of **Alzheimer’s disease** using **T1-weighted MRIs**.

The model uses a custom **Hybrid CNN architecture** tailored for high accuracy in medical image classification and is built with scalability in mind — allowing future integration of diseases like **Parkinson’s**.

---

## 🗂️ Project Structure

```bash
├── /models              # Trained model weights and architectures
├── /data                # T1 and T2 MRI datasets (link or ref)
├── /notebooks           # Jupyter notebooks for training and evaluation
├── /scripts             # Python scripts for inference and preprocessing
├── README.md            # Project overview and usage guide
└── requirements.txt     # List of dependencies
```

---

## 📌 Workflow

1. **Brain Tumor Detection**
   - Input: T2 MRI images
   - Output: Tumor / No Tumor
   - Model: Custom hybrid CNN

2. **Alzheimer’s Disease Classification**
   - Triggered only if no tumor is detected
   - Input: T1 MRI images
   - Output: Alzheimer’s stage (Non-Demented, Mild, Moderate, Severe)

---

## 🧪 Tools & Technologies

- Python
- TensorFlow / PyTorch
- OpenCV, NumPy, scikit-learn
- Jupyter Notebooks

---

## 📊 Results (Example)

| Model Stage         | Accuracy | Precision | Recall |
|---------------------|----------|-----------|--------|
| Brain Tumor Detector | 95.2%    | 94.8%     | 96.1%  |
| Alzheimer’s Classifier | 93.5%    | 92.4%     | 94.0%  |

*Note: These are placeholder results. Replace with actual values from your training.*

---

## 📂 Dataset References

- Brain Tumor Dataset (T2 MRI): [Add link here]
- Alzheimer’s MRI Dataset (T1): [Add link here]

---

## 🚀 Future Work

- Integrate Parkinson’s classification using DAT scans or other modalities.
- Deploy as a web app or API for clinical usage.
- Implement attention mechanisms or 3D CNNs for better spatial understanding.

---

## ⚠️ Disclaimer

This project is for **educational and research purposes only**. Clinical use requires proper validation and regulatory approvals.

---

## 🤝 Contributions

Feel free to fork this repo, raise issues, or submit pull requests if you’re passionate about AI in healthcare!