# Football Live Stream Frontend

Single-page web application powered by **Hls.js** that connects to verified HLS live streams with an ultra-sleek dark mode interface (Charcoal, Pitch Black, Electric Gold, and Cyan).

## Features
- **Hls.js Engine**: High performance decoding of `.m3u8` streams across modern browsers.
- **Auto Manifest Ingestion**: Automatically loads channels from local `working_streams.json` or syncs directly with the remote GitHub backend repository.
- **Safari / WebKit Native Fallback**: Seamless playback on iOS and macOS devices.
- **Active Channel Switching**: Real-time channel switching without video overlay/audio overlap.
- **Manual Input Bar**: Test any custom HLS URL directly in the player.

## How to Run Locally

You can serve this frontend using any static web server:

### Using Python:
```bash
python -m http.server 8080
```
Then visit [http://localhost:8080](http://localhost:8080).

### Using Node.js (npx serve):
```bash
npx serve .
```

## Deployment
Can be deployed instantly on **GitHub Pages**, **Vercel**, or **Netlify** by pointing to `index.html`.
