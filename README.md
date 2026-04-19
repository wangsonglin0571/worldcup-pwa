# worldcup-pwa

Minimal PWA projects for World Cup national-team tracking.

Current version:

- Root landing page
- Japan single-page PWA in `/japan`
- France single-page PWA in `/france`
- All match times shown in Beijing time (`UTC+8`)

Core sections:

- next match
- one-line status
- World Cup journey timeline
- key players
- footer status bar

Structure:

- `/` entry page
- `/japan` Japan team PWA
- `/france` France team PWA

Local preview:

```bash
cd /Users/wangsonglin/worldcup-pwa
python3 -m http.server 8000
```

Then open `http://localhost:8000`.
