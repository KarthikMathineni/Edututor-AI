📘 EduTutor AI
EduTutor AI is an AI-powered education platform that empowers students and teachers with intelligent tools for learning, assessment, and knowledge reinforcement.
Built with FastAPI, Streamlit, and Firebase, it delivers an interactive and modern experience, combining dynamic quiz generation, virtual assistance, summarization, and flashcards—all powered by cutting-edge language models.

🚀 Features

✅ Student & Teacher Authentication

Sign up and log in securely using Firebase Authentication

Support for Google login and email/password credentials

✅ Dynamic Quiz Generator

Generate quizzes dynamically based on:

Topic

Difficulty level

Powered by IBM Granite large language model

✅ Quiz Attempt & History

Students can attempt quizzes and submit answers

View past quiz attempts and scores

✅ Teacher Dashboard

Teachers can review student performance and quiz results  

✅ AI Summarizer

Summarize any text or document to create concise learning material

✅ AI Flash Cards Generator

Automatically generate flashcards from text to aid in revision and memorization

✅ Virtual Assistant

An AI assistant to answer student queries interactively

✅ Modern Themed UI

Professional design with:

Sidebar navigation with icons

Clean, responsive layout

🛠️ Tech Stack


Backend: FastAPI

Frontend: Streamlit

Authentication & Database: Firebase Authentication + Realtime Database

AI Models: IBM Granite (ibm/granite-3-2b-instruct)

⚙️ API Endpoints
Endpoint	Description
/generate-quiz	Generate quizzes based on topic & difficulty
/save-quiz-response	Save student quiz submissions
/student-history	Retrieve past quiz attempts
/summarize-text	Summarize input text
/generate-flashcards	Create flashcards from input text

✨ How to Run


1️⃣ Clone the repository

bash
Copy
Edit
git clone https://github.com/KarthikMathineni/Edututor-AI.git
cd Edututor-AI


2️⃣ Install dependencies

bash
Copy
Edit
pip install -r requirements.txt


3️⃣ Set up environment variables

Firebase credentials

IBM API Key and Endpoint

(You can create a .env file to store them.)

4️⃣ Start the FastAPI server

bash
Copy
Edit
uvicorn main:app --reload


5️⃣ Launch the Streamlit frontend

bash
Copy
Edit
streamlit run app.py
🎯 Future Improvements
Add multilingual support

Enable document upload for summarization and flashcards

Analytics dashboard for teachers and admins

Gamification for student engagement

🙏 Acknowledgments

IBM Granite

Firebase

Streamlit

FastAPI

💡 Contributing
Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

                                                                          👤 Developed By Karthik Mathineni
