a# 🎓 Student Performance Prediction – End-to-End ML Deployment

## 📌 Overview

This project is an **end-to-end Machine Learning application** that predicts student academic performance based on multiple input features. The trained ML model is served through a **Flask-based web application** and deployed on **AWS Elastic Beanstalk** with a fully automated **CI/CD pipeline** using **GitHub and AWS CodePipeline**.

The goal of this project is not only model accuracy, but also demonstrating **production-ready ML deployment**, cloud configuration, and continuous delivery.

---

## 🚀 Live Demo

🔗 **Application URL:** [https://studentperformance-env.eba-ppu8z7tv.eu-north-1.elasticbeanstalk.com](https://studentperformance-env.eba-ppu8z7tv.eu-north-1.elasticbeanstalk.com)

---

## 🧠 Problem Statement

Predict student performance using academic and demographic factors to help analyze educational outcomes and trends.

---

## 🏗️ System Architecture

```
User
  │
  ▼
Web Interface (HTML / CSS)
  │
  ▼
Flask REST API
  │
  ▼
Trained ML Model (Scikit-learn)
  │
  ▼
Prediction Output

Deployment:
GitHub → AWS CodePipeline → AWS Elastic Beanstalk → EC2
```

---

## 🛠️ Tech Stack

### Programming & ML

* Python 3.11
* NumPy
* Pandas
* Scikit-learn

### Backend & Web

* Flask
* Gunicorn
* HTML / CSS

### Cloud & DevOps

* AWS Elastic Beanstalk
* AWS EC2
* AWS CodePipeline
* GitHub (Source Control)

---

## ✨ Features

* Trained machine learning model for student performance prediction
* Flask-based backend API
* Simple web interface for user input
* Automated CI/CD pipeline (GitHub → AWS)
* Cloud deployment with Elastic Beanstalk
* Production-ready configuration

---

## ⚙️ CI/CD Workflow

1. Code pushed to GitHub repository
2. GitHub triggers AWS CodePipeline automatically
3. CodePipeline deploys the application to Elastic Beanstalk
4. Elastic Beanstalk updates the running EC2 instance

✔ No manual deployment required

---

## 📂 Project Structure

```
├── app.py / main.py        # Flask application entry point
├── model/                 # Trained ML model files
├── templates/             # HTML templates
├── static/                # CSS files
├── requirements.txt       # Project dependencies
├── Procfile               # Gunicorn startup command
├── README.md              # Project documentation
```

---

## ▶️ Running Locally

1. Clone the repository

```bash
git clone https://github.com/saksham-s18/ml-model-deployment-pipeline.git
cd ml-model-deployment-pipeline
```

2. Create and activate virtual environment

```bash
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
```

3. Install dependencies

```bash
pip install -r requirements.txt
```

4. Run the application

```bash
python app.py
```

5. Open in browser

```
http://127.0.0.1:5000
```

---

## 📈 What This Project Demonstrates

* End-to-end ML workflow (training → deployment)
* Backend development using Flask
* Cloud deployment on AWS
* CI/CD automation
* Debugging real-world deployment issues

---

## 🔮 Future Improvements

* Add `/health` endpoint for monitoring
* Add API documentation
* Improve UI/UX
* Store predictions in a database
* Add monitoring and logging

---

## 👨‍💻 Author

**Saksham Singh**
B.Tech CSE Student | Aspiring ML & Backend Engineer

---

## ⭐ Acknowledgements

* AWS Documentation
* Scikit-learn
* Flask Framework

---

If you find this project helpful, consider giving it a ⭐ on GitHub!
