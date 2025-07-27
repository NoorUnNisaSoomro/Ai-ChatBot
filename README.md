# 🧠 Noor AI ChatBot – React + Gemini 2.0
A sleek, responsive AI chatbot built in ReactJS, powered by Gemini 2.0 Flash API, and designed with a user-friendly UI/UX. This assistant remembers conversations, supports dark/light mode, allows chat export, and simulates real-time AI typing effects. Meet Anna, your personalized AI assistant!

# 🚀 Features
✅ Real-Time Chat with Gemini 2.0 Flash model

🌓 Dark / Light Mode toggle with system preference detection

💾 Persistent Conversations using localStorage

💬 Multiple Chat Sessions (create, delete, rename)

📄 Export Chat as .txt

🧹 Clear Chat History with confirmation

🎯 Typing Indicator & Smooth Auto-Scroll

📱 Fully Responsive UI for mobile, tablet, and desktop

🔐 API Key Securely Managed (in dev only)

🖼️ Preview

# 🧰 Tech Stack
Frontend: ReactJS (Hooks, JSX, CSS)
API: Google Gemini 2.0 Flash Model
Styling: Custom CSS with CSS Variables
Storage: Browser LocalStorage

# 📦 Setup Instructions
1. Clone the repository
git clone https://github.com/yourusername/noor-ai-chatbot.git
cd noor-ai-chatbot

3. Install dependencies
npm install

4. Add your Gemini API key
Create a .env file in the root directory:
REACT_APP_GEMINI_API_KEY=your_api_key_here
🔐 Never commit your API key to version control.

5. Start the app
npm start

# 🔑 API Reference
This app uses Google's Gemini API with the following endpoint:
https://generativelanguage.googleapis.com/v1beta/models/gemini-2.0-flash:generateContent
 
Make sure to:
Enable the Generative Language API in your Google Cloud Console.
Generate and use a valid API Key.

# 📁 Project Structure
📦 root
├── public/
│   └── index.html
├── src/
│   ├── App.js       # Main chatbot logic and UI
│   ├── App.css      # Full CSS styling (light/dark support)
│   └── index.js     # React DOM entry
├── .env             # API key config (not committed)
├── package.json
└── README.md


# 👩‍💻 Author
Made with ❤️ by Noor un Nisa
📬 LinkedIn
🧠 Powered by: Gemini 2.0 + React
