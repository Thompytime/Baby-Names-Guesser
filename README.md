# England & Wales Baby Names 2024 Guesser

A Wordle-style daily guessing game featuring the top 100 boys' names from England & Wales 2024.

## Deploying to Vercel

1. Install Vercel CLI (if you haven't already):
   ```bash
   npm i -g vercel
   ```

2. Navigate to this directory and run:
   ```bash
   vercel
   ```

3. Follow the prompts to deploy

Or simply:
- Push this code to a GitHub repository
- Go to https://vercel.com
- Click "New Project"
- Import your GitHub repository
- Click "Deploy"

## Recommended Analytics Solutions

### Option 1: Plausible Analytics (Recommended)
- **Website**: https://plausible.io
- **Why**: Simple, privacy-friendly, GDPR compliant
- **Free Tier**: No (€9/month but has 30-day free trial)
- **Metrics**: Daily visitors, returning visitors, bounce rate, traffic sources
- **Setup**: Add one script tag to your HTML

### Option 2: Simple Analytics
- **Website**: https://simpleanalytics.com
- **Why**: Privacy-first, no cookies needed
- **Free Tier**: Has a free tier for small sites
- **Metrics**: Page views, unique visitors, referrers

### Option 3: Umami (Free & Self-hosted)
- **Website**: https://umami.is
- **Why**: Open source, can be hosted free on Vercel
- **Free Tier**: Yes (self-hosted)
- **Metrics**: Pageviews, visitors, bounce rate, retention

### Option 4: Fathom Analytics
- **Website**: https://usefathom.com
- **Why**: Privacy-focused, simple dashboard
- **Free Tier**: No (but has 7-day trial)

## Adding Analytics

Once you choose an analytics provider, you'll add a script tag to the `<head>` section of index.html.

Example for Plausible:
```html
<script defer data-domain="yourdomain.com" src="https://plausible.io/js/script.js"></script>
```

## Features

- Daily puzzle with a new name each day
- 5 guesses per game
- Color-coded feedback (green = correct position, yellow = wrong position, grey = not in name)
- Streak tracking
- Win rate statistics
- Guess distribution
- Social sharing (Twitter, Facebook, WhatsApp, SMS)
- Local storage for progress tracking

## Files

- `index.html` - Main game file
- `vercel.json` - Vercel configuration
- `README.md` - This file
