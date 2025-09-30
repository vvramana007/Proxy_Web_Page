
# Gloria News Feed

This project includes both a frontend React application and a backend Express server to securely fetch crypto news.

## Setup Instructions

### Backend Setup

1. Navigate to the server directory:
   ```
   cd server
   ```

2. Install dependencies:
   ```
   npm install
   ```

3. Create an `.env` file based on `.env.example`:
   ```
   cp .env.example .env
   ```

4. Add your Crypto Briefing API key to the `.env` file

5. Start the server:
   ```
   npm run dev
   ```

The server will start on port 5000 by default.

### Frontend Setup

1. From the project root, install dependencies:
   ```
   npm install
   ```

2. Start the frontend development server:
   ```
   npm run dev
   ```

The frontend will use the backend API to securely fetch news data from the Crypto Briefing API.
