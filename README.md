# 📄 ATS (Applicant Tracking System) - Resume Screening

An **Applicant Tracking System (ATS)** built using Python and machine learning to analyze resumes, match them with job roles, and calculate ATS scores for candidates.  
This project supports analyzing resumes for roles like **Business Analyst**, **Software Engineer**, and **Consultant**, with a scoring system based on skills, experience, and job requirements.

---

## 🚀 Features
- **Resume Parsing** – Extracts text from PDF/DOCX resumes.
- **ATS Scoring** – Matches candidate profiles with job descriptions and calculates a score.
- **Role Matching** – Classifies resumes into relevant job categories.
- **Model Training** – Includes training scripts for custom datasets.
- **Data Storage** – Saves analysis history for future reference.
- **Easy to Run** – Start the ATS from the command line or integrate with your own UI.

---

## 📂 Project Structure
ats system-1/
│── app.py # Main application entry point
│── ats_scorer.py # ATS scoring logic
│── dataset_loader.py # Loads datasets for training
│── model_trainer.py # Trains the ML model
│── resume_analyzer.py # Main resume analysis functions
│── text_extractor.py # Extracts text from resumes
│── startup_check.py # Checks dependencies and environment
│── run_system.py # Script to run the ATS
│── requirements.txt # Python dependencies
│── setup.py # Installation setup
│── test_system.py # Test cases
│
├── data/
│ ├── comprehensive_training_dataset.csv
│ ├── analysis_history.csv
│ └── training_dataset_200.csv
│
├── models/
│ ├── field_classifier.pkl
│ ├── vectorizer.pkl
│ ├── performance_metrics.json
│ └── training_metadata.json

yaml
Copy code

---

## 🔧 Installation

1. **Clone the Repository**
```bash
git clone https://github.com/your-username/ats-system.git
cd ats-system
Create a Virtual Environment (Optional but Recommended)

bash
Copy code
python -m venv venv
source venv/bin/activate   # On macOS/Linux
venv\Scripts\activate      # On Windows
Install Dependencies

bash
Copy code
pip install -r requirements.txt
▶️ Usage
Run the ATS Application
bash
Copy code
python app.py
Run the Command-Line Version
bash
Copy code
python run_system.py
Train the Model
bash
Copy code
python model_trainer.py
📊 Dataset
comprehensive_training_dataset.csv – Contains labeled resume data for training.

training_dataset_200.csv – Smaller dataset for quick tests.

🛠️ Tech Stack
Language: Python 3.x

Libraries: scikit-learn, pandas, numpy, nltk, Flask (if using web mode)

Storage: CSV-based dataset storage

ML Models: Vectorization + Classifier

🤝 Contributing
Pull requests are welcome! Please ensure your code follows PEP8 standards and is well-documented.

📜 License!

This project is licensed under the MIT License – see the LICENSE file for details.

👨‍💻 Author
Shivam Singh
📧 Contact: shivampaytm19@gmail.com

![Uploading Screenshot 2025-08-14 at 7.09.39 AM.png…]()


