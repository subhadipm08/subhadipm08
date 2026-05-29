<h1 align="center">Hi, I'm Subhadip Mudi 👋</h1>

<p align="center">
  <b>Backend Developer &nbsp;·&nbsp; ML Engineer &nbsp;·&nbsp; CSE-AIML @ Haldia Institute of Technology</b><br/>
  <i>Graduating 2027 &nbsp;|&nbsp; Open to SDE · Backend Engineer · ML Engineer Roles &nbsp;|&nbsp; West Bengal, India</i>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/subhadip-mudi-5a53b4298/">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white" />
  </a>
  <a href="https://leetcode.com/u/subha__123/">
    <img src="https://img.shields.io/badge/LeetCode-FFA116?style=flat-square&logo=leetcode&logoColor=white" />
  </a>
  <a href="https://www.geeksforgeeks.org/profile/subhadipj4l6">
    <img src="https://img.shields.io/badge/GeeksForGeeks-2F8D46?style=flat-square&logo=geeksforgeeks&logoColor=white" />
  </a>
</p>

---

## About Me

I'm a final-year **Computer Science (AIML)** student at Haldia Institute of Technology who builds and **ships** production-ready software. I work across the backend, ML, and deployment stack — from designing real-time WebRTC systems to containerizing and deploying ML models to the cloud.

- 🎓 B.Tech CSE-AIML, Haldia Institute of Technology (2026)
- 💼 Seeking **SDE / Backend Engineer** and **ML Engineer** roles
- 🚀 Projects deployed on **AWS EC2**, **Vercel**, **Render**, and **Docker Hub**
- 📫 Reach me: [LinkedIn](https://www.linkedin.com/in/subhadip-mudi-5a53b4298/)

---

## 🛠 Tech Stack

**Languages**

![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

**Backend & Real-Time**

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-000000?style=flat-square&logo=express&logoColor=white)
![Socket.io](https://img.shields.io/badge/Socket.io-010101?style=flat-square&logo=socket.io&logoColor=white)
![WebRTC](https://img.shields.io/badge/WebRTC-333333?style=flat-square&logo=webrtc&logoColor=white)
![REST API](https://img.shields.io/badge/REST_API-FF6C37?style=flat-square&logo=postman&logoColor=white)

**Databases & Caching**

![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)

**ML & Data**

![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)

**Cloud**

![AWS EC2](https://img.shields.io/badge/AWS_EC2-FF9900?style=flat-square&logo=amazonaws&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)
![Render](https://img.shields.io/badge/Render-46E3B7?style=flat-square&logo=render&logoColor=black)

**Tools**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

---

## 🚀 Projects

### 🎥 [meetix](https://github.com/subhadipm08/meetix) &nbsp;·&nbsp; [`Live Demo`](https://meetixchat.vercel.app/)

> Production-grade real-time P2P video chat and messaging platform.

- Built WebRTC signaling with Node.js + Socket.io; STUN integration for NAT traversal and direct P2P media streams
- Architected a decoupled system: React + Vite frontend on **Vercel**, Node.js + Socket.io backend on **AWS EC2**
- Ran Dockerized **MongoDB** and **Redis** containers; used **NGINX** as a reverse proxy with **Let's Encrypt SSL** via Certbot
- Implemented JWT authentication and OTP email verification; set up **CI/CD pipeline** with GitHub Actions
- **Stack:** JavaScript · Node.js · Express · Socket.io · WebRTC · MongoDB · Redis · Docker · NGINX · AWS EC2 · Vercel

---

### 🎬 [movie-recommendation-system](https://github.com/subhadipm08/movie-recommendation-system) &nbsp;·&nbsp; [`Live Demo`](https://movie-recommendation-system-f1hm.onrender.com) &nbsp;·&nbsp; [`Docker Hub`](https://hub.docker.com/repository/docker/subhadip08/movie-recommender/)

> Content-based movie recommender using NLP and cosine similarity — Dockerized and deployed.

- Built NLP pipeline using **TF-IDF vectorization** and **cosine similarity** on movie metadata (genres, cast, keywords, overview)
- Integrated **TMDB API** to fetch and display live movie posters for recommendations
- Containerized the full Flask app with **Docker** and published to **Docker Hub**; deployed live on **Render**
- Precomputed similarity matrix serialized as `.pkl` for fast inference at runtime
- **Stack:** Python · Flask · scikit-learn · NLTK · Pandas · TMDB API · Docker · Render

---

### 🏦 [loan-approval-system](https://github.com/subhadipm08/loan-approval-system)

> End-to-end ML web app for loan approval prediction with tuned models and a Flask UI.

- Trained and compared **Random Forest** (ROC-AUC ~0.997) and **SVM** (ROC-AUC ~0.995) with cross-validation and hyperparameter tuning
- Performed full EDA — identified CIBIL score as the strongest predictor; engineered Loan-Income Ratio feature
- Built a **Flask web application** with model selection (RF / SVM) and real-time prediction UI
- **Stack:** Python · scikit-learn · Pandas · Flask · HTML/CSS

---

### 📝 [notes-crud-api](https://github.com/subhadipm08/notes-crud-api)

> Clean RESTful Notes API with MongoDB Atlas integration.

- Designed modular REST architecture with proper error handling, input validation, and timestamp support
- **Stack:** Node.js · Express.js · MongoDB Atlas · Mongoose

---

## 📊 GitHub Stats

<p align="center">
  <img src="https://streak-stats.demolab.com/?user=subhadipm08&theme=github-dark-blue&hide_border=true" />
</p>

---

## 📬 Connect With Me

| | |
|---|---|
| 💼 LinkedIn | [subhadip-mudi-5a53b4298](https://www.linkedin.com/in/subhadip-mudi-5a53b4298/) |
| 🧩 LeetCode | [subha__123](https://leetcode.com/u/subha__123/) |
| 📘 GeeksForGeeks | [subhadipj4l6](https://www.geeksforgeeks.org/profile/subhadipj4l6) |
| 💻 GitHub | [subhadipm08](https://github.com/subhadipm08) |

---

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=subhadipm08&label=Profile+Views&color=0e75b6&style=flat-square" />
</p>
