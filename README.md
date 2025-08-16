# AI Meeting Summarizer - Frontend

This is the frontend application for the AI Meeting Summarizer. It provides a user-friendly interface for uploading meeting transcripts, generating AI-powered summaries, and sharing these summaries via email.

## Features

- Clean, responsive UI for transcript submission
- Custom instruction capabilities for AI summary generation
- Markdown preview of generated summaries
- Email sharing functionality
- File upload for various transcript formats
- Error handling and user feedback

## Tech Stack

- React 19
- Vite 7
- React Markdown for rendering summaries
- Axios for API calls

## Prerequisites

- Node.js 18 or higher
- npm or yarn
- Backend API endpoint

## Environment Variables

Create a `.env.production` file in the root directory with:

```
VITE_API_BASE_URL=https://your-backend-domain.com
```

For local development, create a `.env.development` file:

```
VITE_API_BASE_URL=http://localhost:5001
```

## Installation

```bash
# Install dependencies
npm install

# Start development server
npm run dev

# Build for production
npm run build

# Preview production build
npm run preview
```

## Deployment

This frontend is designed to be deployed to platforms like Netlify, Vercel, GitHub Pages, or any static site hosting service.

### Deployment Steps for Netlify/Vercel

1. Connect your repository
2. Set the build command to `npm run build`
3. Set the publish directory to `dist`
4. Configure environment variables
5. Deploy
