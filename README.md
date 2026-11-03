# McCrackFlix

A cinematic movie and TV discovery frontend built for the McCrack ecosystem.

## Features
- Responsive dark UI with cyan accents
- Trending, popular movies, popular TV, search, title details, and local watchlist
- TMDB catalog integration configured in Settings
- Optional direct HTTPS media URL for a stream you are authorized to use
- Single-file static frontend suitable for GitHub Pages

## Run it
Open `index.html` locally or enable GitHub Pages for this repository (Settings → Pages → Deploy from a branch → `main` → `/ (root)`).

## Configure the catalog
1. Create a TMDB account and obtain an API Read Access Token from https://www.themoviedb.org/settings/api.
2. Open McCrackFlix and choose **Settings**.
3. Paste the token and choose **Save & load catalog**.

The token is stored in this browser's localStorage. For a public production deployment, consider proxying API requests through a backend so you can manage rate limits and avoid exposing credentials. Follow TMDB's current API terms and attribution requirements.

## Playback status
This repository currently provides catalog discovery and a basic optional direct-stream URL connection. It does not automatically discover movie streams or include a media hosting backend. Configure only streams you own or are authorized to distribute. For a full personal media library, connect a separately hosted media server with proper authentication.

## License and attribution
Review the terms of each catalog, artwork, and media provider before deploying publicly. TMDB attribution and branding requirements apply when using its API.