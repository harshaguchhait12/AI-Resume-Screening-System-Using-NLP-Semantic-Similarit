# AI-Resume-Screening-System-Using-NLP-Semantic-Similarit

##  Project Overview

The **AI Resume Screening System** is a Machine Learning and NLP-based application designed to automate the resume screening process. It helps recruiters efficiently shortlist candidates by analyzing resumes and comparing them with job descriptions using **semantic similarity techniques**.

---

##  Objective

* Automate manual resume screening
* Improve hiring efficiency
* Rank candidates based on relevance
* Extract skills and match with job requirements

---

##  Key Features

✔ Upload resumes (PDF, DOCX, TXT)
✔ Automatic text extraction
✔ NLP-based preprocessing
✔ Skill extraction engine
✔ Semantic similarity matching
✔ Candidate ranking system
✔ CSV report download

---

##  Project Architecture

1. Resume Upload
2. Text Extraction
3. NLP Preprocessing
4. Feature Engineering
5. Semantic Similarity
6. Candidate Ranking
7. Output Generation

---

##  Tech Stack

* **Programming Language:** Python
* **Libraries:**

  * pandas, numpy
  * nltk, spaCy
  * scikit-learn
  * sentence-transformers
* **Tools:**

  * pdfplumber, PyPDF2, python-docx
  * Google Colab / Jupyter Notebook
  * Streamlit (for UI)

---

##  Project Structure

```
resume-screening/
│── app.py
│── utils.py
│── skill_extractor.py
│── similarity.py
│── requirements.txt
│── data/
│   ├── resumes/
│   ├── job_description.txt
```

---

##  Installation & Setup

### 1️ Clone the Repository

```bash
git clone https://github.com/your-username/resume-screening.git
cd resume-screening
```

### 2️ Install Dependencies

```bash
pip install -r requirements.txt
```

### 3️ Run the Project

For Streamlit:

```bash
streamlit run app.py
```

For Colab:

* Upload resumes
* Run all cells step-by-step

---

##  How It Works

###  Step 1: Resume Parsing

Extracts text from resumes using:

* PDF → pdfplumber / PyPDF2
* DOCX → python-docx

###  Step 2: NLP Preprocessing

* Lowercasing
* Stopword removal
* Tokenization
* Lemmatization

###  Step 3: Skill Extraction

* Uses predefined skill dictionary
* Identifies technical skills from resumes

###  Step 4: Semantic Similarity

* Model: **all-MiniLM-L6-v2**
* Technique: **Cosine Similarity**
* Compares resume with job description

### Step 5: Ranking

* Based on similarity score
* Outputs ranked candidates

---

##  Output Example

```
Resume1.pdf → 87.5% match
Skills: ['python', 'machine learning', 'sql']

Resume2.docx → 72.3% match
Skills: ['java', 'html', 'css']
```

---

##  Future Enhancements

* Use advanced models (BERT, GPT)
* Add experience-based filtering
* Improve UI/UX
* Deploy on cloud platforms
* Integrate real-time job APIs

---

##  Team Members

* Tufan Bera
* Soumaditya Mukherjee
* Jeet Das
* Harsha Guchhait
* Debajyoti Parui

---


---

## 🙌 Acknowledgements

* Sentence Transformers
* Scikit-learn
* NLTK
* Streamlit

---

## ⭐ If you like this project

Give it a ⭐ on GitHub!
