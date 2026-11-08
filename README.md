# NEXUS Desk Hub — v0.1

A lightweight dashboard prototype designed for the iPad 4 running iOS 10.3.4.

## Project structure
- index.html — dashboard structure
- css/nexus.css — visual styling
- js/nexus.js — live clock and date

## Local development
Open this folder in Visual Studio Code. You can preview index.html directly in a browser or run a local static server:

```bash
python3 -m http.server 8000
```

Then visit http://localhost:8000.

## GitHub Pages
This project is intended to be published from the repository root using GitHub Pages:
Settings → Pages → Deploy from a branch → main → /(root).

## Compatibility
The interface uses conservative HTML, CSS and JavaScript and avoids modern framework dependencies. It is a visual prototype; Spotify, weather, calendar and IoT integrations are not connected yet.

## Security
Do not place Spotify client secrets, access tokens, or other private credentials in this public repository. Spotify integration should use Authorization Code with PKCE.
