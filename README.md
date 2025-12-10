# SummAI – AI Text Summarizer (Flask + NLP)

SummAI is an AI-powered text summarizer that supports both **Abstractive** and **Extractive** summarization.  
It uses Flask, Transformers, PyTorch, Sumy, and a custom frontend with HTML templates and CSS.

---

##  Project Structure

SummAI/
 ├── app.py                - Main Flask backend  
 ├── requirements.txt      - Python dependencies  
 ├── render.yaml           - Deployment configuration  
 ├── static/  
 │     └── style.css       - Frontend styling  
 ├── templates/  
 │     └── index.html      - UI HTML template  
 ├── Project_Report.pdf    - Project Report  
 ├── Project_Presentation.pptx - PPT  
 └── README.md             - Documentation  

---

##  Features

###  Abstractive Summarization
- Uses **facebook/bart-large-cnn**  
- Falls back to **t5-base**  
- Produces rewritten, paraphrased summaries  

###  Extractive Summarization
- Uses **TextRank (Sumy)**  
- Finds important original sentences  

###  Output Formats
- Standard text  
- Paragraph format  
- Bullet points  

###  UI & Frontend
- Clean modern design  
- Dark mode support  
- Responsive layout  
- Styled using **style.css**  
- Page rendered using **templates/index.html**

---

##  Installation
pip install -r requirements.txt

Run the Flask app:

Then open in browser:

---

##  NLP Models Used
- facebook/bart-large-cnn  
- t5-base  
- Sumy TextRank  

---

##  Purpose
SummAI helps generate short summaries for:
- Research papers  
- Assignments  
- Articles  
- Business documents  
- Notes preparation  

---

##  Developer
**Gnana Saisree**



Install dependencies:
pip install -r requirements.txt
