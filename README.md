# Walbot AI

A Web3-native AI Chatbot template that remembers users via Walrus/MemWal.

## Features
- **Multi-Model Support**: Gemini, Groq, OpenRouter.
- **Persistent Memory**: Uses MemWal to remember user context across sessions.
- **Web3 Native**: Detects Sui wallet addresses automatically.

## Getting Started
1. Clone the repo
2. Run `npm install`
3. Fill in `.env.local` with your API keys:
   - `GEMINI_API_KEY`
   - `MEMWAL_API_KEY`
   - `OPENROUTER_API_KEY` (optional)
   - `GROQ_API_KEY` (optional)
   - `GROQ_MODEL` (optional)
4. Run `npm run dev`
