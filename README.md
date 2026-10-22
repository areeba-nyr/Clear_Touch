# ClearTouch

**A little less scrolling. A little more touching glass.**

ClearTouch is an interactive computer vision project that explores the idea of turning a webcam into a digital foggy mirror. Using hand tracking, it lets users interact with a glass-inspired visual experience directly in the browser.

The project combines real-time hand tracking with creative web development to explore a more natural way of interacting with digital visuals.

## Features

- Real-time hand tracking through a webcam
- Interactive, foggy-mirror-inspired visuals
- Gesture-based interaction
- Browser-based experience
- Lightweight web technologies

## Tech Stack

- **HTML** — page structure
- **CSS** — styling and visual design
- **JavaScript** — interaction and application logic
- **MediaPipe** — hand tracking and computer vision

## Getting Started

### Requirements

- Python installed on your computer
- A modern web browser
- A working webcam

### Run Locally

1. Clone or download this repository.
2. Open the project folder in VS Code.
3. Open the terminal in the project folder.
4. Start a local development server:

   ```bash
   python -m http.server 8000
   ```

   If the command above does not work on Windows, try:

   ```bash
   py -m http.server 8000
   ```

5. Open the following address in your browser:

   `http://localhost:8000`

6. Allow camera and microphone permissions if requested by the application.

## Troubleshooting

| Issue | Possible solution |
|---|---|
| Camera does not open | Check browser permissions and close other applications that may be using the webcam. |
| Hand tracking is inaccurate | Improve lighting and keep your hand clearly visible within the camera frame. |
| Interactions do not respond | Run the project through a local server and check the browser console for JavaScript errors. |
| Camera access fails online | Ensure the website uses HTTPS and camera permissions are enabled. |
| The page does not load correctly | Refresh the page and check your internet connection if external libraries are loaded from a CDN. |

## Project Overview

ClearTouch is a creative computer vision experiment that brings together browser-based hand tracking and interactive visual design.

The goal is simple: explore how ordinary hardware, open-source tools, and a little imagination can create a more interactive digital experience.

**Built with curiosity. Refined through debugging. Made to interact.**
