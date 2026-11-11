X-RAY MIRROR — REAL-TIME AR DEMO

WHAT IT DOES
- Requests webcam permission when the page opens.
- Mirrors the live camera preview.
- Tracks up to two hands and draws an X-ray-style skeletal hand overlay.
- Adds a face/skull guide overlay based on visible face landmarks.
- Includes controls for layers, glow, opacity and bone thickness.

IMPORTANT LIMITATION
This is an augmented-reality visual effect, not a medical X-ray. It estimates visible hand and face landmarks; it cannot see actual bones, muscles, organs or diagnose injuries.

HOW TO RUN (WINDOWS)
1. Extract the ZIP file.
2. Install Python 3 if it is not already installed.
3. Double-click start-local-server.bat.
4. Open http://localhost:8000 in Chrome or Edge.
5. Allow camera access when prompted.

You can also host the files on an HTTPS website. Browsers generally require HTTPS (or localhost) for webcam access.

REQUIREMENTS
- Webcam
- Modern Chrome or Edge
- Internet connection (MediaPipe tracking libraries load from jsDelivr CDN)
