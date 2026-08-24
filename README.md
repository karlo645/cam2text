# Cam2Text

Turn your webcam feed into live, real-time ASCII art directly inside your browser.

## About the Project

**Cam2Text** is a lightweight, client-side web application that captures your webcam stream, processes each video frame into grayscale ASCII characters, and renders it in real-time as styled terminal text. Everything runs locally in your browser—no data ever leaves your device.

## Features

* **Real-Time ASCII Conversion:** Stream live video translated into ASCII matrices instantly.
* **Customizable Palettes:** Choose from Matrix Green, Cyber Amber, and Neon Cyan.
* **Adjustable Detail/Resolution:** Switch between Standard (80 cols), High (120 cols), and Ultra (160 cols).
* **Snapshot Capture:** Pause and capture frames to preview or download as text files.
* **CRT Scanline Effects:** Styled with a retro terminal look and responsive design.

## Known Issues and Troubleshooting

### Camera Permission Error / "No Permission" Bug

Sometimes, even after you grant camera permissions, browsers or underlying drivers can occasionally fail to bind the stream instantly, showing a permission or access error.

**How to fix it:**

1. **Try Again:** Simply click "Initialize Camera" (or toggle it off and back on) to retry the request. In most cases, the second attempt connects successfully.
2. **Check Other Apps:** Ensure no other application (like Zoom, Teams, or another browser tab) is currently locking your webcam.
3. **Report an Issue:** If you have tried multiple times, double-checked your browser permissions, and made sure no other app is using your camera, please open an issue on the GitHub repository with your browser version and operating system details.

## Credits and License

* Built with Tailwind CSS and Font Awesome
* Inspired by classic terminal aesthetics and retro computing
* Open-source and available under the MIT License