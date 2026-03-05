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

## Quick Deploy to Vercel (Easiest Way!)

### Method 1: Direct GitHub Deploy

1. Push these files to your GitHub repo:
   ```bash
   git add .
   git commit -m "Add Guitar Quest app"
   git push origin main
   ```

2. Go to [vercel.com](https://vercel.com) and sign in

3. Click "Add New" → "Project"

4. Import your GitHub repository: `learning_guitar`

5. Click "Deploy" (no configuration needed!)

6. Your app will be live at `https://your-project.vercel.app`

### Method 2: Direct File Upload

1. Go to [vercel.com](https://vercel.com)
2. Click "Add New" → "Project"  
3. Drag and drop just the `index.html` file
4. Deploy!

## Files

- `index.html` - Complete standalone app (everything is in this one file!)
- `vercel.json` - Vercel configuration
- `README.md` - This file

## Local Testing

Just open `index.html` in any web browser - it works immediately!

Or use a simple server:

```bash
# Python
python -m http.server 8000

# Node.js  
npx http-server
```

Then open `http://localhost:8000`

## Tech Stack

- React 18 (CDN)
- Tailwind CSS (CDN)
- Lucide Icons (CDN)
- Pure HTML/JavaScript (no build required!)

## Browser Support

Works on all modern browsers (Chrome, Firefox, Safari, Edge)

## Troubleshooting

**Blank page on Vercel?**
- Make sure `index.html` is in the root directory
- Check browser console for errors (F12)
- Try clearing cache and hard refresh (Ctrl+Shift+R)

**App not loading?**
- Ensure you have internet connection (loads React from CDN)
- Check that scripts are not blocked by ad blockers

## License

Free to use for educational purposes.
