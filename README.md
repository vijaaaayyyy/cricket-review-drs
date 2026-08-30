# Cricket Review System (Live DRS)

Modern web-based Decision Review System for local cricket, box cricket, turf cricket, academy matches and amateur tournaments.

## Live demo
Open `index.html` or the Vercel/GitHub Pages URL after deploy.

## Features
- Live camera (phone/webcam)
- Continuous rolling 2-min buffer
- BALL DELIVERED timestamp
- TAKE REVIEW with auto last-ball focus
- Slow motion 0.25x-1x, frame step
- Review types + OUT / NOT OUT decisions
- Dark sports UI, mobile-first

## How to run locally
```bash
python3 -m http.server 8080
# open http://localhost:8080
```

Camera requires HTTPS or localhost.
