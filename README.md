# GenAI Resume Screening System using NLP

## 📌 Project Overview
This project is a GenAI-based Resume Screening System that automatically evaluates and shortlists resumes by comparing them with a job description using semantic similarity. It uses modern NLP and GenAI embeddings to understand context rather than just keywords.

## 🚀 Features
- Upload one or multiple resume PDFs
- Automatic text extraction from resumes
- GenAI sentence embeddings (BERT-based)
- Semantic similarity matching
- Resume ranking with match percentage
- Automated shortlisting decision

## 🧠 Technologies Used
- Python
- Sentence Transformers (BERT: all-MiniLM-L6-v2)
- Natural Language Processing (NLP)
- Google Colab
- PyPDF2
- Scikit-learn
- Pandas

## 📂 Project Workflow
1. Upload resume PDF(s)
2. Extract text from resumes
3. Light text preprocessing
4. Generate GenAI embeddings
5. Compute cosine similarity with job description
6. Rank resumes and shortlist candidates

## ▶️ How to Run the Project
1. Clone or download this repository
2. Open `Resume_Screening_GenAI.ipynb` in Google Colab
3. Install dependencies from `requirements.txt`
4. Run all cells in order
5. Upload resume PDF(s) when prompted
6. View matching scores and shortlist results

## 📊 Output
The system displays:
- Resume file name
- Match percentage
- Shortlisting status (Shortlisted / Not Shortlisted)

## 🧪 Example Use Case
- HR resume screening automation
- Recruitment assistance tool
- Academic project on NLP / GenAI
- Resume shortlisting based on job relevance

## 🔮 Future Enhancements
- Skill gap analysis
- Support for DOCX resumes
- Web interface using Streamlit
- OpenAI embeddings integration

## 👤 Author
Your Name
