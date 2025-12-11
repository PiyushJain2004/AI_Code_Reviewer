# 🚀 AI Code Reviewer

An **AI-powered web application** that reviews and optimizes source code using **Google's Gemini API**.  
Built with a **MERN-based architecture**, this project provides real-time feedback and syntax-highlighted insights to help developers improve code quality instantly.

---

## 🧩 Features

- 🤖 **AI Integration:** Uses Google Gemini API to analyze and optimize code intelligently.  
- ⚙️ **Full-Stack MERN Architecture:** Node.js, Express.js, React.js, and MongoDB-ready setup.  
- 🧠 **Secure API Design:** POST-based backend routes with CORS and `.env` configuration.  
- 💡 **Real-Time Feedback:** Code syntax highlighting with **PrismJS** for enhanced readability.  
- 🌐 **Modern UI:** Built with **React + Vite + Tailwind CSS** for fast and responsive experience.

---

## 🧠 Tech Stack

| Category | Tools / Libraries |
|-----------|------------------|
| **Frontend** | React, Vite, Tailwind CSS, PrismJS |
| **Backend** | Node.js, Express.js |
| **AI Integration** | Google Gemini API |
| **Tools & Platforms** | Git, GitHub, Postman, Render |
| **Languages** | JavaScript (ES6+) |

---

## ⚙️ Getting Started

### 1️⃣ Clone the Repository
```
git clone https://github.com/PiyushJain2004/AI_Code_Reviewer.git
cd AI_Code_Reviewer



2️⃣ Install Dependencies
Backend
cd BackEnd
npm install
Frontend

cd ../Frontend
npm install

3️⃣ Configure Environment Variables
Create a .env file inside the BackEnd directory and add:

GEMINI_API_KEY=your_google_gemini_api_key_here
PORT=8000
⚠️ Important: Never commit your real API keys. .gitignore is already configured to prevent this.

4️⃣ Run the Application
Start Backend Server:

bash
cd BackEnd
npm start
Start Frontend Server:

bash
cd ../Frontend
npm run dev
Open your browser and navigate to http://localhost:5173 to experience the app.



### 📁 Project Structure
```
AI_Code_Reviewer/
│
├── BackEnd/
│   ├── package.json
│   ├── .env.example
│   ├── server.js
│   └── src/
│       ├── app.js
│       ├── controllers/
│       │   └── ai.controller.js
│       ├── routes/
│       │   └── ai.routes.js
│       └── services/
│           └── ai.service.js
│
├── Frontend/
│   ├── package.json
│   ├── vite.config.js
│   ├── index.html
│   └── src/
│       ├── main.jsx
│       ├── App.jsx
│       ├── App.css
│       └── assets/
│
├── .gitignore
├── README.md
├── LICENSE
└── .github/
    └── workflows/
        └── ci.yml
        ```



💡 Enhancement Suggestions
Add authentication to restrict API usage or save personalized feedback.

Integrate persistent storage to save user code snippets and review history.

Extend AI capabilities for multi-language support beyond JavaScript.

Implement a collaborative code review feature with real-time comments.

Add detailed analytics on common code issues to guide education or training.
