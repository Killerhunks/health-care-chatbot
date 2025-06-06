# 🤖 HealthCare ChatBot

A machine learning–powered chatbot for disease prediction based on user-input symptoms. It uses a **Decision Tree** classifier and **Support Vector Machine (SVM)** for accurate diagnosis and offers **precautionary advice, severity analysis**, and **symptom descriptions**.

---

## 🚀 Features

- Predicts diseases based on symptoms using a trained ML model.
- Interactive chatbot with voice output (via `pyttsx3`).
- Dual-model diagnosis with Decision Tree and SVM.
- Gives severity-based health recommendations.
- Provides symptom descriptions and precautions.
- Pattern-matching to improve user input accuracy.

---

## 🧠 Tech Stack

- **Language**: Python 3.x  
- **ML Models**: Decision Tree, SVM (from scikit-learn)  
- **Libraries**:  
  - `pandas`, `numpy`, `scikit-learn` – data processing & ML  
  - `pyttsx3` – text-to-speech output  
  - `csv`, `re` – for data and input handling

---

## 📁 Project Structure

```bash
├── Data/
│   ├── Training.csv
│   └── Testing.csv
├── MasterData/
│   ├── symptom_Description.csv
│   ├── symptom_precaution.csv
│   └── symptom_severity.csv
├── healthcare_chatbot.py
├── requirements.txt
└── README.md
```

## ⚙️ How to Run

1. **Clone the repo**
   ```bash
   git clone https://github.com/YOUR-USERNAME/HealthCare-ChatBot.git
   cd HealthCare-ChatBot
   

2. **Create a virtual environment**
   ```bash
   python -m venv venv
   source venv/bin/activate
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the chatbot**
   ```bash
   python healthcare_chatbot.py
   ```