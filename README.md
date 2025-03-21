# Smart India Hackathon Workshop
# Date: 21/03/2025
## Register Number:212224040116
## Name: Hemapriyan.p
## Problem Title
SIH 1653: Web based Selector-Applicant Simulation Software
## Problem Description
Background: Recruitment and Assessment Centre (RAC) under DRDO, Ministry of Defence carries out interviews for applications received against advertised vacancies and for promotion to next higher grade for scientific manpower inducted within DRDO. Description: The process of interviewing is a challenging task. An unbiased objective interviewing process helps identify the right talent. The basic process of an interview involves posing a set of questions by an interviewer and thereafter evaluating responses from candidates. Thus, the questions asked should be relevant and match the area/ expertise of the applicant and the responses should also be of relevance w.r.t. the question asked. Expected Solution: The proposed solution should provide experts as well as candidates a real life Board Room experience, starting with initial ice-breaking questions leading to in-depth techno-managerial (depending on the level of candidate) questions. It shall also be able to provide a quantifiable score for experts as well as the candidate for the relevancy of questions w.r.t. the area/ expertise of the applicant. Similarly, candidate responses should also be graded for relevancy w.r.t. the question asked, finally assisting in arriving at an overall score for the subject knowledge of the candidate and thus his/ her suitability against the advertised post.

## Problem Creater's Organization


## Idea
1. Real-Life Board Room Simulation:
Objective: Create a simulated boardroom experience that makes the interview feel realistic and engaging for the candidates. The simulation should evolve from basic ice-breaker questions to more in-depth, domain-specific questions, creating a natural flow.
Implementation Ideas:

Virtual/Hybrid Platform: Create a virtual interview platform where both candidates and interviewers interact. This could be done through video conferencing software with custom features.
Customizable Scenarios: The platform should allow the interviewer to adapt the questions in real-time based on the candidate’s responses, adjusting from general questions to highly specialized technical or managerial queries.
Dynamic Questioning: The platform can have an AI that suggests follow-up questions based on the candidate’s previous responses, mimicking the dynamic nature of an in-person interview.
2. Relevancy of Questions to Candidate’s Expertise:
Objective: Ensure the questions are aligned with the job role and candidate’s background, thus helping in evaluating whether they have the required domain-specific knowledge.
Implementation Ideas:

Automated Question Generation: Use AI and Natural Language Processing (NLP) to generate or recommend interview questions based on:
The job description.
The resume/CV of the candidate.
The level of the position being applied for (junior, senior, managerial).
Domain Matching: A machine learning model could map the candidate’s expertise to relevant topics, ensuring that the questions target areas that are specific to the applicant's field, whether it's electronics, software, systems engineering, or another specialized area.
3. Grading & Scoring of Questions and Answers:
Objective: Quantify the relevancy and quality of the interview questions as well as the candidate’s responses, allowing for a transparent and objective evaluation.
Implementation Ideas:

Question Relevance Scoring: Each question could be scored for its relevance to the candidate’s background and the advertised role. For example, if a candidate has a background in electrical engineering, a question about software development would receive a lower relevance score.
Answer Relevance Scoring: Responses could be evaluated for their accuracy, depth, and relevance using NLP-based semantic analysis. The system could:
Compare responses against a database of ideal answers.
Measure the completeness and technical correctness of the answer.
Analyze the logical flow and coherence of the response.
Automated Scoring System: An automated scoring algorithm could assign numeric values to each question/response based on the above factors, providing a clear, quantitative assessment of the candidate’s performance.
4. Subject Knowledge Assessment:
Objective: Aggregate the scores from question relevance and response quality to generate an overall score for the candidate’s technical and managerial suitability for the advertised position.
Implementation Ideas:

Composite Scoring Model: Combine the scores from question relevance, answer quality, and other parameters (like communication skills, logical reasoning) to produce a final score.
Weighted Scoring: The scoring model could assign different weights to different aspects depending on the job role. For example, technical roles might place more weight on subject knowledge and problem-solving ability, while managerial roles might focus on leadership and communication skills.
Interview Analytics: The system could provide interviewers with detailed analytics, such as areas where the candidate performed well and areas where they could improve. This can help interviewers make more informed decisions and provide constructive feedback to candidates.


## Proposed Solution / Architecture Diagram
![hemapriyan p](https://github.com/user-attachments/assets/b9c60a1d-e576-4641-967a-15a01807d1cd)


## Use Cases
![web](https://github.com/user-attachments/assets/4b78f8a4-d44e-41eb-aee7-fe6bbdbad068)


## Technology Stack
1. Frontend (User Interface for Interview and Interaction)
Technology: React.js / Angular / Vue.js
Purpose: Provide a responsive and interactive interface for both interviewers and candidates. React.js (or any similar framework) allows for a dynamic user interface that adapts based on the ongoing interview.
2. Backend (Server-side Processing and Logic)
Technology: Node.js / Python (Django / Flask)
Purpose: Handle the logic for question generation, scoring algorithms, real-time data processing, and integration with databases. Python might be preferred for its NLP capabilities and machine learning integration.
3. Question Generation & NLP
Technology: Natural Language Processing (NLP) Libraries like spaCy, Hugging Face Transformers, GPT-based models (such as GPT-3)
Purpose: Automatically generate or recommend domain-specific interview questions based on the candidate's resume and job description. NLP can also be used to analyze and score the relevance of candidate responses.
4. Speech-to-Text Conversion
Technology: Google Cloud Speech-to-Text or AWS Transcribe
Purpose: Convert the candidate’s verbal answers into text for easier processing and analysis. This is crucial for real-time analysis and scoring.
5. Real-Time Interaction (Virtual Board Room)
Technology: WebRTC / Jitsi / Zoom API
Purpose: Allow seamless video/audio communication between the interviewer and the candidate. WebRTC provides low-latency video conferencing capabilities.
6. Database
Technology: PostgreSQL / MySQL / MongoDB
Purpose: Store candidate information, interview history, responses, and scores securely. Relational databases (PostgreSQL/MySQL) are ideal for structured data, while MongoDB can be used if flexibility in data storage is needed.

## Dependencies
Mapping service- 10 days

Data collection- 10 days

budget- rs.1000006

