# Guitar Quest - Learn Guitar in 8 Weeks 🎸

An interactive educational platform for children ages 8-14 to learn guitar with gamification, progress tracking, and competitive leaderboards.

## Features

- 21 comprehensive lessons from beginner to advanced
- Detailed lesson content with step-by-step instructions
- Gamification with XP points and levels
- Competitive leaderboard
- Multi-user support
- Progress tracking and streak system
- Interactive lesson completion

## Deploying to Vercel

### Option 1: Deploy via Vercel Dashboard (Easiest)

1. Go to [vercel.com](https://vercel.com) and sign in
2. Click "Add New" → "Project"
3. Import your Git repository (or upload these files)
4. Vercel will auto-detect the settings
5. Click "Deploy"

### Option 2: Deploy via Vercel CLI

1. Install Vercel CLI:
   ```bash
   npm i -g vercel
   ```

2. Navigate to this folder in your terminal:
   ```bash
   cd guitar-quest-app
   ```

3. Deploy:
   ```bash
   vercel
   ```

4. Follow the prompts and your app will be live!

### Option 3: Deploy via GitHub

1. Push this folder to a GitHub repository
2. Go to [vercel.com](https://vercel.com)
3. Click "Import Project"
4. Select your GitHub repository
5. Click "Deploy"

## File Structure

```
guitar-quest-app/
├── index.html       # Main HTML file
├── app.jsx          # React application code
├── vercel.json      # Vercel configuration
└── README.md        # This file
```

## Local Testing

To test locally, you can use any simple HTTP server:

```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx http-server
```

Then open `http://localhost:8000` in your browser.

## Tech Stack

- React 18
- Tailwind CSS
- Lucide Icons
- Vanilla JavaScript (no build step required)

## Browser Support

Works on all modern browsers (Chrome, Firefox, Safari, Edge)

## License

Free to use for educational purposes.
