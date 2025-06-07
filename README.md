# AI-Powered Voice-Based Appointment Booking System

A web application that enables users to book appointments using voice commands, integrated with Google Calendar for seamless scheduling.

## Core Features
- Voice-based appointment booking
- Google Calendar integration
- Email notifications
- Real-time scheduling
- Modern UI with React & Tailwind CSS

## Basic Functionalities
- **Voice Commands**: Book, view, and manage appointments using voice
- **Appointment Management**: Create, view, modify, and cancel appointments
- **Calendar Sync**: Automatic synchronization with Google Calendar
- **Notifications**: Email alerts for confirmations and reminders
- **User Dashboard**: Quick access to appointments and calendar view

## Prerequisites
- Node.js (v16+)
- npm (v7+)
- Google Cloud Platform account
- VAPI AI API key

## Quick Setup

### Backend
```bash
cd backend
npm install
# Create .env file with required credentials
npm run dev
```

### Frontend
```bash
cd frontend
npm install
# Create .env file with API keys
npm run dev
```

## Environment Variables

### Backend (.env)
```
PORT=5000
VAPI_API_KEY=your_vapi_api_key
GOOGLE_CLIENT_ID=your_google_client_id
GOOGLE_CLIENT_SECRET=your_google_client_secret
GOOGLE_REDIRECT_URI=http://localhost:5000/auth/google/callback
EMAIL_USER=your_email@gmail.com
EMAIL_PASS=your_email_app_password
```

### Frontend (.env)
```
VITE_API_URL=http://localhost:5000
VITE_VAPI_API_KEY=your_vapi_api_key
```

## Running the App
1. Start backend: `npm run dev` (port 5000)
2. Start frontend: `npm run dev` (port 5173)
3. Open `http://localhost:5173` in browser
4. Allow microphone access
5. Start booking appointments with voice commands

## Tech Stack
- **Frontend**: React, Vite, Tailwind CSS, VAPI AI SDK
- **Backend**: Node.js, Express, Google Calendar API, Nodemailer

## License
ISC License 