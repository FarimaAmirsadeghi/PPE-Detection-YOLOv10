# 🛡️ PPE Detection using YOLOv10

This project implements a YOLOv10-based deep learning model to detect Personal Protective Equipment (PPE) on construction workers, supporting real-time safety compliance monitoring.

---

## 📂 Project Contents

- `Final_DETECTPPE.ipynb`:  
  Main notebook for running predictions, visualizing detection results, and generating automated PDF/Word reports.
- `requirements.txt`:  
  Dependencies required to run the notebook in Python/Colab.
- 📄 Project report and presentation available upon request.

---

## 🧠 Model Summary

- **Model**: YOLOv10m (Ultralytics)
- **Precision**: 88.7%  
- **Recall**: 99.2%  
- **mAP@0.5**: 99.5%  
- **mAP@0.5:0.95**: 93.8%

---

## 🎯 PPE Classes Detected

- Helmet  
- Vest  
- Boots  
- Person

---

## 🚀 How to Run

1. Clone this repository or upload to [Google Colab](https://colab.research.google.com)
2. Install dependencies:

```bash
pip install -r requirements.txt
