# QAI Hackathon 2025 – Challenge 1 (QCNN)

This repository contains my complete solution for **Challenge 1** of the  
**QAI Hackathon 2025**.  
The goal was to design and evaluate a Quantum Convolutional Neural Network (QCNN)  
for the BreastMNIST classification task using the structure provided by the organizers.

---

## 📂 Project Structure

```
HACK_QAI_challenge_1/
├── Task1_QAI_Hack2025.ipynb # Exploratory analysis + baseline
├── Task2_QAI_Hack2025.ipynb # QCNN training & evaluation
├── qai_model.py # QCNN model architecture
├── docs.pdf # Official challenge description
├── qcnn_with_measurement.png # QCNN architecture diagram
├── QCNN_inference_pyc.zip # Precompiled inference utilities (provided)
├── requirements.txt
└── .gitignore

```

---

## 🚀 Setup & Installation

### 1. Clone the repository

```bash
git clone https://github.com/aleksojdanic/HACK_QAI_challenge_1.git
cd HACK_QAI_challenge_1
python -m venv .venv
.\.venv\Scripts\Activate.ps1
pip install -r requirements.txt

```
##📘 Usage
Launch Jupyter Notebook
```
jupyter notebook
```

Open:

- Task1_QAI_Hack2025.ipynb
- Task2_QAI_Hack2025.ipynb

Import the QCNN model directly
```
from qai_model import QCNNModel
```
##📌 Notes

- The dataset used in the challenge was partially private and is not included here.
- Virtual environments, caches, and large binary files are excluded via .gitignore.
- QCNN_inference_pyc.zip is included exactly as provided by the organizers.

##📝 License

Created for the QAI Hackathon 2025.
Feel free to reuse or modify.









