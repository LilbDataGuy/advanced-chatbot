# Advanced Chatbot with GPT & Intent Recognition

This is a full-stack chatbot application built with **Node.js**, **Express**, **MongoDB**, and **OpenAI's GPT API**. It features both rule-based intent recognition and intelligent GPT-powered replies.

## 🔧 Features

- Rule-based intent detection (greetings, help, farewells)
- Fallback to GPT-3.5-Turbo for more intelligent responses
- Stores chat history in MongoDB
- Simple frontend chat interface
- GitHub Codespaces compatible

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/your-repo-name.git
cd your-repo-name/server
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Set Up Environment Variables

Create a `.env` file in the `server` directory with the following:

```bash
OPENAI_API_KEY=your_openai_api_key_here
```

### 4. Start MongoDB

Ensure MongoDB is running locally, or update the connection string in `server.js` to match your remote database.

### 5. Start the Server

```bash
node server.js
```

### 6. View in Browser

Go to [http://localhost:3000](http://localhost:3000)

## 💻 Using GitHub Codespaces

This project includes a `.devcontainer` configuration. Open it in Codespaces and it will automatically:

- Install dependencies
- Set up Node.js
- Install MongoDB locally
- Forward port 3000

## 📁 Project Structure

```
chatbot_project/
├── public/
│   └── index.html        # Frontend UI
├── server/
│   ├── server.js         # Express server with chatbot logic
│   └── .env              # OpenAI API key
└── .devcontainer/
    └── devcontainer.json # Codespaces config
```

## 📦 Dependencies

- express
- mongoose
- body-parser
- cors
- openai
- dotenv

## 🧠 AI Model

This project uses [OpenAI's GPT-3.5 Turbo](https://platform.openai.com/docs/models/gpt-3-5) via API.

## 📜 License

MIT

---

Built with ❤️ by ChatGPT
