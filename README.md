# Code-snippet-finder
A full-stack web app to search GitHub repositories and extract code snippets, built with React.js, Node.js, Express.js and the GitHub REST API.  Topics to add: react nodejs expressjs github-api rest-api javascript full-stack mern-stack


# Code Snippet Finder

A full-stack web application that lets users search GitHub repositories and extract relevant code snippets quickly, without browsing through repositories manually.

## Features
- Search GitHub repositories by keyword
- Extract and display relevant code snippets from results
- Express.js backend that integrates the GitHub REST API
- Dynamic React.js interface for viewing results

## Tech Stack
- **Front-End:** React.js, JavaScript, HTML, CSS
- **Back-End:** Node.js, Express.js
- **API:** GitHub REST API

## How It Works
1. The user enters a search query in the React interface.
2. The request is sent to the Express.js backend.
3. The backend calls the GitHub REST API and processes the response.
4. Relevant code snippets are returned and displayed in the UI.

## Getting Started

### Prerequisites
- Node.js and npm installed
- A GitHub personal access token (optional, but it raises API rate limits)

### Installation
```bash
git clone https://github.com/Kruthikar2804/<your-repo-name>.git
cd <your-repo-name>

# Backend
cd server
npm install
npm start

# Frontend (new terminal)
cd client
npm install
npm start
```

### Environment Variables
Create a `.env` file in the backend folder:

## Author
**Kruthika R**
