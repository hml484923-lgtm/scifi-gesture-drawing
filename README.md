# JARVIS AR Air Canvas

## Introduction
This is a web-based Augmented Reality drawing application using Google MediaPipe. It allows users to draw on the screen using hand gestures without any physical input devices. The interface is designed with a sci-fi HUD style, featuring neon glowing strokes and particle effects.

## Features
- **Real-time Tracking:** Uses computer vision to track hand movements via the webcam.
- **Gesture Control:** Fully controlled by hand gestures (no mouse or keyboard needed).
- **Sci-Fi Interface:** Includes a mirrored video feed with a grid overlay and dynamic UI.
- **Particle Effects:** Drawings dissolve into particles when the screen is cleared.
- **Zoom Support:** Supports dual-hand gestures to scale the canvas.

## Technology Stack
- HTML5
- CSS3
- JavaScript (ES6)
- Google MediaPipe Hands
- HTML5 Canvas API

## How to Run
This project requires camera access. Due to browser security restrictions, it must be run under **HTTPS** or **Localhost**. It will not work if you simply double-click the HTML file.

### Method 1: Visual Studio Code (Recommended)
1. Clone or download this repository.
2. Open the folder in VS Code.
3. Install the "Live Server" extension.
4. Right-click `index.html` and select "Open with Live Server".

### Method 2: GitHub Pages
1. Upload the code to a GitHub repository.
2. Go to Settings > Pages.
3. Set the source branch to `main` and save.
4. Access the generated URL.

## Gesture Guide

| Gesture | Action |
| :--- | :--- |
| **Open Palm** | Show or hide the tool menu. |
| **Index Finger** | Move the cursor (hover over buttons to select). |
| **Pinch (Thumb & Index)** | Start drawing or writing. |
| **Peace Sign (V Shape)** | Clear the canvas with a dissolve effect. |
| **Two Hands** | Move hands apart to zoom in, together to zoom out. |

## License
MIT License
