# 🌍 Civic Sense WebXR - Waste Segregation Challenge

An interactive, educational, and humorously dramatic **WebXR (VR/AR/Desktop)** experience built with **A-Frame**. 
Learn waste segregation by sorting items into color-coded bins. Getting it right awards you Eco Points and increases your Civic Sense streak. Putting waste into the wrong bin summons the angry **Civic Sense Enforcer NPC**, who punches you straight into outer space!

---

## 🎮 Features

- 🕶️ **Full WebXR Compatibility**: Tested for Meta Quest (1, 2, 3, Pro), Apple Vision Pro, PC VR, Desktop (Mouse + WASD), and Mobile.
- 🟢 **Standard Color-Coded Segregation Bins**:
  - 🟢 **Green Bin**: Organic / Wet / Food Scraps (Apple Core, Banana Peel)
  - 🔵 **Blue Bin**: Paper & Cardboard (Newspapers, Delivery Box)
  - 🟡 **Yellow Bin**: Plastics & Wrappers (Plastic Bottles, Plastic Bags)
  - 🔴 **Red Bin**: Hazardous, Glass, E-Waste & Metal (Glass Bottles, Batteries, Aluminum Cans)
- 🥊 **Hilarious NPC Punishment Sequence**:
  - Comedic fail sound (`Faaaa...`)
  - Cybernetic Civic Enforcer rushes the player and delivers a punch
  - Player gets launched into orbit viewing Earth from space with a blood vignette
  - Educational dialogue explaining the mistake and giving real-world civic sense tips
- 🎵 **Built-in Web Audio API Sound Synthesizer**: No broken MP3 links; 100% offline-ready dynamic chimes, buzzers, punch thuds, and speech synthesis!

---

## 🕹️ Controls

### 🖥️ Desktop / Laptop
- **Look Around**: Click and drag with mouse.
- **Move**: `W`, `A`, `S`, `D` keys.
- **Pick Up Waste**: Click directly on any waste item on the sorting table.
- **Drop Waste into Bin**: Click on the matching colored bin.
- **VR Mode**: Click the VR goggles icon at the bottom-right of the screen.

### 🥽 Meta Quest (VR Headset)
- **Laser Pointer**: Aim your controller at items/bins.
- **Pick / Drop**: Press the **Index Trigger** or **Grip** button.
- **Space Return**: Point at the `RETURN TO EARTH` button and trigger.

---

## 🚀 How to Deploy to GitHub & GitHub Pages

Since this project uses pure HTML and WebXR with CDN scripts, you can deploy it for free in 1 minute using GitHub Pages:

### Step 1: Initialize Git and Push to GitHub
Open your terminal in this project folder (`d:\GA`) and run:

```bash
git init
git add .
git commit -m "Initial commit: Civic Sense WebXR game"
git branch -M main
```

Create a new public repository on [GitHub](https://github.com/new) (e.g. `civic-sense-vr`), then link and push:
```bash
git remote add origin https://github.com/<your-username>/<your-repo-name>.git
git push -u origin main
```

### Step 2: Enable GitHub Pages
1. Go to your repository on GitHub.
2. Click **Settings** (tab at the top).
3. In the left sidebar, click **Pages**.
4. Under **Build and deployment > Source**, select **Deploy from a branch**.
5. Under **Branch**, select `main` and `/ (root)`, then click **Save**.
6. Wait 1–2 minutes. Your live WebXR URL will appear at:
   `https://<your-username>.github.io/<your-repo-name>/`

---

## 🥽 How to Test on Meta Quest

1. Put on your **Meta Quest** headset.
2. Open the built-in **Meta Quest Browser**.
3. Type in your GitHub Pages URL (e.g. `https://<your-username>.github.io/<your-repo-name>/`).
4. Once the page loads, click the **VR Button** (goggles icon) in the bottom-right corner.
5. You are now inside the 3D Eco Plaza in full immersive 6DOF VR! Aim with your laser controllers to start sorting.
