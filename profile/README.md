<img width="1920" height="949" alt="image" src="https://github.com/user-attachments/assets/0e3f25e0-787c-48c5-a1b1-27b78f7474b7" />

# Quizzlybear 🐻❓

**Quizzlybear** is a full-stack web application developed by a team of five Computer Engineering students at OsloMet.

The application makes it easy for users to create, customize, and answer interactive quizzes with automated scoring and leaderboards. The system is built with a decoupled architecture to ensure a clear separation of concerns between client and server.

---

## 🏗️ Architecture & Repositories

The source code is organized into two main components:

- **[Dansetorget/API](https://github.com/Dansetorget/API)**: A backend RESTful API built with **ASP.NET Core (C#)** for handling business logic, database modeling, and authentication.

- **[Dansetorget/Client](https://github.com/Dansetorget/Client)**: A responsive, user-friendly frontend built with **React** and **Tailwind CSS**.

---

## 🛠️ Tech Stack

- **Backend:** C#, .NET / ASP.NET Core, Entity Framework Core, SQL

- **Frontend:** JavaScript / TypeScript, React, Tailwind CSS

- **Tools & Methodologies:** Git, GitHub, REST API, Agile teamwork (5 members)

---

## 🚀 Getting Started Locally

To run the full application locally, you need to spin up both the backend service and the frontend client in separate terminal windows.

### Prerequisites
- [.NET 8 SDK](https://dotnet.microsoft.com/download)
- [Node.js](https://nodejs.org/) (v18+) and `npm`

### 1. Run the Backend (API)
```bash
# Clone the backend repository
git clone [https://github.com/Dansetorget/API.git](https://github.com/Dansetorget/API.git)
cd API

# Restore dependencies and start the API
dotnet restore
dotnet run --project QuizApi/QuizApi.csproj
```
### 2. Run the Frontend (Client)
```bash
# Clone the frontend repository
git clone [https://github.com/Dansetorget/Client.git](https://github.com/Dansetorget/Client.git)
cd Client
```
Create `.env.development` to configure communication with the API:
```bash
echo -e "VITE_PORT=3000\nVITE_API_URL=http://localhost:5110" > .env.development
```
Start the client:
```bash
npm install && npm run dev
```
© [2025] Dansetorget. All rights reserved.
