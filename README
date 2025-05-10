# AI Resume Screening & Candidate Ranking System

An AI-driven system that automates the process of resume screening and ranking based on job descriptions. Leveraging **Natural Language Processing (NLP)** and **Machine Learning (ML)** techniques, this system helps recruiters efficiently shortlist the best candidates by analyzing resumes and ranking them according to relevance.

## Features

- **Automated resume screening** using NLP and machine learning models.
- **Resume ranking** based on job description relevance.
- Built using **Python**, **Streamlit**, **Scikit-learn**, and **PyPDF2**.
- Easy-to-use web interface for uploading resumes and job descriptions.

## Tech Stack

- **Python**: Programming language used for backend development.
- **Streamlit**: Framework for creating the web app interface.
- **Scikit-learn**: For machine learning tasks, including vectorization and similarity calculation.
- **PyPDF2**: For PDF resume text extraction.
- **Pandas**: For data manipulation and results display.

## Project Structure

AI-Resume-Screening/
├── 📄 app.py # Streamlit app to interact with the user
├── 📄 requirements.txt # List of dependencies
├── 📄 README.md # Project documentation
└── 📄 .gitignore # Git ignore file for unnecessary files

## Installation

Follow the steps below to install and run the project:

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/AI-Resume-Screening.git
cd AI-Resume-Screening
pip install -r requirements.txt
streamlit run app.py
The application will be available at http://localhost:8501/ in your web browser.


Usage
1. Enter Job Description
In the web interface, paste the job description for the role you are hiring for.

2. Upload Resumes
Upload one or more PDF resume files. These files should be in PDF format, and the text content of the resumes will be extracted for analysis.

3. Resume Ranking
After uploading the resumes and entering the job description, click the "Rank Resumes" button.

The system will rank the uploaded resumes based on how similar they are to the job description.

The ranked resumes, along with their similarity scores, will be displayed.

Ranking Algorithm
The resumes are ranked based on their cosine similarity to the provided job description. Here's a brief overview of how the system works:

Text Extraction: The system extracts text from uploaded PDF resumes using PyPDF2.

TF-IDF Vectorization: The job description and resumes are vectorized using the TF-IDF (Term Frequency-Inverse Document Frequency) method.

Cosine Similarity Calculation: The cosine similarity is calculated between the job description and each resume vector to determine their relevance.

Ranking: Resumes are ranked from the highest to the lowest based on their similarity score to the job description.

Requirements
Python 3.6+

Libraries:
streamlit
PyPDF2
scikit-learn
pandas

To install the libraries, run:
pip install streamlit PyPDF2 scikit-learn pandas
Example Output
The web app will display a table showing the resumes and their corresponding similarity scores. Higher similarity scores indicate better matches for the job description.
| Resume      | Similarity Score |
| ----------- | ---------------- |
| resume1.pdf | 0.85             |
| resume2.pdf | 0.79             |
| resume3.pdf | 0.65             |
Future Improvements
Support additional file formats like DOCX, RTF, etc.

Advanced models: Integrate pre-trained NLP models like BERT for better semantic understanding.

Improved ranking algorithms: Enhance ranking with additional features such as skills matching or keyword extraction.

Contact
For inquiries or collaborations, you can reach out at your.email@example.com.

---

### Key Sections in the README:
1. **Project Overview**: Brief description of the system’s purpose.
2. **Features**: Highlights the main functionality, including resume ranking and screening.
3. **Tech Stack**: Specifies the libraries and technologies used.
4. **Installation**: Instructions for setting up the project locally.
5. **Usage**: Steps on how to use the application (job description input, resume upload, ranking).
6. **Ranking Algorithm**: Brief explanation of how the system ranks resumes.
7. **Requirements**: Specifies Python version and required libraries.
8. **Demo**: Example output showing ranked resumes.
9. **Future Improvements**: Potential enhancements for the project.
10. **Contact**: Your email or contact information for collaboration/inquiries.

---

You can replace `your.email@example.com` with your actual email and update the **GitHub repository URL** as well.

Let me know if you need any changes or additions!
