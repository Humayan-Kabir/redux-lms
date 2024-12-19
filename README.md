# Redux LMS

A learning management system built with React, Redux Toolkit, and JSON Server.

## Features
- 📺 Video listing with search and filtering
- 🏷️ Tag-based navigation
- 🎯 Related video suggestions
- 👍 Like/Unlike functionality
- 🎨 Modern UI with Tailwind CSS
- 🔄 State management with Redux Toolkit
- 📱 Responsive design

## Tech Stack
- React 18
- Redux Toolkit
- React Router DOM
- Axios
- JSON Server
- Tailwind CSS

## Getting Started

1. Install dependencies:
```bash
npm install
```

2. Start JSON Server (in one terminal):
```bash
json-server --watch server/db_videos.json --port 9000
```

3. Start development server (in another terminal):
```bash
npm run start    # Development mode
# or
npm run prod     # Production mode locally
```

## Build Commands
```bash
npm run build    # Production build
npm run preview  # Preview production build
```

## Environment Variables
Create `.env.development` or `.env.production` with:
```
VITE_API_URL=http://localhost:9000
