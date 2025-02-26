# ResuMate - AI Resume Builder

## Overview
ResuMate is an AI-powered resume-building platform designed to help users create professional, high-quality resumes with ease. Leveraging artificial intelligence, ResuMate generates tailored resumes based on user input, optimizing content for different industries and job roles.

## Features
- **AI-Powered Resume Generation**: Automatically generates resumes based on user-provided details.
- **Customizable Templates**: Choose from a variety of professionally designed templates.
- **Keyword Optimization**: Ensures resumes are ATS (Applicant Tracking System) friendly.
- **Real-Time Editing**: Edit and format your resume seamlessly within the platform.
- **PDF Export & Sharing**: Download and share your resume in multiple formats.
- **Smart Suggestions**: AI-driven recommendations for enhancing resume content.
- **Secure & Private**: User data is securely stored and protected.

## Tech Stack
- **Frontend**: React/React Native
- **Backend**: FastAPI/Node.js (Express.js)
- **Database**: MongoDB/PostgreSQL
- **AI/ML**: Gemini API/NLP techniques for resume content generation
- **Deployment**: Vercel (Frontend), Render/Heroku (Backend)

## How to Run Locally
### Prerequisites
- Node.js & npm/yarn installed

### Steps
1. Clone the repository:
   ```sh
   git clone https://github.com/jeetukgpian/resumate.git
   cd resumate
   ```

2. Install frontend dependencies:
   ```sh
   cd frontend
   npm install  # or yarn install
   ```

3. Install backend dependencies:
   ```sh
   cd backend
   pip install -r requirements.txt
   ```

4. Run the frontend:
   ```sh
   npm start  # or yarn start
   ```

5. Run the backend:
   ```sh
   uvicorn main:app --reload
   ```

## Deployment
- **Frontend**: Hosted on Vercel
- **Backend**: Hosted on Strapi
- **Database**: Cloud-based MongoDB/PostgreSQL
-**Authentication**: Clerk Management System

## Contribution Guidelines
1. Fork the repository
2. Create a new branch: `git checkout -b feature-name`
3. Commit your changes: `git commit -m "Added new feature"`
4. Push the branch: `git push origin feature-name`
5. Open a pull request


