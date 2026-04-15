Project Overview

Recruiters often spend a lot of time manually reviewing resumes. This project simplifies the process by:

- Extracting skills from resumes

- Converting text into numerical features using TF-IDF

- Comparing resumes with job descriptions using cosine similarity

- Ranking candidates based on relevance

Features

1 Automated resume parsing  

2 Skill extraction using regex  

3 TF-IDF based text vectorization  

4 Cosine similarity matching  

5 Candidate ranking system  

6 Synthetic dataset for testing

Tech Stack

- Python 

- Pandas

- Scikit-learn

- Regular Expressions (re)

- NLP (TF-IDF Vectorizer)

Project Structure

AI-Resume-Screening-System/
│
├── Resume_Screening.ipynb # Main notebook
├── README.md # Project documentation
└── requirements.txt # Dependencies

How It Works

1. Dataset Creation

- Synthetic resumes dataset is created with:

   - Skills

   - Experience

   - Education

  - Certifications

2. Skill Extraction

- Extracts skills using pattern matching (regex)

3. Text Vectorization

- Converts resumes into numerical vectors using TF-IDF

4. Similarity Calculation

- Uses cosine similarity to compare resumes with job descriptions

5. Ranking Candidates

- Candidates are ranked based on similarity score

Example Use Case

Input:

- Job Description: "Python, SQL, Machine Learning"

Output:

- Ranked list of candidates best matching the job



Installation

bash
git clone https://github.com/your-username/AI-Resume-Screening-System.git
cd AI-Resume-Screening-System
pip install -r requirements.txt

Usage

Open the notebook:

jupyter notebook Resume_Screening.ipynb

Future Improvements

1 Add real resume dataset

2 Improve NLP with advanced models (BERT, spaCy)

3 Build a web app (Streamlit / Flask)

4 Add job description input UI

5 Improve skill extraction accuracy

License

This project is open-source and available under the MIT License.

Author

Ridhima




