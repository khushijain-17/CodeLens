\# CodeLens – AI-Powered GitHub Repository Explainer



CodeLens is a full-stack web application that helps developers understand GitHub repositories using AI.



Users can provide a GitHub repository, clone its contents, explore the project structure, view source code, and get AI-powered explanations of individual files.



\## 🚀 Features



\* Clone GitHub repositories

\* Visualize repository file structure

\* Browse source-code files

\* View file contents

\* Generate AI-powered code explanations

\* Store searched repositories

\* RESTful backend APIs

\* Interactive React frontend



\## 🛠️ Tech Stack



\### Frontend



\* React.js

\* Vite

\* Axios

\* React Router

\* HTML

\* CSS

\* JavaScript



\### Backend



\* Java

\* Spring Boot

\* REST APIs

\* JGit

\* Maven



\### Database



\* PostgreSQL



\### AI



\* Groq API



\## 🏗️ Architecture



```text

&#x20;               ┌─────────────────────┐

&#x20;               │     React.js        │

&#x20;               │      Frontend       │

&#x20;               └──────────┬──────────┘

&#x20;                          │

&#x20;                          │ REST API

&#x20;                          ▼

&#x20;               ┌─────────────────────┐

&#x20;               │    Spring Boot      │

&#x20;               │       Backend       │

&#x20;               └──────┬───────┬──────┘

&#x20;                      │       │

&#x20;            ┌─────────┘       └────────────┐

&#x20;            ▼                              ▼

&#x20;    ┌───────────────┐              ┌───────────────┐

&#x20;    │  PostgreSQL   │              │   Groq API    │

&#x20;    │   Database    │              │      AI       │

&#x20;    └───────────────┘              └───────────────┘

&#x20;                      │

&#x20;                      ▼

&#x20;                 ┌─────────┐

&#x20;                 │  JGit   │

&#x20;                 │ GitHub  │

&#x20;                 │ Clone   │

&#x20;                 └─────────┘

```



\## 📁 Project Structure



```text

CodeLens/

│

├── Backend/

│   ├── src/

│   ├── pom.xml

│   └── ...

│

├── Frontend/

│   ├── src/

│   ├── package.json

│   └── ...

│

├── .gitignore

└── README.md

```



\## ⚙️ Getting Started



\### Prerequisites



Make sure you have installed:



\* Java 17+

\* Maven

\* Node.js

\* npm

\* PostgreSQL



\### Backend Setup



Navigate to the backend:



```bash

cd Backend

```



Configure your PostgreSQL database and required API credentials.



Then run:



```bash

mvn spring-boot:run

```



The Spring Boot backend will start on its configured port.



\### Frontend Setup



Open another terminal and navigate to:



```bash

cd Frontend

```



Install dependencies:



```bash

npm install

```



Start the development server:



```bash

npm run dev

```



Open the URL provided by Vite in your browser.



\## 🔑 Environment Variables



Do not commit API keys, database passwords, or other secrets to GitHub.



Configure sensitive values through environment variables or your local configuration.



Example:



```text

GROQ\_API\_KEY=your\_api\_key

DATABASE\_URL=your\_database\_url

```



\## 🎯 Future Improvements



\* Support multiple AI providers

\* Add authentication and user accounts

\* Improve repository visualization

\* Add repository-level AI analysis

\* Generate architecture diagrams automatically

\* Deploy the complete application to the cloud



\## 👩‍💻 Author



Khushi Jain



GitHub: https://github.com/khushijain-17



