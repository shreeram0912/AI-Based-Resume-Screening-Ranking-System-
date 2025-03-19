# AI-Based-Resume-Screening-Ranking-System

### Introduction

* The recruitment process is a crucial aspect of human resource management, and with the increasing number of job applicants, automating resume screening has become essential. Traditional hiring methods require 
  recruiters to manually evaluate resumes, which is time-consuming and prone to human bias. To address these challenges, AI-driven resume screening systems have gained significant attention.
* The AI Resume Screening & Ranking System utilizes Natural Language Processing (NLP) and Machine Learning (ML) to automate resume evaluation, extract relevant information, and rank candidates based on their skills 
  and experience. By leveraging advanced data processing techniques, this system enhances the efficiency of recruiters, reduces hiring time, and ensures fair candidate assessment.
* This project aims to develop an intelligent resume screening system that provides accurate and unbiased resume analysis, helping recruiters make informed decisions efficiently.

### Abstract
* The AI-Powered Resume Screening and Ranking System is a web-based solution designed to automate the process of resume evaluation and provide personalized recommendations for job seekers. By utilizing AI 
  algorithms and Natural Language Processing (NLP), the system analyzes resumes uploaded by candidates, extracting key information such as contact details, skills, experience level, and other essential data. Based 
  on this analysis, the system suggests suitable career fields (e.g., Data Science, Web Development, Android Development) aligned with the candidate's expertise. 
* The system further enhances the candidate's profile by offering skill recommendations to improve job prospects and providing suggestions for relevant online courses. Additionally, it evaluates the quality of the 
  resume, assigning a resume score based on the inclusion of essential sections such as Objective, Achievements, Projects, and Hobbies. Candidates are also provided with resume writing tips and interview 
  preparation videos to boost their chances of landing a job. 
* For the Admin side, the system integrates with a MySQL database to store candidate data. Admin users can view and analyze candidate profiles, generate reports, and visualize trends, such as the most common 
  predicted job fields and experience levels, through pie charts. 
* This project leverages AI, NLP, and data analytics to streamline the hiring process, making it more efficient for recruiters and offering valuable insights for job seekers. Ultimately, the system helps both 
  candidates and recruiters achieve better job matching and improved hiring outcomes.

### System Design
Provide a system architecture diagram to represent the overall workflow of the project. 

The diagram should depict: 
1. User Interface (Streamlit) 
  * Users can upload their resumes (PDF).
  * Admins can manage data and view analytics. 
2. Resume Parsing & Processing 
   * pdfminer3 extracts text from resumes.
   * pyresparser analyzes resume content.
   * NLTK and spaCy process text data. 
3. Skill & Job Recommendation 
   * Keywords are matched with predefined job roles.
   * Recommended skills and courses are suggested. 
4. Database (MySQL) 
   * User data is stored (name, email, resume score, recommendations).
   * Admins can access and analyze the database. 
5. Visualization & Reporting 
   * Plotly generates charts.
   * Reports can be downloaded in CSV format. 
6. External Integrations 
   * yt_dlp fetches YouTube videos for career guidance.
   * AI-driven recommendations are displayed.

### Requirement Specification 
This section outlines the hardware and software requirements needed to implement the AI Resume Screening & Ranking System. 

Hardware Requirements: 
* Processor: Intel Core i5 or higher (or equivalent AMD Ryzen)
* RAM: 8GB or more (16GB recommended for faster performance)
* Storage: Minimum 50GB free space (for database and dependencies)
* Operating System: Windows 10/11, macOS, or Linux (Ubuntu preferred)
* Internet Connection: Required for fetching online resources and installing dependencies 
 
Software Requirements: 
* Programming Language: Python 3.12
* Libraries & Dependencies:
* streamlit – for building the web application
* spacy – for Natural Language Processing (NLP)
* pymysql – for connecting to the MySQL database
* pdfminer3 – for extracting text from resumes in PDF format
* yt_dlp – for fetching YouTube video information
* nltk – for text processing and stopwords removal
* pyresparser – for resume parsing
* plotly.express – for creating data visualizations
* PIL (Pillow) – for handling images
* base64 – for encoding data for downloads
* Database: MySQL
* Development Tools:
* VS Code (for coding and debugging)
* MySQL Workbench (for database management)
* GitHub (for version control)
* Other Tools:
* pip – for package management
* virtualenv (optional) – for dependency isolation

### Implementation and Result

#### Home Screen before uploading resume:
![image](https://github.com/user-attachments/assets/f27d003a-17bd-4560-b0fb-22e00bd0e2bf)
#### Home Screen after uploading resume:
![image](https://github.com/user-attachments/assets/139c2a1c-ff5f-457a-9fb0-adf334012a40)
![image](https://github.com/user-attachments/assets/52c57c6a-cb2e-4bb2-89cb-94b776b968cc)
![image](https://github.com/user-attachments/assets/c991c0cc-b4b8-47f4-b4fc-b93a7c4beab3)
![image](https://github.com/user-attachments/assets/00d4545c-cbbb-454d-9033-43050f73e1f4)
#### Home Screen of Admin Page:
![image](https://github.com/user-attachments/assets/8bebd039-b09a-42c4-a2de-ff0e14f00bf7)
![image](https://github.com/user-attachments/assets/7ccf330f-4408-4496-be24-42e49a18dfcf)
![image](https://github.com/user-attachments/assets/695901cc-24a9-4550-8bb3-ce4f4b9e5202)
![image](https://github.com/user-attachments/assets/8e5d0fdf-3aa5-477f-81b9-378f5909d3d4)

### Future Work
* To further enhance the AI Resume Screening & Ranking System, the following improvements and developments can be considered:
* Enhanced NLP Techniques: Incorporating advanced NLP models like GPT-based analysis for better resume parsing and skill matching.
* Machine Learning Integration: Implementing machine learning algorithms to predict job fit based on historical hiring data.
* Support for More File Formats: Extending compatibility to process resumes in DOCX, TXT, and other popular formats.
* Real-time Resume Feedback: Providing instant suggestions for resume improvements before submission.
* Expanded Database Support: Allowing integration with NoSQL databases like MongoDB for scalability.
* Multilingual Processing: Supporting multiple languages for international job applicants.
* AI-based Interview Preparation: Developing features that generate personalized interview questions based on resume content

### Conclusion:  
The AI Resume Screening & Ranking System has demonstrated its potential in automating and improving the recruitment process. By leveraging natural language processing, data analysis, and visualization techniques, the system provides efficient resume screening, skill recommendations, and career guidance. The project significantly reduces the time spent by recruiters in evaluating resumes while 
enhancing the chances of candidates securing relevant job opportunities. Future enhancements, such as machine learning-based predictions and multilingual support, can further improve the system’s efficiency and usability, making it a valuable tool for modern hiring practices.

### REFERENCES 
[1]. Saomya Choudhari, for continuous guidance and encouragement, which have been 
invaluable throughout this project. 
[2]. P Raja, for mentorship and constructive feedback that played a crucial role in 
completing the project. 
[3]. Pavan Sumohana, for providing critical insights and advice that contributed to the 
project's success. 
[4]. Briit 🇬🇭🇺🇲 (Data Science & AI Mentor on YouTube), for online tutorials and 
resources that helped in understanding complex AI and Data Science concepts. 
[5]. OpenAI's ChatGPT, for assistance in research, development, and structuring the 
project effectively. 
