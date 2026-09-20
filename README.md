# Walbot AI

A Web3-native AI Chatbot designed to provide an intelligent, persistent conversational experience. Walbot AI is natively integrated with the Sui ecosystem and utilizes MemWal to remember user context across sessions.

## Features
- **Multi-Model Support**: Seamlessly switch between Gemini, Groq, and OpenRouter API providers directly from the chat interface.
- **Persistent Memory**: Integrates with MemWal (built on Walrus Protocol) to remember user preferences, names, and previous conversation context.
- **Web3 Native**: Automatically detects connected Sui wallet addresses to personalize the user experience without requiring traditional email logins.
- **Highly Customizable**: Clean React/Next.js architecture with Tailwind CSS, making it easy to drop into any Web3 dApp.

## Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/zazadra/Walbot-AI.git
cd Walbot-AI
```

### 2. Install dependencies
```bash
npm install
```

### 3. Configure Environment Variables
Copy `.env.local.example` (or create `.env.local`) and configure your API keys:
```env
GEMINI_API_KEY=your_gemini_api_key
MEMWAL_API_KEY=your_memwal_api_key

# Optional:
OPENROUTER_API_KEY=your_openrouter_api_key
GROQ_API_KEY=your_groq_api_key
GROQ_MODEL=llama-3.1-8b-instant
```

### 4. Run the development server
```bash
npm run dev
```
Open [http://localhost:3000](http://localhost:3000) with your browser to see the result. The Walbot AI widget will be floating in the bottom right corner of the screen.
