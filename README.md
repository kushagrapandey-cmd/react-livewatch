# React Live Clock

A small React interface that displays local time and provides a **Get Time** button.

## Code

`usestate-hook-practice-completed/src/components/App.jsx` uses `useState` to render the time and a one-second interval to refresh it.

## Run locally

```bash
cd usestate-hook-practice-completed
npm install
npm start
```

This early React 16/Create React App 3 exercise has no backend. Its interval is created during rendering rather than managed with effect cleanup; it is a fundamentals example, not a production timer implementation.
