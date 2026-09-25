
# AI-Powered Smart Interview Assessment

## Team Members
| Name                  | Roll Number   |
| --------------------- | ------------- |
| Krishna Chaitanya     | 2420090077    |
| Chaitanya Karthik     | 2420090030    |
| V.Sai Dhanush         | 2420030162    |

## Supervisor
Dr. K. Swanthana

## Abstract
Recruitment is a time-consuming process for organizations due to 
manual resume screening and interviews. This project proposes an AIPowered Virtual Interview and Candidate Assessment Platform
that automates the initial hiring process using Artificial Intelligence, 
Natural Language Processing (NLP), and Speech Processing. The 
system first analyses the candidate's resume and compares it with the 
job description to perform resume shortlisting. Shortlisted candidates 
attend an AI-based voice interview where the AI asks domain-specific 
technical questions based on the candidate's resume and job 
requirements. Candidate responses are converted into text using the 
Whisper Speech-to-Text model and evaluated using Transformer-based 
language models such as BERT and Sentence Transformers. The 
system also performs speech emotion analysis and communication 
assessment to estimate confidence and speaking quality. A short 
domain-specific coding assessment is conducted at the end of the 
interview. Finally, the platform generates an AI-based evaluation report 
containing resume matching score, technical performance, 
communication score, coding score, confidence analysis, and an overall 
hiring recommendation for HR. The proposed system aims to provide 
a faster, fairer, and more intelligent recruitment process.
## Setup Instructions
1. Clone this repository.
2. Install dependencies: `pip install -r requirements.txt`
3. Add datasets in `/data`.
4. Run the application: `streamlit run app.py`

## Project Structure
- `/src` → source code
- `/docs` → documentation
- `/data` → datasets
- `/results` → outputs
- `/reports` → project reports
- `/README.md` → overview and instructions
