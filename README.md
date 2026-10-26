# AR/VR Viewer Demo

A browser-based **simulation** of an AR/VR viewer, built with plain HTML, CSS and JavaScript. No frameworks, no build step, no dependencies.

> **Note:** This is a 2D UI demo that mimics AR/VR interactions. It does not use WebXR, a camera, or a headset.

## Features

- **VR mode**: a gradient "virtual world" with floating objects you can click to spin
- **AR mode**: a scanning animation that detects markers one by one
- Add cubes, spheres and stars at random positions
- Click AR markers to remove them
- Clear all objects with one button
- Live status bar showing the current mode and object count
- Responsive layout with a dark, neon theme

## Getting Started

```bash
git clone https://github.com/<your-username>/ar-vr-viewer-demo.git
cd ar-vr-viewer-demo
```

Then open `index.html` in any modern browser. No server needed.

## How to Use

1. Switch between **VR Mode** and **AR Mode** using the tabs.
2. Use the buttons to add a cube, sphere or star.
3. Click an object in VR to spin it, or click an AR marker to remove it.
4. Press **Clear** to remove everything.

## Tech Stack

- HTML5
- CSS3 (flexbox, keyframe animations, gradients)
- Vanilla JavaScript (DOM manipulation)

## Possible Improvements

- Real AR/VR with **WebXR**, **A-Frame** or **Three.js**
- Drag-and-drop to move objects
- Save and load scenes with `localStorage`
- Sound effects and more object types

## License

MIT
