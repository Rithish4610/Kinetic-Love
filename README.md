# 🫶 Kinetic Love: AI-Powered Hand Particle System

A real-time, interactive 3D particle system that reacts to your hand gestures in the browser. Built with **Three.js** and **MediaPipe**, this project blends computer vision with generative art to create a magical experience.

🔗 **[Live Demo](https://rithish4610.github.io/Kinetic-Love/love.html)** *(Click to try it!)*

## ✨ Features

* **Real-time Hand Tracking:** Uses MediaPipe Hands to track fingers and wrists with high precision.
* **3D Particle Morphing:** 3,000 particles seamlessly flow between mathematical shapes based on your movements.
* **Gesture Recognition:**
    * 🖐 **Open Hand:** Triggers an "Explosion" effect, scattering particles in gold.
    * 🫰 **Pinch (Index + Thumb):** Morphs particles into a spinning 3D Heart (Red/Pink).
    * 🫶 **Two Hands Together:** Detects the "Heart Gesture" (wrists close together) and floats a glowing "I LOVE YOU" message.
* **No Install Required:** Runs entirely in the browser using standard web technologies.

## 🎮 Controls

| Gesture | Action | Visual Effect |
| :--- | :--- | :--- |
| **Idle** | Relax hand | Floating Blue/Purple Sphere |
| **Move Hand** | Move around | Particles follow your hand position |
| **Open Hand** | Splay fingers | Particles expand/explode (Gold) |
| **Pinch** | Index + Thumb | Forms a 3D Heart (Red) |
| **Heart** | Two wrists close | Displays "I LOVE YOU" text |

## 🛠️ Tech Stack

* **Three.js:** For high-performance 3D rendering and particle shaders.
* **MediaPipe Hands:** For machine-learning-based hand tracking directly in the browser.
* **HTML5/CSS3:** For UI overlays and animations.

## 🚀 How to Run Locally

1.  **Clone the repository**
    ```bash
    git clone [https://github.com/Rithish4610/Kinetic-Love.git](https://github.com/Rithish4610/Kinetic-Love.git)
    ```
2.  **Open the folder**
    ```bash
    cd Kinetic-Love
    ```
3.  **Run a local server** (Required for camera access)
    * If using **VS Code**: Install the "Live Server" extension and click "Go Live".
    * If using **Python**:
        ```bash
        python -m http.server
        ```
4.  **Open in Browser**
    * Go to `http://localhost:8000/love.html`
    * **Allow Camera Access** when prompted.

## 🤝 Contributing

Feel free to fork this project and add your own shapes or gestures!

1.  Fork the Project
2.  Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3.  Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4.  Push to the Branch (`git push origin feature/AmazingFeature`)
5.  Open a Pull Request

---
*Created with ❤️ by [Rithish4610](https://github.com/Rithish4610)*
