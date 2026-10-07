# Deploy OFC on a new server

1. Install Docker and Docker Compose.
2. Clone this repository.
3. Create .env from .env.example.
4. Set APP_URL to the server URL and add required secrets.
5. Run: docker compose up -d --build

The application listens on port 3000.

Never commit production .env files, Firebase private credentials, or Telegram bot tokens.
