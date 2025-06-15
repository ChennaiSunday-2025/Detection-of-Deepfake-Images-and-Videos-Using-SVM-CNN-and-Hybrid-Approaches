# 🧠 Deepfake Detection System using SVM & SigLIP

A web-based deepfake image detection system built with **Django**, comparing the performance of **SVM** and **SigLIP (CLIP variant)** models for binary classification: `Real` vs `Fake`.

---

## 🚀 Features

* 🖼️ Upload images to test for deepfake detection
* 🧪 Compare results between:

  * **SVM-based Model** (with probability confidence)
  * **SigLIP/CLIP-based Model** (vision-language)
* 📊 View classification reports side by side
* 📁 Clean Django interface with multiple result pages

---

## 🛠️ Tech Stack

| Layer         | Technology         |
| ------------- | ------------------ |
| Backend       | Django (Python)    |
| ML Models     | SVM, SigLIP (CLIP) |
| Data Handling | Pandas, CSV, HTML  |
| File Handling | Django FileStorage |
| Frontend      | HTML, Bootstrap    |

---

## 📁 Folder Structure

```
deepfake_project/
│
├── deepfake_app/
│   ├── views.py
│   ├── utils_svm.py
│   ├── utils_siglip.py
│   ├── templates/
│   │   ├── upload_svm.html
│   │   ├── upload_siglip.html
│   │   ├── result_svm.html
│   │   ├── result_siglip.html
│   │   └── reports.html
│
├── media/
│   ├── Uploaded images
│   ├── svm_classification_report.csv
│   ├── siglig_classification_report.csv
│
├── manage.py
└── requirements.txt
```

---

## ⚙️ How to Run

1. Clone the repository

```bash
git clone https://github.com/your-username/deepfake-detector.git
cd deepfake-detector
```

2. Create a virtual environment and install dependencies

```bash
python -m venv env
source env/bin/activate  # or env\Scripts\activate on Windows
pip install -r requirements.txt
```

3. Run the server

```bash
python manage.py runserver
```

4. Open in browser:
   [http://127.0.0.1:8000/](http://127.0.0.1:8000/)

---

## 📊 Sample Result Pages

* **SVM Result**
  ✅ Label + Probability Breakdown
* **SigLIP Result**
  ✅ Real/Fake Score
* **Comparison Page**
  📈 Classification Report Tables

---

## 📬 Contact

📧 **[chennaisunday@gmail.com](mailto:chennaisunday@gmail.com)**
🌐 [www.chennaisunday.com](https://www.chennaisunday.com)

---

## 📌 License

This project is intended for educational and academic use.
