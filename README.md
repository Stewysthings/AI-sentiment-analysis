

# 🔍 AI Sentiment Analysis API
![Python](https://img.shields.io/badge/Python-3.9+-blue?logo=python)
![Flask](https://img.shields.io/badge/Flask-2.0-green?logo=flask)
![Docker](https://img.shields.io/badge/Docker-✓-lightgrey?logo=docker)
[![CI/CD](https://github.com/Stewysthings/AI-sentiment-analysis/actions/workflows/main.yml/badge.svg)](https://github.com/Stewysthings/AI-sentiment-analysis/actions)

**Real-time sentiment prediction (89% accuracy)**  
Production-ready API with Swagger documentation and containerized deployment.

## 🚀 Features
- ✔ **High Accuracy**: 89% F1-score on Twitter Sentiment140
- ✔ **Self-Documenting**: Interactive Swagger UI at `/docs`
- ✔ **One-Command Deploy**: Fully containerized with Docker
- ✔ **Automated Pipelines**: CI/CD via GitHub Actions

## 🛠️ Quick Start
```bash
# Build and run with Docker
docker build -t sentiment-api . && docker run -p 5000:5000 sentiment-api

# Or run locally
python -m venv .venv
source .venv/bin/activate  # Linux/Mac
.\.venv\Scripts\activate   # Windows
pip install -r requirements.txt
python app.py
.
📂 Project Structure
├── app.py          # Flask API endpoints
├── train.py       # LinearSVC model training
├── Dockerfile     # Production container setup
├── requirements.txt

📊 API Documentation
Access interactive docs after running:
http://localhost:5000/docs
Swagger UI Preview





└── error_logs/    # Automated error tracking

