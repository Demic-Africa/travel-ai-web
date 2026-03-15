# 🌍 Demic Africa Travel AI

AI-powered travel intelligence platform for Africa. Personalized itineraries, real-time recommendations, and smart travel planning.

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Status](https://img.shields.io/badge/status-alpha-yellow.svg)]()
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)

## 🚀 Overview
Demic Africa combines AI agents with local African travel data to create personalized, culturally-aware travel experiences. Our platform helps travelers discover hidden gems, optimize budgets, and plan seamless itineraries across the continent.

## ✨ Features
- 🤖 AI-powered itinerary generation with local context
- 📍 Real-time travel recommendations based on conditions
- 🎯 Local experiences & hidden gems discovery
- 🔄 Multi-agent planning system (flights, hotels, activities)
- 💰 Budget optimization with currency conversion
- 🌐 Offline-first design for low-connectivity regions

## 🏗️ Architecture

┌─────────────────┐
│ Frontend │
│ (Next.js) │
└────────┬────────┘
│
┌────────▼────────┐
│ API Gateway │
│ (FastAPI) │
└────────┬────────┘
│
┌────────▼────────┐
│ AI Agents │
│ (LangGraph) │
└────────┬────────┘
│
┌────────▼────────┐
│ Travel APIs │
│ + Vector DB │
└─────────────────┘


## 🛠️ Tech Stack
| Layer | Technology |
|-------|-----------|
| **Frontend** | Next.js 14, React, Tailwind CSS, shadcn/ui |
| **Backend** | FastAPI, Python 3.11, Node.js |
| **AI/ML** | LangGraph, CrewAI, OpenAI/Claude APIs |
| **Database** | MongoDB Atlas + Vector Search, Redis |
| **Infrastructure** | Google Cloud Run, Docker, Terraform |
| **CI/CD** | GitHub Actions, Cloud Build |

## 🗺️ Roadmap
```mermaid
gantt
    title Demic Africa Development Timeline
    dateFormat  YYYY-MM
    section Core Platform
    MVP Prototype       :done,    des1, 2026-01, 2026-03
    AI Agent Integration:active,  des2, 2026-04, 2026-06
    section Expansion
    Multi-city Launch   :         des3, 2026-07, 2026-09
    Predictive Analytics:         des4, 2026-10, 2026-12

    🤝 Contributing
We welcome contributions! See our Contributing Guide to get started.
Quick Start for Developers

# Clone and install
git clone https://github.com/demicafrica/travel-ai-web.git
cd travel-ai-web
npm install

# Set up environment
cp .env.example .env.local
# Add your API keys

# Run development server
npm run dev

📫 Contact
🌐 Website: www.demicafrica.com
📧 Email: info@demicafrica.com
🔐 Security: security@demicafrica.com
💬 Discussions: GitHub Discussions

📄 License
MIT License - see LICENSE for details.

Built with ❤️ for African travel innovation
