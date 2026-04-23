# Invisibility Cloak Demo

An interactive browser-based prototype demonstrating a real-time "invisibility cloak" effect using your webcam.

## How It Works

The demo uses your device camera and computer vision techniques to:
- Capture a background frame as a reference
- Detect a specific color (e.g. a green/blue cloth) in the live video feed
- Replace that color region with the captured background in real time
- Creating the illusion that the object — or person — wearing the cloak becomes invisible

## Try It

Open `invisibility_cloak_demo.html` in a browser (Chrome recommended), grant camera access, and follow the on-screen instructions.

No installation or dependencies required — runs entirely in the browser.

## Tech Stack

- HTML5 Canvas
- JavaScript (WebRTC / getUserMedia)
- Real-time pixel manipulation via Canvas 2D API
