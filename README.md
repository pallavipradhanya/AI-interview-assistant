# AI Interview Assistant 🤖

An AI-powered interview preparation platform designed to help users improve their interview skills through personalized questions, interactive mock interviews, and AI-generated feedback.

## 📌 Project Overview

The AI Interview Assistant helps candidates prepare for technical and general interviews in a more structured and interactive way. It uses Artificial Intelligence to generate relevant interview questions and provide feedback that helps users identify areas for improvement.

The platform aims to make interview preparation more accessible, personalized, and effective.

## ✨ Features

- **AI-Generated Interview Questions:** Generates interview questions based on the selected interview topics.
- **Mock Interviews:** Provides an interactive environment to practice answering interview questions.
- **AI-Based Feedback:** Offers feedback to help users understand and improve their responses.
- **Personalized Preparation:** Supports a more focused interview preparation experience.
- **User Authentication:** Provides user account and authentication functionality.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Next.js | Frontend framework |
| React.js | User interface |
| JavaScript | Application development |
| Tailwind CSS | UI styling |
| Gemini AI | AI-powered interview assistance |
| Clerk | User authentication |
| Neon Database | Database services |
| Node.js | JavaScript runtime |

## 📂 Project Structure

```text
ai-interview-assistant/
│
├── app/
│   ├── (auth)/
│   ├── about-us/
│   ├── dashboard/
│   ├── how-it-works/
│   └── layout.js
│
├── utils/
│   └── GeminiAIModal.js
│
├── public/
├── package.json
├── package-lock.json
├── .gitignore
└── README.md
```

## ⚙️ Installation and Setup

### 1. Clone the Repository

```bash
git clone https://github.com/pallavipradhanya/AI-interview-assistant.git
```

### 2. Navigate to the Project Directory

```bash
cd AI-interview-assistant
```

### 3. Install Dependencies

```bash
npm install
```

### 4. Configure Environment Variables

Create a `.env` file in the project root and add the required API keys and database credentials.

Configure the environment variables required by your application, including Gemini AI, Clerk authentication, and Neon Database.

**Important:** Never upload your `.env` file or expose API keys and database credentials on GitHub.

### 5. Start the Development Server

```bash
npm run dev
```

Open your browser and visit:

```text
http://localhost:3000
```

## 🚀 Future Enhancements

- Voice-based mock interview functionality.
- Real-time analysis of interview responses.
- Detailed performance reports and progress tracking.
- Support for multiple programming languages and technical domains.
- Improved personalization based on user performance.

## 🎯 Project Objective

The primary objective of this project is to develop an intelligent interview preparation platform that combines web technologies and Artificial Intelligence to help candidates build confidence, strengthen their technical knowledge, and improve their interview performance.



