# AI First Coach

A web app that coaches female entrepreneurs to become AI-first.

- `index.html` - Marketing landing page (7-day free trial signup)
- `app.html` - The actual coach app: signup, onboarding, chat with Claude, 30-day roadmap, prompt library, settings

## How it works

Fully static site. No backend. Runs entirely in the browser.

- Accounts, profiles, chat history and roadmap are stored in the user's `localStorage`
- The coach chat calls the Anthropic API directly from the browser using the user's own API key (saved in Settings)

## Deploy

Any static host works. This repo is set up for Vercel. No build step.

## Local preview

Double-click `index.html` or run `python3 -m http.server` in this folder.
