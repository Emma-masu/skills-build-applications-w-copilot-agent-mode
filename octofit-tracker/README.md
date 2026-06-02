# OctoFit Tracker

A modern multi-tier fitness tracking application built with React 19, Node.js/Express, TypeScript, and MongoDB.

## Architecture

```
octofit-tracker/
├── frontend/          # React 19 + Vite
│   ├── src/
│   ├── package.json
│   ├── vite.config.js
│   └── index.html
└── backend/           # Node.js + Express + TypeScript
    ├── src/
    ├── package.json
    ├── tsconfig.json
    └── .env.example
```

## Port Configuration

- **Frontend**: http://localhost:5173 (React + Vite)
- **Backend API**: http://localhost:8000 (Express)
- **MongoDB**: mongodb://localhost:27017 (Database)

## Quick Start

### Prerequisites
- Node.js (v16 or higher)
- MongoDB (running locally on port 27017)

### Frontend Setup

```bash
cd octofit-tracker/frontend
npm install
npm run dev
```

### Backend Setup

```bash
cd octofit-tracker/backend
npm install
cp .env.example .env
npm run dev
```

## Technologies Used

### Frontend
- React 19
- Vite (build tool)
- ES Modules

### Backend
- Node.js
- Express.js
- TypeScript
- Mongoose (MongoDB ODM)
- CORS support

### Database
- MongoDB
- Mongoose for data modeling

## Available Scripts

### Frontend
- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build

### Backend
- `npm run dev` - Start development server with ts-node
- `npm run build` - Compile TypeScript to JavaScript
- `npm start` - Start production server
- `npm run watch` - Watch mode for development

## Environment Variables

Create a `.env` file in the backend directory:

```
PORT=8000
MONGODB_URI=mongodb://localhost:27017/octofit-tracker
NODE_ENV=development
```
