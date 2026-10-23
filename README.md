# Thanik AI Academy

A static Progressive Web App for generating YouTube scripts in Telugu or English.

## Run it locally

Serve this folder using any local web server; do not open `index.html` directly from the filesystem because service workers require HTTP or HTTPS. For example, after installing Python:

```powershell
python -m http.server 8080
```

Open `http://localhost:8080` in Chrome or Edge.

## Setup required

The app works without setup in demo-script mode. To use Gemini-generated scripts, create your own Gemini API key in Google AI Studio and paste it into the optional field at runtime. The key is not stored by the app.

For public deployment, do not expose a shared Gemini key in this frontend. Add a protected backend endpoint instead.

## Deploy and install

Deploy these files to an HTTPS host such as GitHub Pages. Then use Chrome's **Install app** or **Add to Home screen**. This is a PWA, not an APK. To produce an APK, package the deployed PWA with PWABuilder or a Trusted Web Activity workflow.
