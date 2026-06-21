# ScriptGenie AI

ScriptGenie AI is a full-stack AI-powered platform that helps creators generate professional YouTube scripts and AI-generated thumbnails in seconds.

The application combines OpenRouter LLMs, Hugging Face image generation models, MongoDB Atlas, and Vercel deployment to provide a complete content creation workflow.

## Live Demo

🌐 https://scriptgenie-ai-eight.vercel.app/

## Features

* AI-powered YouTube script generation
* Multiple writing tones and styles
* AI thumbnail generation
* Secure user authentication
* Cloud-synced script history
* Persistent user sessions
* MongoDB Atlas integration
* Responsive modern dashboard
* Script management and deletion

## Tech Stack

### Frontend

* HTML5
* CSS3
* JavaScript

### Backend

* Node.js
* OpenRouter API
* Hugging Face Inference API

### Database

* MongoDB Atlas

### Deployment

* Vercel

## Project Workflow

1. User signs up or logs in.
2. User enters topic, audience, tone, duration, and key points.
3. OpenRouter generates a structured YouTube script.
4. Generated scripts are stored in MongoDB Atlas.
5. Users can revisit previously generated scripts through history.
6. Hugging Face generates AI thumbnails for selected scripts.
7. All content remains accessible through the cloud-synced dashboard.

## Installation

Clone the repository:

```bash
git clone https://github.com/AnunayKumar07/ScriptGenie-AI.git
```

Install dependencies:

```bash
npm install
```

Create a `.env` file:

```env
OPENROUTER_API_KEY=your_key
HF_TOKEN=your_token
```

Run the project:

```bash
node server.js
```

Open:

```text
http://localhost:3000
```

## Screenshots

* Login Page
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/06eb2745-c8d3-49bf-a3d9-5087d88d550e" />

* Dashboard
  <img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/8f3a941f-96df-4f4a-9762-bed311f339b4" />


* Script Generation & Thumbnail Generation
  <img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/2a370013-5e0a-41f4-ad01-57fc93192ad3" />


## Author

**Anunay Kumar**

Built as a full-stack AI project showcasing authentication, API integration, database management, deployment, and AI-powered content generation.
