# BitPulse Backend (Render Free Tier)

This backend is designed to work on Render's free tier. It includes:
- Basic Express server
- CORS enabled
- Renders `BitPulse backend is live` on the root route

## Deploy

1. Push this to a public GitHub repository
2. Go to https://render.com
3. Click "New Web Service"
4. Connect your GitHub and import this repo
5. Use these settings:
   - Environment: Node
   - Build Command: `npm install`
   - Start Command: `node index.js`
   - Free Plan: Enabled

## Wake Up Trick

Use a tool like [UptimeRobot](https://uptimerobot.com) to ping your Render URL every 10 mins to keep it awake.