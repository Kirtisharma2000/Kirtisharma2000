<div align="center">

# Hey, I'm Kirti Sharma 👋

### ML Developer · NLP · AI Systems · Open to Internships & Fresher Roles

</div>

---

## 👩‍💻 About Me

I'm an ML developer from India who builds end-to-end AI systems — not just models, but full working applications with backends, UIs, and real results.

I completed a **9-month AI minor from IIT Ropar** covering ML, deep learning, NLP, and computer vision — and I've been building independently ever since.

- 🔭 Currently building a **Chatbot with Rasa** and a **Book Recommender System**
- 🌱 Learning **deployment** and **MLOps basics**
- 💬 Ask me about **Python, Scikit-learn, NLP, Flask, XGBoost**
- 📫 Reach me at **kskirtisharma2000@gmail.com**
- ⚡ Looking for **internships & fresher roles in ML/AI**

---

## 🛠️ Tech Stack

### ML & Data
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-FF6600?style=for-the-badge&logoColor=white)

### Deep Learning
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras&logoColor=white)

### Dev & Deployment
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)

---

## 🚀 Projects

### 🔍 [SMS / Email Spam Classifier](https://github.com/Kirtisharma2000/sms-spam-classifier)
Classifies messages as spam or ham with **97% accuracy** using an ensemble Voting Classifier

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat&logo=streamlit&logoColor=white)
![NLTK](https://img.shields.io/badge/NLTK-154F5B?style=flat&logoColor=white)

- Full NLP pipeline: tokenization, stopword removal, stemming, TF-IDF vectorization
- Combined SVM + Decision Tree + Extra Trees into a **Voting Classifier**
- Deployed as a live interactive web app using Streamlit

[![View Repo](https://img.shields.io/badge/View%20Repo-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Kirtisharma2000/sms-spam-classifier)

---

### 🧠 [AI Emotion Tracker](https://github.com/Kirtisharma2000/AI_emotion_tracker)
Predicts emotional state from journal text + metadata and recommends personalised actions

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat&logo=flask&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-FF6600?style=flat&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)

- Combined TF-IDF (5000 features, bigrams) with metadata via **sparse matrix stacking**
- Used **Logistic Regression** (tuned with GridSearchCV) for emotion classification
- Used **XGBRegressor** (tuned with RandomizedSearchCV) for intensity prediction (scale 1–5)
- Built a **rule-based decision engine** — maps state + intensity + context to recommended actions with timing
- Added **uncertainty modeling** — flags predictions with confidence below 0.55
- Ran **3-way ablation study**: combined text + metadata outperformed both text-only and metadata-only baselines
- Deployed with Flask backend and HTML/CSS frontend

[![View Repo](https://img.shields.io/badge/View%20Repo-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Kirtisharma2000/AI_emotion_tracker)

---

### 🤖 [Chatbot with Rasa](https://github.com/Kirtisharma2000/Chatbot_with_Rasa)
Conversational AI chatbot with NLU pipeline, Flask backend, and custom frontend *(In Progress)*

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Rasa](https://img.shields.io/badge/Rasa-5A17EE?style=flat&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat&logo=flask&logoColor=white)

[![View Repo](https://img.shields.io/badge/View%20Repo-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Kirtisharma2000/Chatbot_with_Rasa)

---

### 📚 [Book Recommender System](https://github.com/Kirtisharma2000/Book_recommender_system)
> Two-engine recommendation system — popularity-based + collaborative filtering on 1.1M+ real ratings

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat&logo=flask&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)

- Processed **1.1M+ ratings** across 271,360 books and 278,858 users (Amazon Book-Crossing dataset)
- Built user-item pivot table (706 books × 810 active users); applied **cosine similarity** to generate top-5 personalized recommendations
- Input `1984` → returns `Animal Farm`, `The Handmaid's Tale`, `Brave New World` — based on real user rating patterns
- Popularity engine surfaces top 50 books filtered by minimum 250 ratings and average score; deployed via **Flask** + HTML/CSS

[![View Repo](https://img.shields.io/badge/View%20Repo-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Kirtisharma2000/Book_recommender_system)
---

## 📊 GitHub Stats

<div align="center">

![Kirti's GitHub Stats](https://github-readme-stats.vercel.app/api?username=Kirtisharma2000&show_icons=true&theme=tokyonight&hide_border=true&count_private=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Kirtisharma2000&layout=compact&theme=tokyonight&hide_border=true)

![GitHub Streak](https://streak-stats.demolab.com?user=Kirtisharma2000&theme=tokyonight&hide_border=true)

</div>

---

## 📜 Certifications

| Certificate | Issuer |
|---|---|
| 🎓 AI Minor (9 months) — ML, DL, NLP, CV | IIT Ropar |
| 🏅 Python (Basic) | HackerRank |
| 🏅 SQL (Basic) | HackerRank |
| 🏅 Problem Solving (Basic) | HackerRank |

---

## 🤝 Let's Connect

I'm open to internships, fresher ML roles, freelance AI projects, or just a good conversation about AI.

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/kirti-sharma-bba460245)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:kskirtisharma2000@gmail.com)

</div>

---

<div align="center">

![Profile Views](https://komarev.com/ghpvc/?username=Kirtisharma2000&color=blueviolet&style=flat-square&label=Profile+Views)

</div>
