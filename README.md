# cloud-learning-journey
 From fundamentals to deployment.

This repository documents my projects and progress as I follow a strategic roadmap to land a top-tier tech role.


Completed the Introduction to IAM lab.
 Learned about IAM roles, policies, and service accounts.
 
 First Production Deployment on Cloud Run

## 🎉 MAJOR MILESTONE ACHIEVED

**Live Application URL:** https://my-first-cloud-app-640781293504.us-central1.run.app

## What I Accomplished

1.  **Set up secure GCP environment** with budget controls
2.  **Created Docker container** from scratch
3.  **Debugged real deployment issue** (port configuration)
4.  **Successfully deployed to Google Cloud Run**
5.  **Application is now live and publicly accessible**

## 🛠 Technical Stack Used

- HTML/CSS/JavaScript
- Docker Containerization
- Google Cloud Run
- Google Cloud Build
- Nginx Web Server

## Problem Solved

**Initial Deployment Failed:** Container port misconfiguration
**Root Cause:** Nginx listening on port 80, Cloud Run requires port 8080
**Solution:** Modified nginx configuration to listen on port 8080

## 📚 Key Learnings

- Cloud Run requires containers to listen on port 8080
- Dockerfile configuration is critical for deployment success
- Debugging deployment issues is a valuable skill
- Professional deployment workflow: local → container → cloud


## 🎯 Mission Accomplished
**Live AI Sentiment Analyzer with Database Integration**

**URL:** https://ai-sentiment-analyzer-640781293504.us-central1.run.app

## ✅ What Works
1. **Gemini AI Integration** - Real sentiment analysis via `models/gemini-2.0-flash`
2. **Database Persistence** - SQLite with automatic saving to `/tmp`
3. **Full REST API** - 4 endpoints with proper JSON responses
4. **Production Deployment** - Google Cloud Run with auto-scaling
5. **Frontend Interface** - Browser-accessible UI

## 🔧 Technical Stack
- **Backend:** FastAPI 0.104.1
- **AI Model:** Gemini 2.0 Flash
- **Database:** SQLite (persistent in Cloud Run `/tmp`)
- **Deployment:** Google Cloud Run (serverless)
- **Memory:** 512Mi
- **Region:** us-central1

## 🧪 Test Results
**Input:** "Gemini model fixed! Database integration complete!"
**Output:**
- Sentiment: **positive** (95% confidence)
- Key Phrases: ["Gemini model fixed", "Database integration complete"]
- Database Save: ✅ Successful
- Response Time: < 3 seconds

## 🚀 Features Live
- `POST /analyze` - AI sentiment analysis + database save
- `GET /history` - Retrieve chronological analysis history
- `GET /stats` - Analytics (sentiment distribution, averages)
- `GET /health` - Service health + database connection check
- `GET /` - Frontend interface with sentiment input


This project demonstrates:
- **Full-stack development** from idea to production
- **Cloud deployment expertise** (Google Cloud Run)
- **AI integration skills** (Gemini API with proper model handling)
- **Database design** (SQLite with schema and queries)
- **Production debugging** (solving real deployment issues)
- **API design** (RESTful endpoints with proper responses)



