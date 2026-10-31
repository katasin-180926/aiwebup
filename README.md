# Our First Anniversary — Android WebAR prototype

## What's included
- Animated 3D gift box, opening lid, floating hearts and anniversary text
- 3D preview for desktop and unsupported mobile browsers
- WebXR immersive AR hit-test for compatible Android devices in Chrome
- Tap to place the box on a detected surface, then tap again or use the open button

## Publish (HTTPS required)
1. Upload `index.html` to a GitHub repository root.
2. In Settings > Pages, select Deploy from a branch, main, /(root).
3. Wait for the Pages URL, then open it in Chrome on an ARCore-compatible Android device.
4. Give camera permission, tap ARで見る, scan a surface and tap to place.

## Important
- This prototype has not been tested on a physical Android device.
- GitHub Pages is public: don't upload private couple photos until choosing a suitable privacy approach.
- The original image and personalized 3D characters are not yet incorporated.
- Three.js is loaded from a CDN, so an internet connection is needed.
- AR depends on Chrome, device support, Google Play Services for AR and HTTPS.

## Customize
Edit the text in the HTML `label(...)` calls and the `start()` message.
