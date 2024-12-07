# Personality Analysis Web App | من أنا

A bilingual (Arabic/English) personality analysis web application with Google Pay integration and Firebase backend.

## Features

- 🤖 Dynamic personality analysis chatbot
- 💳 Google Pay integration for premium reports
- 🌐 Bilingual support (Arabic/English)
- 🔥 Firebase backend for data storage
- 📱 Responsive design for all devices

## Project Structure

```
├── frontend/
│   ├── public/
│   │   ├── index.html
│   │   ├── styles/
│   │   └── assets/
│   └── src/
│       ├── components/
│       ├── services/
│       └── utils/
├── backend/
│   ├── config/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   └── services/
└── firebase/
    └── config/
```

## Prerequisites

- Node.js (v14 or higher)
- Firebase account
- Google Pay merchant account
- ChatGPT/Grok API access

## Installation

1. Clone the repository:
```bash
git clone https://github.com/alshfa0e/personality-analysis-app.git
cd personality-analysis-app
```

2. Install dependencies:
```bash
# Frontend
cd frontend
npm install

# Backend
cd ../backend
npm install
```

3. Configure environment variables:
```bash
# Create .env files in both frontend and backend directories
cp .env.example .env
```

4. Set up Firebase:
- Create a new Firebase project
- Add your Firebase configuration to `firebase/config/firebase.config.js`

5. Configure Google Pay:
- Set up your Google Pay merchant account
- Add your merchant ID to the configuration

## Running the Application

### Development

```bash
# Frontend (from frontend directory)
npm run dev

# Backend (from backend directory)
npm run dev
```

More instructions will be added as development progresses.