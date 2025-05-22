# Gemini AI Clone

Gemini AI Clone is a React-based web application that simulates an AI-powered chatbot interface. It uses Google's Generative AI SDK to process user prompts and generate dynamic responses.

## Features

- **Chat Interface**: A user-friendly interface for interacting with the AI.
- **Dynamic Responses**: AI-generated responses are displayed with a typing animation.
- **Customizable Prompts**: Users can input their own prompts or select from predefined suggestions.
- **New Chat Functionality**: Easily reset the chat for a fresh start.
- **Recent Prompts**: View and reload previously used prompts.

## Project Structure
gemini-ai/ ├── public/ # Static assets ├── src/ │ ├── assets/ # Images and icons │ ├── component/ # React components │ │ ├── Main/ # Main chat interface │ │ ├── Sidebar/ # Sidebar component │ ├── context/ # Context API for state management │ ├── config.js/ # Configuration files │ ├── App.jsx # Main application component │ ├── main.jsx # Entry point │ ├── index.css # Global styles ├── .gitignore # Git ignore file ├── package.json # Project dependencies and scripts ├── vite.config.js # Vite configuration └── README.md # Project documentation


## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/gemini-ai.git
   cd gemini-ai

npm install

npm run dev

The project uses Google's Generative AI SDK. To configure the API key,
