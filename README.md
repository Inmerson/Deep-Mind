# Run and deploy your AI Studio app

This contains everything you need to run your app locally.

## Frontend

**Prerequisites:** Node.js

1. Install dependencies:
   `npm install`
2. Set the `GEMINI_API_KEY` in [.env.local](.env.local) to your Gemini API key
3. Run the app:
   `npm run dev`

## Backend

**Prerequisites:** Python 3.11+

1. Navigate to the backend folder:
   `cd backend`
2. Install dependencies:
   `pip install fastapi uvicorn sqlalchemy pydantic`
3. Run the server:
   `uvicorn main:app --reload`
