# Lineup DJ Website

This is the landing page for Lineup DJ, an iOS app that creates walkout songs and AI voice introductions for youth sports.

## Local Development

To run the website locally:

1. Simply open `index.html` in your web browser
2. No build process or dependencies required

## Deployment

To deploy the website:

1. Upload all files to your web hosting service
2. Ensure the `.well-known/apple-app-site-association` file is served with the correct content type:
   ```
   Content-Type: application/json
   ```
3. Configure your domain (lineupdj.app) to point to your hosting service
4. Set up SSL/HTTPS (required for Universal Links)

## Universal Links Setup

1. Replace `YOUR_TEAM_ID` in `.well-known/apple-app-site-association` with your actual Apple Developer Team ID
2. Ensure the AASA file is accessible at `https://lineupdj.app/.well-known/apple-app-site-association`
3. Configure your iOS app to handle Universal Links

## File Structure

- `index.html` - Main landing page
- `styles.css` - Styling
- `script.js` - Interactive elements and deep link handling
- `.well-known/apple-app-site-association` - Universal Links configuration
- `README.md` - This file

## Contact

For support or questions, email support@lineupdj.app 