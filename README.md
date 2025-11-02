# cloud-learning-journey
 From fundamentals to deployment.

This repository documents my projects and progress as I follow a strategic roadmap to land a top-tier tech role.

## Phase 1: Skill Foundation

### Week 1-2: Cloud Fundamentals

**Day 1: 01-11-2025** 
Completed the Introduction to IAM lab.
 Learned about IAM roles, policies, and service accounts.
# Day 2: First Production Deployment on Cloud Run

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

