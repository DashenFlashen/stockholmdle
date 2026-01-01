# Stockholmdle

## References

Also read:
- ~/dev/dev-meta/claude/targets/firebase.md

Wordle-style game for Stockholm geography/culture.

## Tech Stack

**Platform(s):** Web
**Key Technologies:** HTML, CSS, JavaScript, Firebase Hosting

## Firebase Project

- **Project ID**: sl-gissaren
- **Hosting URL**: https://sl-gissaren.web.app

## Project Structure

```
stockholmdle/
├── public/
│   └── index.html      # Single-page web app
├── firebase.json       # Firebase Hosting configuration
└── .firebaserc        # Firebase project reference
```

## Deployment

```bash
firebase deploy
```

Deploys static files from `public/` directory to Firebase Hosting.

## Quick Reference

```bash
# Deploy to Firebase Hosting
firebase deploy

# Test locally
firebase serve
```
