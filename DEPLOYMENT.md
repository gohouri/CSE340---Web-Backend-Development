# Deployment Guide for CSE Motors

## GitHub Repository Setup

1. **Initialize Git Repository** (if not already done):
   ```bash
   git add .
   git commit -m "Initial commit: CSE Motors website"
   git branch -M main
   git remote add origin <your-github-repo-url>
   git push -u origin main
   ```

2. **Push Updates**:
   ```bash
   git add .
   git commit -m "Update: [describe your changes]"
   git push
   ```

## Render.com Deployment

### Step 1: Create New Web Service
1. Go to [Render.com](https://render.com) and sign in
2. Click "New +" and select "Web Service"
3. Connect your GitHub repository

### Step 2: Configure Web Service
- **Name**: `cse-motors` (or your preferred name)
- **Environment**: `Node`
- **Build Command**: `npm install`
- **Start Command**: `npm start`
- **Plan**: Free (or your preferred plan)

### Step 3: Environment Variables
Add these environment variables if needed:
- `PORT`: Will be set automatically by Render
- `NODE_ENV`: `production`

### Step 4: Deploy
1. Click "Create Web Service"
2. Wait for the build to complete
3. Your site will be available at: `https://your-app-name.onrender.com`

## Testing Your Deployment

1. **Check Functionality**: Visit your deployed URL and test all features
2. **Responsive Design**: Test on different screen sizes
3. **Accessibility**: Use WAVE browser extension to check accessibility
4. **Cross-browser**: Test in different browsers

## Troubleshooting

### Common Issues:
- **Build Failures**: Check that all dependencies are in `package.json`
- **Port Issues**: Ensure your app uses `process.env.PORT`
- **Static Files**: Verify that `public` folder is being served correctly

### Debug Commands:
```bash
# Check local build
npm install
npm start

# Check for syntax errors
node -c app.js

# Validate HTML/CSS (use online validators)
```

## Assignment Submission Checklist

Before submitting, ensure you have:
- ✅ Working local development environment
- ✅ GitHub repository with all code pushed
- ✅ Render.com deployment working correctly
- ✅ Both URLs ready for submission:
  - GitHub Repository URL: `https://github.com/yourusername/your-repo-name`
  - Render.com Production URL: `https://your-app-name.onrender.com`

## Notes
- Render.com free tier may have some limitations
- First deployment might take 5-10 minutes
- Subsequent deployments are faster
- Keep your GitHub repository updated with all changes
