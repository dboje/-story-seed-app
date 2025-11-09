# Story Seed Backend - Vercel Deployment

This is the backend API for your Story Seed interactive page.

## Files in this folder:

- `api/story-seed.js` - The serverless function that handles API calls
- `vercel.json` - Configuration for Vercel
- `package.json` - Node.js configuration
- `public/index.html` - Your Story Seed webpage

## Deployment Steps:

### 1. Upload to GitHub
- All these files will go in a repository
- David will do this through GitHub's web interface

### 2. Connect to Vercel
- Sign up at vercel.com with GitHub
- Import your repository
- Add environment variable: ANTHROPIC_API_KEY

### 3. Your API will be live at:
`https://your-project-name.vercel.app/api/story-seed`

### 4. Update your HTML file
The frontend HTML will automatically call this API endpoint.

## Cost: FREE
- Vercel free tier: 100GB bandwidth/month
- More than enough for your Story Seed page
