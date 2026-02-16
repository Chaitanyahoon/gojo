# SAT0RU: Jujutsu Kaisen Cursed Technique Visualizer

SAT0RU is a web-based Augmented Reality (AR) application that brings the powerful **Cursed Techniques** from the anime *Jujutsu Kaisen* to life using your webcam.

Powered by **MediaPipe** for hand tracking and **Three.js** for high-performance 3D particle rendering, this project lets you wield the power of Satoru Gojo and Ryomen Sukuna in real-time.

![Demo GIF](https://github.com/user-attachments/assets/8ad2b871-02c0-4b97-95f3-34682e745be0)

## 🔥 Features

*   **Real-time Hand Tracking**: Instantly recognizes hand gestures to trigger different techniques.
*   **Volumetric Particle Systems**: Techniques are rendered as 3D particle fields with depth and motion.
*   **Dynamic Animations**:
    *   **Hollow Purple**: A chaotic singularity of attraction (Blue) and repulsion (Red).
    *   **Cleave (Dismantle)**: A stabilized, rhythmic "Dicing Net" that cuts through 3D space.
    *   **Infinite Void**: A mesmerizing celestial domain expansion.
*   **Post-Processing Effects**: Unreal Bloom and Film Grain filters for a cinematic anime look.

## 🖐️ Technique Guide & Gestures

Use these hand signs to activate the techniques:

| Technique | Trigger Gesture | Visual Effect |
| :--- | :--- | :--- |
| **Neutral Limitless** | **Default** (No gesture) | Gentle blue energy flow around your hands. |
| **Cursed Technique Lapse: Blue** | **Fist** ✊ | A dense, spiraling core of blue attractive force. |
| **Cursed Technique Reversal: Red** | **Index Pointing Up** ☝️ | A violent, jagged sphere of repulsive red energy. |
| **Hollow Purple** | **Pinch** 👌 (Thumb + Index) | A chaotic, purple singularity erasing everything in its path. |
| **Dismantle / Cleave** | **Peace Sign** ✌️ | A **"Dicing Net"** of invisible red slashes that pulse Rhythmically to dice the target. |
| **Malevolent Shrine** | **Open Palm** ✋ | A dark, ominous aura representing the King of Curses. |
| **Infinite Void** | **Crossed Fingers** 🤞 (Index + Middle) | A celestial domain of infinite information with a bright event horizon. |

## 🚀 Getting Started

### Prerequisites
*   A modern web browser (Chrome, Edge, Firefox).
*   A webcam.

### Installation

1.  **Clone the repository**
    ```bash
    git clone https://github.com/Chaitanyahoon/gojo.git
    cd gojo
    ```

2.  **Run the project**
    This project uses ES6 modules, so it must be run on a local server (opening `index.html` directly won't work due to CORS).

    *   **VS Code (Recommended):** Install the "Live Server" extension, right-click `index.html`, and select "Open with Live Server".
    *   **Python:**
        ```bash
        # Python 3
        python -m http.server
        ```
    *   **Node.js:**
        ```bash
        npx http-server
        ```

3.  **Allow Camera Access**: When prompted, allow the browser to access your webcam.

## 🚀 Deployment (Vercel)

Click the button below to deploy this project instantly on Vercel:

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/Chaitanyahoon/gojo)

Or deploy manually:
1.  Push your code to GitHub.
2.  Go to [Vercel](https://vercel.com) and import your repo.
3.  Vercel will detect the static site automatically (no build command needed).

## 🛠️ Tech Stack

*   **Three.js**: 3D Rendering & Particle Systems.
*   **MediaPipe Hands**: Machine Learning Hand Tracking.
*   **Post-Processing**: Unreal Bloom Pass (Glowing effects).

---
*Built with Cursed Energy and Code.*
