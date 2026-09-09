# DOSE-ZERO: WebXR Drug Awareness VR Prototype

> **"Experience the consequences. Never the substance."**

A standalone, single-file WebXR educational virtual reality prototype built with **A-Frame 1.6.0**, optimized for the **Meta Quest 3S** and fully playable via desktop fallback.

---

## Quick Start

### Run Locally
Serve the project directory using Python:
```bash
python -m http.server 8080
```
Then navigate to `http://localhost:8080/index.html` in your browser.

### Open on Meta Quest 3S
WebXR requires a secure context (`HTTPS` or `localhost`). To test on a Quest 3S:
1. Use a tunnel like `ngrok` or local SSL:
   ```bash
   npx ngrok http 8080
   ```
2. Open the resulting HTTPS URL inside the **Meta Quest Browser**.
3. Click **ENTER VR** on the top bar or 3D Welcome board.
4. Interact using your Quest 3S touch controllers (point laser ray & pull trigger).

---

## Controls Reference

### Meta Quest 3S Controllers
- **Left / Right Controller**: Laser pointer targeting interactive elements (`.clickable`)
- **Index Trigger**: Select / Click / Confirm choice
- **Thumbsticks**: Comfort snap turning & slow exploration
- **Wrist / Top Bar**: Access the VR Comfort Menu

### Desktop Fallback
- **W / A / S / D**: Move forward, left, backward, right
- **Mouse Click & Drag**: Look around 360°
- **Left Click**: Select 3D objects or HUD interactive cards

---

## Key Features

1. **Complete 13-Stage Educational User Journey**:
   - Welcome Pavilion -> Safety Disclaimer -> Scenario Selection -> Campus Courtyard (Peer Pressure) -> Substance Decision -> Simulated Impairment -> Cognitive Challenge -> Decision Making -> Consequence Corridor -> Reality Check -> 5-Question Quiz -> Awareness Score -> Final Call to Action.
2. **Procedural Web Audio Engine**: Zero external asset dependencies; generative ambient chords, muffled lowpass impairment filter, and UI SFX generated in real time.
3. **Controlled Perceptual Impairment**: Safe demonstration of visual tunnel vision, subtle environmental sway, and latency without seizure triggers, gore, or flashing.
4. **VR Comfort & Accessibility**: In-VR Comfort menu with Comfort Mode, Reduced Visual Effects toggle, Audio toggle, Closed Captions, and Skip Simulation.