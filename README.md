# Ambient Glow for Twitch, YouTube & Kick ✨

A lightweight Chrome extension that adds a beautiful, cinema-style ambient lighting effect around the video player on your favorite streaming platforms. 

Instead of a harsh border, the colors from the edge of the video bleed into the surrounding webpage, creating a more immersive viewing experience. One single extension and one settings panel controls the effect across **Twitch**, **YouTube**, and **Kick**.

## 🚀 Features

* **Multi-Platform Support:** Works seamlessly across YouTube, Twitch, and Kick.
* **Unified Settings Panel:** Control the glow effect for all sites from a single popup menu.
* **Highly Customizable:** 
  * Adjust Blur, Glow Size (Spread), Opacity, Brightness, and Saturation.
  * Tune the Frame Rate and Smoothing for performance vs. visual quality.
  * Individually toggle the extension on/off per platform.
* **Smart Detection:** Automatically turns off in fullscreen mode or when the video scrolls out of view to save resources.
* **Theater Mode Ready:** Adapts flawlessly to standard and theater viewing modes without clipping the UI.
* **Non-Intrusive:** Hides YouTube's native (and often limited) cinematic lighting so the effects don't overlap, and renders as a blended overlay so site themes aren't interrupted.

## 🛠️ Installation Guide (Manual Install)

Since this extension is not currently hosted on the Chrome Web Store, you can easily install it manually using Chrome's Developer Mode.

1. **Download the Extension:**
   * Click on the green `<> Code` button at the top of this repository and select **Download ZIP**.
   * Extract/unzip the downloaded folder to a location on your computer.

2. **Load into Chrome:**
   * Open your Chromium-based browser (Google Chrome, Brave, Edge, etc.).
   * Type `chrome://extensions/` into your URL bar and press Enter.
   * Turn on **Developer mode** using the toggle switch in the top right corner.
   * Click the **Load unpacked** button that appears in the top left.
   * Select the extracted folder (the one containing the `manifest.json` file).

3. **Enjoy!**
   * The extension is now installed! Open a Twitch, YouTube, or Kick stream.
   * Pin the extension to your toolbar to quickly access the settings popup and tune the glow to your liking.

## ⚠️ Notes & Limitations

* **DRM Content:** Protected or DRM-encrypted videos (like purchased movies on YouTube) block screen sampling for security reasons. The glow effect will not render on these specific videos.
* **Browser Warnings:** Because the extension is loaded in Developer Mode, Chrome might occasionally prompt you to disable extensions running in developer mode. You can safely dismiss this warning.

## 🤝 Contributing

Feel free to open an Issue if you find a bug, or submit a Pull Request if you'd like to add support for another streaming platform!
