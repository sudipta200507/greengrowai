# GreenGrow — AI-Powered Farming Assistant

An AI-enabled agricultural platform combining conversational assistance, crop-disease analysis, weather intelligence, market information, and farm-management workflows.

## Overview

GreenGrow explores how AI can be combined with multiple data sources and application services to build a practical digital farming assistant.

## Core Capabilities

- AI-powered farming assistant
- Image-based crop disease analysis
- Voice interaction
- Weather information
- Agricultural market-price information
- Crop-management guidance
- Government-scheme information
- Farm profiles and personalization
- Community/support workflows
- Authentication and protected APIs

## Architecture

```text
React Client
     ↓
Node.js / Express API
     ↓
MongoDB
     │
     ├── AI / Gemini services
     ├── Python disease-detection service
     ├── Weather APIs
     └── Agricultural data services
```

## Technology

| Layer | Technology |
|---|---|
| Frontend | React, TypeScript, Vite, Tailwind CSS |
| Backend | Node.js, Express |
| Database | MongoDB / Mongoose |
| Authentication | JWT |
| ML | TensorFlow / Keras |
| AI | Gemini |
| Python Service | Flask |
| HTTP | Axios |
| Deployment | Service-dependent |

## Repository Structure

```text
GreenGrow/
├── Client/       # React application
├── server/       # Node.js / Express API
├── backend/      # Python ML service
├── model/        # ML model assets
└── Readme.md
```

## Local Development

### Node.js API

```bash
cd server
npm install
npm run dev
```

### Python ML service

```bash
cd backend
python -m venv venv
# Windows
venv\Scripts\activate
pip install -r requirements.txt
python app.py
```

### Frontend

```bash
cd Client
npm install
npm run dev
```

Configure required environment variables locally. **Never commit API keys, database credentials, JWT secrets, or other secrets.**

## Engineering Focus

- Full-stack application architecture
- AI API integration
- Computer-vision model integration
- REST API development
- Authentication
- Database-backed applications
- Multi-service development
- AI-assisted product design

## Project Status

**Hackathon / product-development project.**

The repository contains the implementation of the GreenGrow concept and can be evolved toward stronger model evaluation, service isolation, observability, and production deployment.

## Portfolio Note

This project has an older duplicate repository in the same GitHub account. The implementation should be treated as **one project**, not two separate portfolio projects.

## Author

**Sudipta Roy**  
B.Tech CSE (AI & ML)

Focus: **AI/ML • Full-Stack AI • Computer Vision • Applied AI**
