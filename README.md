# AI-Powered Travel Guide 🌍

An AI-powered travel guide that helps users explore popular tourist destinations and generate audio guides using **Google Gemini AI** and **Murf AI**.

The project combines a web interface with a Python Flask backend to provide destination information and AI-generated audio experiences.

## ✨ Features

- **Destination Search:** Search for available tourist destinations.
- **Destination Cards:** Browse destinations and select a place to explore.
- **AI-Powered Information:** Generate destination descriptions using Google Gemini AI.
- **Audio Guide Generation:** Generate audio guides using Murf AI.
- **Multiple Languages:** Choose from English, Hindi, Tamil, and Telugu.
- **Voice Selection:** Choose a male or female voice.
- **Guide Length:** Select a summary or a longer guide, depending on the available options.
- **Transcript:** Read the generated destination information alongside the audio guide.

## 🛠️ Technologies Used

- HTML
- JavaScript
- Python
- Flask
- Flask-CORS
- Python Dotenv
- Google Gemini AI
- Murf AI
- Visual Studio Code

## 📁 Project Structure

```text
AI-Powered-Travel-Guide/
│
├── .vscode/
│   └── settings.json
│
├── Backend/
│   ├── app.py
│   └── .env                 # Local environment variables
│
├── Frontend/
│   ├── index.html
│   └── index.js
│
├── .gitignore
└── README.md
```

## ⚙️ Setup and Installation

### 1. Clone the repository

Replace `YOUR-USERNAME` with your GitHub username.

```bash
git clone https://github.com/YOUR-USERNAME/AI-Powered-Travel-Guide.git
cd AI-Powered-Travel-Guide
```

### 2. Install Python dependencies

Open a terminal in VS Code and install the required packages:

```bash
pip install flask flask-cors python-dotenv
```

Install any additional packages imported by `Backend/app.py` if they are not already installed.

### 3. Configure environment variables

Create a `.env` file inside the `Backend` folder.

Add your Gemini AI and Murf AI API keys using the exact environment variable names expected by `app.py`.

Keep your API keys private. Do not publish them in source code, screenshots, or GitHub commits.

### 4. Start the backend

Open the VS Code terminal and run:

```bash
cd Backend
python app.py
```

The Flask backend should start on the local address configured in `app.py`.

### 5. Run the frontend

Open `Frontend/index.html` using the **Live Server** extension in Visual Studio Code.

Ensure the backend is running when you use the audio guide feature.

## 🔐 Security

- Store API keys in environment variables.
- Exclude `.env` files from Git using `.gitignore`.
- Never expose private API keys in a public repository.
- Configure environment variables securely when deploying the application.

## 🚀 Deployment

The frontend and backend need to be deployed so the application can be accessed online.

The frontend must use the deployed backend URL instead of a local address such as `127.0.0.1`.

The backend's API keys must be configured securely through the hosting provider's environment settings.

## 👩‍💻 Project Purpose

This project explores how generative AI and text-to-speech technology can be combined to create an interactive travel experience. It aims to make destination information more accessible through text and audio.

---

**AI-Powered Travel Guide** — Explore destinations with AI.
