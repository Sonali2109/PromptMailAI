# Prompt Mail AI

The **Prompt Mail AI** is a Chrome extension that provides auto-generated email replies based on the tone and style requirements of the email (professional, casual, friendly). This project integrates **SpringBoot** for the backend, **ReactJS** for the frontend, and a **user-defined Chrome extension** to provide the core functionality. The extension utilizes the **Gemini API 2.0 model** to generate replies dynamically.

## Table of Contents
1. [Description](#description)
2. [Technologies Used](#technologies-used)
3. [Installation](#installation)
4. [Usage](#usage)
5. [How it Works](#how-it-works)
6. [Contact](#contact)

## Description

This project enables users to automate their email responses through a Chrome extension. The extension allows users to select the tone of the reply (professional, casual, or friendly), and the system will generate the appropriate response based on the input email, using the **Gemini API 2.0** model.

- **Backend**: Built with **SpringBoot**, providing API endpoints for processing and handling email data.
- **Frontend**: Built with **ReactJS** for seamless integration with the Visual Studio Code environment.
- **Chrome Extension**: A user-defined extension that interacts with Gmail and utilizes the generated responses from the backend.

## Technologies Used

- **Backend**: SpringBoot
- **Frontend**: ReactJS
- **API**: Gemini API 2.0 (for AI-generated responses)

## Installation

### 1. Clone the Repository
First, clone the repository to your local machine:

```bash
git clone https://github.com/Sonali2109/PromptMailAI.git
cd email-ai-extension
```

### 2. Setup Backend (SpringBoot)
Navigate to the backend directory and run the SpringBoot application:
The backend will be running on http://localhost:8080/

```bash
cd email-writer-sb
./mvnw spring-boot:run
```

### 3. Setup Frontend (ReactJS)
Navigate to the frontend directory and install the dependencies:
The frontend will be available at http://localhost:3000/

```bash
cd email-writer-react
npm install
npm run dev
```

### Usage
  - Open your Gmail account in Chrome.
  - Compose a new email or open an existing email to reply to.
  - Click on the extension icon in the Chrome toolbar to open the interface.
  - Select the desired tone for your email reply (Professional, Casual, Friendly).
  - The extension will send the email data to the backend, which will process it using the Gemini API 2.0 model.
  - The generated email response will be displayed, and you can choose to insert it directly into your reply.

### Working 
  - The Chrome extension captures the email content and sends it to the SpringBoot backend.
  - The backend communicates with the Gemini API 2.0 model to generate a response based on the tone selected.
  - The generated response is sent back to the frontend and displayed in the Chrome extension.
  - Users can then review, modify, or send the generated response directly.
      
### Contact
For any inquiries, feel free to reach out:

- Author: Sonali Chaudhari
- Linkedin Profile: https://www.linkedin.com/in/sonali-chaudhari-08a84620b/
