# Smart-resume-analysis-project-Data-analytics-and-ML

🧠📄 Smart Resume Analyzer

A Streamlit-based intelligent resume analysis & career recommendation system

🚀 Overview

Smart Resume Analyzer is a web-based application that analyzes a user’s resume and provides career-oriented insights using Natural Language Processing (NLP) and Machine Learning concepts.

The app helps users:

Understand their resume strength

Identify their career domain

Get skill improvement suggestions

Receive course & learning recommendations

Watch resume & interview preparation videos

It also includes an Admin Dashboard for viewing analytics and user data.

✨ Key Features
👤 User Side

📄 Resume upload (PDF)

📊 Resume score calculation

🧠 Skill extraction using NLP

🎯 Career field prediction
(Data Science, Web Dev, Android, iOS, UI/UX, etc.)

💡 Skill improvement suggestions

🎓 Course recommendations

🎥 Resume writing & interview prep videos

🔐 Admin Side

🔑 Secure admin login

📋 View all user resume data

📈 Data visualization using charts

📥 Download user data as CSV

🛠 Tech Stack
Category	Tools
Frontend	Streamlit
Backend	Python
NLP	NLTK, spaCy
Resume Parsing	pdfminer
Database	MySQL
Visualization	Plotly
Others	Pandas, PyMySQL, PIL
📂 Project Structure
Smart_Resume_Analyser_App/
│
├── App.py                # Main Streamlit application
├── Courses.py            # Course & YouTube recommendations
├── Classifier.py         # KNN-based skill classification logic
├── Uploaded_Resumes/     # Stores user-uploaded resumes
├── Logo/                 # App logos & icons
├── requirements.txt      # Project dependencies
└── README.md             # Project documentation

⚙️ How the Application Works

1️⃣ User uploads their resume (PDF)
2️⃣ Resume text is extracted using PDFMiner
3️⃣ NLP techniques extract:

Name

Email

Phone number

Skills
4️⃣ Resume is analyzed to:

Determine experience level

Predict career domain

Calculate resume score
5️⃣ System recommends:

Missing skills

Relevant courses

Helpful YouTube videos
6️⃣ User data is stored in MySQL database
7️⃣ Admin can visualize & download all user data

🧪 Installation & Setup
1️⃣ Clone the Repository
git clone https://github.com/your-username/Smart-Resume-Analyser-App.git

2️⃣ Open CMD in Project Folder

(Tip: Click address bar → type cmd → Enter)

3️⃣ Install Dependencies
pip install -r requirements.txt

4️⃣ Setup Database

Install XAMPP / WAMP

Start Apache and MySQL

MySQL runs on localhost (default port 3306)

Database and tables are created automatically by the app.

▶️ Run the Application

⚠️ Important: This is a Streamlit app — do NOT use python App.py

streamlit run App.py


The app will open in your browser at:

http://localhost:8501

🔑 Admin Login Credentials
Username: mlproject
Password: ml123

📊 Output Highlights

Resume score visualization

Skill tag display

Career recommendation charts

Downloadable admin reports

Interactive UI with Streamlit

📌 Use Cases

Students & freshers improving resumes

Career guidance platforms

Resume screening automation

Academic ML / NLP projects

📚 Learning Outcomes

Practical NLP implementation

Resume parsing techniques

Streamlit web app development

MySQL database integration

End-to-end ML project structure

👨‍💻 Author

Lakshya Shukla
Engineering Student | Python | ML | Data Analysis

⭐ Support

If you found this project useful:

⭐ Star the repository

🍴 Fork it

🧠 Improve it
