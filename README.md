
# Gemini Clone Project

A React.js-based frontend that mimics the functionality of Gemini, integrated with an AI chatbot backend powered by an API key from Google AI Studio.


## Project Overview

This project is a Gemini clone built using React.js for the frontend and an AI-powered backend that interacts with the Gemini API. The project replicates the core features of Gemini, offering a chat-based interface that allows users to interact with an AI chatbot. The backend is connected via an API key generated from Google AI Studio, enabling the chatbot-like functionality.


## Technologies Used

 - Frontend: React.js
 - Backend: Node.js (with Google AI Studio API integration)
 - AI Model: Google AI Studio API
 - API: Gemini API (for backend communication)
 - Others: Axios (for API requests), CSS/SCSS for styling


## Installation

To get started with the project locally, follow these steps in your integrated terminal:

### 1. Clone the repository:
```bash
git clone https://github.com/adityasahu1109/gemini-clone.git
cd gemini-clone
```
### 2. Install dependencies:
```bash
npm install
```

### 3. Set up backend:

- Obtain an API key from Google AI Studio.
- Create a `.env` file in the `backend` directory and add your API key:
```bash
VITE_API_KEY=your-api-key-here
```

### 4. Start the website:
```bash
npm run dev
```
Now, your application should be running at http://localhost:3000
or any other place depending on your system.## Usage

 - Open the app in your browser.
 - You will be presented with a chatbot interface.
 - Type your queries, and the AI chatbot will respond, simulating the Gemini chatbot-like functionality.

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please follow these steps:

 - Fork the repository.
 - Create a new branch (git checkout -b feature/your-feature).
 - Commit your changes (git commit -am 'Add new feature').
 - Push to the branch (git push origin feature/your-feature).
 - Create a new Pull Request.
## License

This project is licensed under the MIT License - see the [LICENSE](https://choosealicense.com/licenses/mit/)

## Acknowledgements

 - Gemini API for powering the chatbot.
 - Google AI Studio for the backend integration.
 - React.js for building the frontend interface.
