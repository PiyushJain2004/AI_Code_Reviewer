🚀 AI Code Reviewer
An AI-powered web application that automatically reviews, analyzes, and optimizes source code using Google's Gemini API. This tool provides developers with instant, real-time feedback to improve code quality, maintainability, and performance through an intuitive, syntax-highlighted interface.

🧩 Key Features
🤖 Advanced AI Code Analysis
Leverages the power of Google Gemini API to intelligently analyze code, detect potential issues, and suggest optimizations.

⚙️ Robust Full-Stack MERN Architecture
Built with Node.js, Express.js, React.js, and MongoDB, ensuring scalability and maintainability.

🧠 Secure API Design
Implements secure POST routes with CORS handling and environment variables for safe API key management.

💡 Instant Real-Time Feedback
Uses PrismJS for elegant, live syntax highlighting and detailed code review insights.

🌐 Responsive Modern UI
Designed with React + Vite + Tailwind CSS to deliver a fast, lightweight, and visually appealing user experience.

🔄 Continuous Integration
Automated workflows using GitHub Actions streamline testing and deployment processes.

🧰 Tech Stack
Layer	Technologies & Tools
Frontend	React, Vite, Tailwind CSS, PrismJS
Backend	Node.js, Express.js
AI Integration	Google Gemini API
Database	MongoDB (ready for future enhancements)
DevOps	Git, GitHub, GitHub Actions, Render
Languages	JavaScript (ES6+)
⚙️ Getting Started
Follow these steps to set up and run the AI Code Reviewer locally:

1️⃣ Clone the Repo
bash
git clone https://github.com/PiyushJain2004/AI_Code_Reviewer.git
cd AI_Code_Reviewer
2️⃣ Install Dependencies
Backend

bash
cd BackEnd
npm install
Frontend

bash
cd ../Frontend
npm install
3️⃣ Configure Environment Variables
Create a .env file inside the BackEnd directory and add:

text
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
```

💡 Enhancement Suggestions
Add authentication to restrict API usage or save personalized feedback.

Integrate persistent storage to save user code snippets and review history.

Extend AI capabilities for multi-language support beyond JavaScript.

Implement a collaborative code review feature with real-time comments.

Add detailed analytics on common code issues to guide education or training.
