# 🚀 Task 1 – Beam Search Decoding for LSTM-based NMT Model

![Beam Search Diagram](https://miro.medium.com/v2/resize:fit:1100/format:webp/1*4OG8TlvJbAa9s7J5MZ8jQA.png)

This project implements **Beam Search decoding** to improve translation quality using a **pre-trained LSTM-based Neural Machine Translation (NMT)** model.  
This task is part of the **NullClass Data Science Internship Program** (17 June 2025 – 17 July 2025).

---

## 🎯 Objective

To apply Beam Search decoding in place of greedy decoding on a sequence-to-sequence model to enhance translation accuracy.

---

## 📁 Project Structure

```
├── beam_search_decoder.py       # Beam Search implementation
├── model_loader.py              # Code to load the pre-trained LSTM model
├── evaluate.py                  # Evaluation metrics and comparison
├── requirements.txt             # Python dependencies
├── model_weights/               # Folder with pre-trained weights (or GDrive link in README)
├── Task1_BeamSearch.ipynb       # Jupyter Notebook for demo and results
└── README.md                    # This file
```

---

## 📊 Evaluation Metrics

- Accuracy Score  
- Confusion Matrix  
- Precision and Recall  

The model achieved an accuracy of **[update with actual %]**, showing clear improvement over the greedy search baseline.

---

## 📦 Dependencies

All dependencies are listed in the `requirements.txt` file. Install using:

```bash
pip install -r requirements.txt
```

---

## 📁 Model Files

- Pre-trained model weights are included in the `model_weights/` folder.  
- If large, download them from [Google Drive Link Here].

---

## 🚀 Running the Code

Open the notebook:

```bash
jupyter notebook Task1_BeamSearch.ipynb
```

Follow the steps to load the model and apply beam search decoding.

---

## 📌 Notes

- GUI is **not** required for this task.  
- This implementation is part of a broader course-integrated application.

---

## 📄 Report

The complete internship report with task-wise documentation is included in the final submission as per NullClass guidelines.
