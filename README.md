Automatic Legal Clause Extraction Using NLP  

This project Automatically identifies and classifies legal clauses from contracts, agreements, and other legal documents using **Natural Language Processing (NLP)** and **Machine Learning (ML)**.  
It helps lawyers, legal researchers, and organizations save time and improve accuracy by automating the process of clause identification (e.g., Confidentiality, Liability, Termination, Payment, etc.).


##  Features
- Upload any **legal document** (.txt, .pdf, .docx)
- Automatic **preprocessing** (tokenization, lemmatization, stopword removal)
- **TF-IDF** and **BERT-based** feature extraction
- **Clause classification** using ML models (SVM / Logistic Regression / Legal-BERT)
- Simple **Flask-based web interface**
- Displays predicted **clause type** with confidence score
- Supports model retraining with new datasets
- Ensures **data privacy** (local document processing)

##  Tech Stack
| Component | Technology Used |
|------------|------------------|
| **Frontend** | HTML, CSS, JavaScript |
| **Backend** | Flask (Python) |
| **Machine Learning** | Scikit-learn, SpaCy, Transformers (BERT/Legal-BERT) |
| **Database** | SQLite / PostgreSQL |
| **IDE** | Visual Studio Code |
| **Version Control** | Git + GitHub |

Automatic-Legal-Clause-Extraction-Using-NLP/

│
├── app.py # Flask main application file
├── model/
│ ├── clause_model.pkl # Trained ML model
│ └── vectorizer.pkl # TF-IDF or embedding vectorizer
├── static/
│ ├── style.css # Frontend styling
│ └── script.js # Client-side logic
├── templates/
│ ├── index.html # Home UI
│ └── result.html # Output display page
├── dataset/
│ ├── legal_dataset.csv # Training data (clauses + labels)
│ └── sample_input.txt
├── requirements.txt # Required Python dependencies
├── README.md # Project documentation
└── LICENSE # Open-source license 

## ⚙️ Installation and Setup

### 1. Clone the repository
git clone https://github.com/<your-username>/Automatic-Legal-Clause-Extraction-Using-NLP.git
cd Automatic-Legal-Clause-Extraction-Using-NLP

### 2.Create and activate a virtual environment
python -m venv venv
venv\Scripts\activate     # On Windows
source venv/bin/activate  # On macOS/Linux

### 3. Install required libraries
pip install -r requirements.txt

### 4. Run the Flask application
python app.py

### 5. Open in browser
Visit: http://127.0.0.1:5000/

### Model Workflow
Upload Document: User uploads a legal text file.
Text Preprocessing: Tokenization, stopword removal, lemmatization.
Feature Extraction: TF-IDF or BERT embeddings generated.
Clause Classification: Trained ML model predicts clause type.
Output Display: Classified clauses are shown on a web dashboard.
Evaluation Metrics

🧑‍💻 Author

Sadiya Sultana
Department of Information Science and Engineering
CIT, Gubbi | 2025–2026

📫 Reach me at: sadiyasulthana@2004gmail.com

🌐 GitHub: https://github.com/sadiyaasultana

🪪 License

This project is licensed under the MIT License — feel free to modify and share for educational or research purposes.

<img width="1920" height="1080" alt="Screenshot (27)" src="https://github.com/user-attachments/assets/5d8f6fde-718c-4c0e-bd52-16f046b062f6" />



## 🏗️ Project Structure
