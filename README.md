ZCoder

=>ZCoder is a full-stack coding assistant built to help developers enhance their problem-solving skills using AI. It integrates the GROQ API for intelligent responses and supports real-time coding data via external APIs like the Alpha LeetCode API.

Features=>AI-powered coding support using Groq API
=>Fast frontend powered by React + Vite =>Backend built with Node.js + Express 
=>Integration with external APIs like LeetCode 
=>Responsive and developer-friendly interface

TECH STACK
=>Frontend:React, Vite, Tailwind CSS 
=>Backend:Node.js, Express 
=>APIs: Groq API, Alpha LeetCode API 
=>Dev Tools:nodemon, dotenv

**Getting Started Follow these instructions to run the project locally. Clone the Repository git clone https://github.com/Rishi-rky06/Z-coder cd Z-coder Run the Backend Go to the backend folder: cd backend Install dependencies: npm install Create a .env file in the backend folder at the same level as index.js: GROQ_API_KEY=your_api_key_here

**You can generate your own API key at: https://console.groq.com/keys

=>Start the backend server using:

nodemon index.js

The backend runs at: http://localhost:3000

=>Run the Frontend

Open a new terminal and go to the frontend folder:

cd frontend

Install frontend dependencies:

npm install

=>Create a .env file inside the frontend folder:

VITE_API_URL=https://alfa-leetcode-api.onrender.com VITE_BACKEND_URL=http://localhost:3000

=>Start the frontend server:

npm run dev

The frontend runs at: http://localhost:5173

=>Environment Variables

Backend .env:

GROQ_API_KEY=your_groq_api_key

Frontend .env:

VITE_API_URL=https://alfa-leetcode-api.onrender.com VITE_BACKEND_URL=http://localhost:3000

a

