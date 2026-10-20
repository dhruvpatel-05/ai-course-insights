# AI Course Insights

A full-stack web app that analyzes student assignments with Google's Gemini API and turns them into a dashboard of performance insights. Upload your coursework, and AI Course Insights tracks how you're doing across assignments and surfaces trends over time.

Built at LA Hacks.

## Features

- **Assignment analysis:** upload assignments and get AI-generated feedback and performance insights from the Gemini API
- **Progress dashboard:** an interactive view of academic progress across everything you've uploaded
- **Trend tracking:** a data pipeline that aggregates results across documents to show patterns over time

<!-- TODO: adjust the feature list above to match exactly what the app does -->

## Tech stack

| Layer | Tools |
|---|---|
| Frontend | React |
| Backend | Node.js, Express |
| Database | MongoDB |
| AI | Google Gemini API |

## Project structure

```
ai-course-insights/
├── frontend/     # React client: upload flow and dashboard
├── backend/      # Express API: Gemini calls, data pipeline, MongoDB access
└── package.json
```

## Running locally

**Prerequisites:** Node.js, a MongoDB connection string, and a Gemini API key.

1. Clone the repo and install dependencies:

   ```bash
   git clone https://github.com/dhruvpatel-05/ai-course-insights.git
   cd ai-course-insights
   npm install
   ```

2. Create a `.env` file in `backend/`:

   ```
   GEMINI_API_KEY=your_key_here
   MONGO_URI=your_connection_string
   ```

3. Start the app:

   ```bash
   npm start
   ```
