# Chatapp

A full-stack chat application built with React and Express. It combines a modern chat interface with an OpenAI-powered backend and third-party chat services.

## Features

- Real-time-style chat interface
- User sign-in flow
- OpenAI API integration
- File upload support
- Client state management with Redux Toolkit
- Separate frontend and backend applications

## Tech Stack

### Client

- React
- Vite
- Redux Toolkit
- React Router
- React Chat Engine
- Sass

### Server

- Node.js
- Express
- OpenAI API
- Helmet
- Morgan

## Getting Started

Start the API:

```bash
cd server
npm install
npm run dev
```

Start the frontend in another terminal:

```bash
cd app
npm install
npm run dev
```

Configure required API keys and service credentials in local environment files. OpenAI requests and secrets should remain on the server and must never be committed to Git.
