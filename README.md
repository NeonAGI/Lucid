# Lucid - AI-Powered Personal Journal and Chat Application

Lucid is an intelligent journaling application that combines conversational AI with personal memory and journaling capabilities. It provides a seamless experience for users to chat with an AI that remembers past conversations and automatically saves reflective content to a personal journal.

## Core Features

- **AI Chat Interface**: Talk with an AI assistant that remembers your conversations and learns about you over time
- **Automated Journaling**: The app automatically detects personal, reflective content in your conversations and saves it to your journal
- **Web Search Integration**: When you ask factual questions, the AI can search the web for up-to-date information
- **Memory System**: The app maintains a vector database of your conversations to provide more personalized responses
- **Chat History Import**: You can import conversation history from other platforms (like ChatGPT exports)

## Tech Stack

- **Frontend**: React with TypeScript, Tailwind CSS, and Shadcn UI components
- **Backend**: Node.js with Express
- **Database**: PostgreSQL for storing user data, messages, and journal entries
- **AI Integration**: OpenAI API for generating responses and embeddings
- **Vector Search**: For memory retrieval based on semantic similarity

## Getting Started

### Prerequisites

- Node.js (v18.x or later)
- PostgreSQL database
- OpenAI API key

### Installation

1. Clone the repository
   ```
   git clone https://github.com/yourusername/lucid.git
   cd lucid
   ```

2. Install dependencies for both frontend and backend
   ```
   # Install frontend dependencies
   cd client
   npm install

   # Install backend dependencies
   cd ../server
   npm install
   ```

3. Set up environment variables
   - Create a `.env` file in the server directory based on `.env.example`
   - Add your OpenAI API key and database connection details

4. Initialize the database
   ```
   cd server
   npm run db:migrate
   ```

5. Start the development servers
   ```
   # Start backend server
   cd server
   npm run dev

   # In a new terminal, start frontend
   cd client
   npm run dev
   ```

## Project Structure

- `/client` - React frontend application
- `/server` - Node.js Express backend API
- `/docs` - Documentation and design assets

## License

[Include your license information here]