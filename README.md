# Point Cloud Studio

Interactive 3D point cloud editor with hand tracking using Three.js and MediaPipe.

## Requirements

- Python 3.x installed
- A modern web browser (Google Chrome or Microsoft Edge recommended)
- Webcam access enabled

## Installation

1. Download or clone the project.

2. Open a terminal inside the project folder.

3. Start a local HTTP server using Python:

```bash
python -m http.server 8000
```

If your system uses `python3`:

```bash
python3 -m http.server 8000
```

4. Open your browser and go to:

```
http://localhost:8000
```

5. Open `index.html` if it is not loaded automatically.

6. Allow camera permissions when the browser asks.

## Notes

- Do **not** open the HTML file directly (double-click), as camera access and some browser features may not work correctly.
- Internet connection is required the first time because Three.js and MediaPipe are loaded from CDNs.
- Chrome or Edge is recommended for the best compatibility.

## Technologies

- HTML5
- CSS3
- JavaScript
- Three.js
- MediaPipe Hands