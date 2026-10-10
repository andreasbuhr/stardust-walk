# Stardust Walk

Point your iPhone camera at people: everyone who walks through the picture drags a trail of colourful, sparkling clouds behind them. Each cloud drifts for a few seconds, then fades.

Open the page in Safari and allow camera access. Everything runs on the phone; no video is uploaded.

- Body tracking: [MediaPipe Pose Landmarker](https://ai.google.dev/edge/mediapipe/solutions/vision/pose_landmarker) (lite model, up to 4 people), bundled in `lib/`, `wasm/` and `models/` (Apache-2.0).
- Rendering: two canvases over the camera feed, soft clouds at reduced resolution plus additive sparkles.
- Tip: Share › Add to Home Screen runs it full screen.
