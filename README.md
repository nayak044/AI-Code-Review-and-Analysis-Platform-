# AI Code Review and Analysis Platform

A scalable, full-stack MERN platform that leverages AI (LLMs) to automate code reviews, detect bugs, security vulnerabilities, and code smells. The platform streamlines the review process, boosts code quality, and saves developer time by providing actionable feedback on code submissions.

## Features

- 🔍 **Automated Code Review:** Analyzes code and provides AI-generated feedback.
- 🛡️ **Bug & Security Detection:** Flags potential bugs, vulnerabilities, and code smells.
- 💬 **Contextual Suggestions:** Offers explanations and improvement suggestions.
- 🏗️ **Microservices Architecture:** Modular backend using Node.js, Express, MongoDB.
- 📊 **Historical Analytics:** Tracks review history and code quality trends.
- 👥 **Role-Based Access:** Admin and developer roles.
- ⚡ **Real-Time Updates:** Live notifications via Socket.IO.

## Tech Stack

- **Frontend:** React.js, CSS
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **AI Integration:** OpenAI GPT-4 API

## Getting Started

### Prerequisites

- Node.js (v18+)
- MongoDB
- OpenAI API Key ([get one here](https://platform.openai.com/))
- (Optional) RabbitMQ for advanced workflows

### Installation

1. **Clone the repository**
    ```
   git clone https://github.com/nayak044/AI-Code-Review-and-Analysis-Platform.git
   AI-Code-Review-and-Analysis-Platform
    ```

2. **Set up environment variables**
    - Copy `.env.example` to `.env` and fill in your MongoDB URI and OpenAI API key.

3. **Install dependencies**
    ```
    cd backend
    npm install
    cd ../frontend
    npm install
    ```

4. **Start the backend server**
    ```
    cd ../backend
    npm start
    ```

5. **Start the frontend**
    ```
    cd ../frontend
    npm start
    ```

## Usage

- Paste your code snippet into the input box on the homepage.
- Submit for review; the AI will analyze and provide feedback.
- View previous reviews and feedback in the history section.

## Configuration

- Customize review rules in the configuration file (if implemented).
- Adjust severity thresholds and reviewer preferences as needed.

---

