# Slither X

A lightweight 3D Slither.io-style game built with Three.js.

## Deploy

1. Upload this folder to a GitHub repository.
2. Import the repo into Vercel.
3. Deploy as a static site.
4. Replace `YOUR-DOMAIN.vercel.app` in `index.html` with your actual Vercel domain.
5. Redeploy.
6. Test the public URL and X Player Card metadata.

## Important X Player Card fields

The page uses:
- `twitter:card=player`
- `twitter:player=https://YOUR-DOMAIN.vercel.app/`
- `twitter:player:width=720`
- `twitter:player:height=405`
- `twitter:image=...`

The player URL needs to be HTTPS.

## Note

This is a single-player prototype with client-side bots. Real multiplayer requires a backend/WebSocket server.
