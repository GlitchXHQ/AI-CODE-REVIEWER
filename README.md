🤖 AI Code Reviewerz
AI Code Reviewerz is an AI-powered code review assistant built with the MERN stack and Gemini Pro.
It helps developers by analyzing source code, detecting bugs, improving readability, and suggesting optimizations in real time.

📂 Project Structure
/ai-code-reviewerz/
│
├── frontend/              # React.js (UI for code input & results)
│   ├── src/
│   └── package.json
│
├── backend/               # Node.js + Express API
│   ├── routes/
│   ├── controllers/
│   ├── server.js
│   └── package.json
│
├── ai-engine/             # Gemini Pro integration
│   ├── geminiClient.js
│   ├── reviewService.js
│   └── README.md
│
├── database/              # MongoDB schema/models
│   └── codeReviews.js
│
├── docs/                  # Screenshots, diagrams, demo assets
│
└── README.md

🚀 Tech Stack

Frontend → React.js + TailwindCSS

Backend → Node.js + Express.js

Database → MongoDB

AI Engine → Gemini Pro API

Auth & Security → JWT / OAuth2

Deployment → Vercel (frontend), Render/Heroku (backend), MongoDB Atlas

⚡ How to Run Locally
1️⃣ Clone the repository
git clone https://github.com/your-username/ai-code-reviewer.git
cd ai-code-reviewer

2️⃣ Setup Backend
cd backend
npm install
npm run dev

3️⃣ Setup Frontend
cd frontend
npm install
npm run dev

4️⃣ Configure Gemini Pro API

Create a .env file in backend/ with:

GEMINI_API_KEY=your_api_key_here
MONGO_URI=your_mongodb_connection

5️⃣ Start Application

Backend → http://localhost:5000

Frontend → http://localhost:5173

✨ Features

✅ AI-Powered Code Review → Detects bugs, inefficiencies, and missing best practices.
✅ Multi-Language Support → Works with Python, JavaScript, C++, Java (and expanding).
✅ Gemini Pro Integration → Uses cutting-edge AI to provide accurate suggestions.
✅ History Tracking → Stores past code reviews in MongoDB.
✅ Collaborative UI → Simple, clean React-based dashboard.
✅ Real-Time Suggestions → Instant AI feedback on pasted/uploaded code.

🎮 Usage

Open the web app in your browser.

Paste or upload your code.

Click Review Code → AI analyzes your submission.

Get structured feedback:

✅ Errors & warnings

✅ Optimization hints

✅ Readability improvements

✅ Security checks

🌍 Demo Preview
<img width="1001" height="873" alt="image" src="https://github.com/user-attachments/assets/8604891a-423c-4938-a5c5-e5af01c11fc0" />
<img width="924" height="689" alt="image" src="https://github.com/user-attachments/assets/dc8f6b29-850a-4021-ab38-ec6bc21a4357" />


Example:

📌 Roadmap

🚀 Add GitHub PR integration (auto-review pull requests).

🚀 Provide inline code annotations.

🚀 Expand support for Go, Rust, PHP.

🚀 Add team collaboration features (comments, assignments).

🚀 Build a VS Code Extension.

🤝 Contributing

We welcome contributions from the community 💡

Fork the repo

Create your branch (git checkout -b feature/AmazingFeature)

Commit changes (git commit -m 'Added new feature')

Push to branch (git push origin feature/AmazingFeature)

Open a Pull Request

🙌 Credits

Gemini Pro API → AI-powered code analysis.

MERN Stack → Full-stack web app development.

Community Contributors ❤️
