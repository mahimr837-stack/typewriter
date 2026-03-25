# Vintage Typewriter

## Overview
An interactive vintage typewriter experience built as a single self-contained HTML file. Users can type on a beautifully rendered typewriter with animated key presses, typebar strikes, and text appearing on the paper.

## Tech Stack
- Pure HTML/CSS/JavaScript (no build system, no dependencies)
- Single file: `index.html`
- Served via Python's built-in HTTP server in development

## Project Structure
```
index.html    # The entire application (HTML, CSS, JS, embedded assets)
```

## Running the App
The app is served by Python's HTTP server:
```
python3 -m http.server 5000 --bind 0.0.0.0
```

## Deployment
- Deployment target: **static**
- Public directory: `.` (root)
- No build step required
