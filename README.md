# 3D-Gesture-Experience

**Christmas Magic: Camera Control**  
A festive and interactive 3D experience leveraging hand gestures and live camera input!  
Control dazzling holiday-themed shapes and objects using your mouse or hand gestures with seamless transitions, brought to life via [Three.js](https://threejs.org/) and [MediaPipe Hands](https://google.github.io/mediapipe/solutions/hands.html).

---

## Features

- **Real-Time Hand Gesture Recognition:** Switch between various 3D scenes using gestures  
  - ✊ Fist → Christmas Tree (树)
  - ✌️ Peace → DNA Double Helix (DNA双螺旋)
  - ☝️ One Finger → Galaxy (银河)
  - 🖐️ Open Hand → Sphere/Photos (星球/照片)
- **Mouse or Gesture Control:** Switch between classic mouse controls and futuristic hand tracking.
- **Photo Upload:** Seamlessly upload your own photos to be displayed as floating holograms within the 3D canvas.
- **Festive Particle & Light FX:** Enjoy bloom and color effects with animated particles.
- **Camera Toggle:** Turn hand tracking on/off for privacy and performance.

---

## How To Run

1. **Clone the repository**

    ```bash
    git clone https://github.com/limjiajun/3D-Gesture-Experience.git
    cd 3D-Gesture-Experience
    ```

2. **Open `index.html` in your browser**  
   _No build step required! All dependencies are loaded via CDN._

3. **Grant Camera Access**  
   On first load, the app will request permissions for your webcam.

---

## Usage

- Use the control panel on the left to switch modes, morph shapes, and upload photos.
- Gesture controls:
  - Make gestures in front of your webcam according to the legend in the UI.
- Mouse controls:
  - Orbit, zoom, and pan using the mouse when "鼠标" mode is active.

---

## Tech Stack

- **Three.js** for 3D rendering  
- **MediaPipe Hands** for gesture recognition  
- **GSAP** for smooth scene transitions  
- **HTML/CSS** for UI components  
- **Vanilla JavaScript / ES Modules**

---

## License

[MIT License](LICENSE)

---

## Credits

- Designed and developed by LIM JIA JUN  
- Powered by open-source libraries
