# DOSE-ZERO
Yep. Here’s a **GitHub-ready README** for the project, written to make it look like a serious WebXR project rather than just a college prototype.

# 🥽 Drug Awareness VR

### *Experience the consequences. Never the substance.*

An immersive **WebXR-based drug awareness simulation** designed to educate users about the potential consequences of impaired perception and decision-making through a safe, interactive virtual experience.

> **No real drugs or substances are used, provided, demonstrated, or instructed.**
> The experience uses a completely fictional substance and simulated effects for educational purposes.

---

## 🚀 Overview

Traditional drug-awareness programs often rely on posters, presentations, and videos.

**Drug Awareness VR** takes a different approach.

Instead of simply telling users about the risks, the experience places them inside a fictional scenario where they can:

* Experience simulated changes in perception
* Make decisions under simulated impairment
* Observe the consequences of those decisions
* Learn about potential risks
* Test their understanding through an awareness quiz

The entire experience is delivered through the browser using **WebXR**, allowing compatible VR headset users to access it through a URL without installing an application.

---

## 🎯 Objective

The project aims to help users understand:

* How impaired perception can affect everyday tasks
* How impaired judgement can influence decisions
* How peer pressure can affect behaviour
* Potential short-term and long-term consequences
* Safer ways to respond to risky situations
* The importance of seeking appropriate help

The objective is **education and prevention**, not recreation or experimentation.

---

# 🧠 Experience Flow

```text
        WELCOME
           │
           ▼
      DISCLAIMER
           │
           ▼
   SCENARIO SELECTION
           │
           ▼
    PEER PRESSURE
           │
           ▼
    SUBSTANCE X
       DECISION
           │
           ▼
   SIMULATED EFFECTS
           │
           ▼
 COGNITIVE CHALLENGE
           │
           ▼
   DECISION MAKING
           │
           ▼
     CONSEQUENCES
           │
           ▼
     REALITY CHECK
           │
           ▼
   AWARENESS QUIZ
           │
           ▼
      FINAL RESULT
```

---

# 🥽 Key Features

### 🌐 Web-Based VR

Runs directly through a compatible WebXR browser.

**No APK installation required.**

### 🎮 VR Interaction

Supports:

* VR controllers
* Ray-based interaction
* Hand tracking where available
* Gaze-based interaction where practical

### 🌀 Simulated Effects

The simulation can demonstrate:

* Reduced visual clarity
* Mild distortion
* Difficulty focusing
* Simulated reaction challenges
* Audio distortion
* Decision-making difficulties

These effects are intentionally controlled and are **not intended to medically reproduce intoxication**.

### 🌳 Branching Decisions

Users make choices that affect the simulated outcome.

The experience demonstrates:

```text
Impairment
    ↓
Decision
    ↓
Risk
    ↓
Potential Consequence
```

### 🧠 Cognitive Challenge

Users complete a simple interactive task during the simulation.

The result is presented as a **simulation score**, not a medical or psychological assessment.

### 🚨 Reality Check

After the simulation, the experience explicitly explains that everything was simulated and provides educational information about potential risks.

### 📝 Awareness Quiz

A short quiz tests the user's understanding of:

* Impaired judgement
* Peer pressure
* Risk awareness
* Safer decision-making
* Seeking help

### 💻 Desktop Fallback

If WebXR is unavailable, users can experience the educational journey through a normal desktop browser.

---

# 🛠️ Tech Stack

| Technology              | Purpose                         |
| ----------------------- | ------------------------------- |
| React                   | UI and application architecture |
| TypeScript / JavaScript | Application logic               |
| Three.js                | 3D rendering                    |
| React Three Fiber       | React-based 3D development      |
| WebXR                   | VR functionality                |
| Vite                    | Development and build tooling   |
| GLTF / GLB              | 3D assets                       |
| Web Audio API           | Audio effects                   |
| Vercel / Netlify        | Deployment                      |

---

# 📁 Project Structure

```text
drug-awareness-vr/
│
├── public/
│   ├── models/
│   ├── textures/
│   ├── audio/
│   └── environments/
│
├── src/
│   ├── components/
│   │   ├── VRButton/
│   │   ├── StartScreen/
│   │   ├── ScenarioSelector/
│   │   ├── ChoicePanel/
│   │   └── RealityCheck/
│   │
│   ├── scenes/
│   │   ├── WelcomeScene/
│   │   ├── DisclaimerScene/
│   │   ├── ScenarioScene/
│   │   ├── SimulationScene/
│   │   ├── ConsequenceScene/
│   │   └── QuizScene/
│   │
│   ├── effects/
│   │   ├── VisionEffects/
│   │   └── AudioEffects/
│   │
│   ├── interactions/
│   │   ├── ControllerInteraction/
│   │   ├── HandInteraction/
│   │   └── GazeInteraction/
│   │
│   ├── data/
│   │   └── scenarios/
│   │
│   ├── utils/
│   │
│   ├── App.tsx
│   └── main.tsx
│
├── package.json
├── vite.config.ts
├── tsconfig.json
└── README.md
```

---

# ⚙️ Getting Started

## Prerequisites

Install:

* Node.js
* npm
* A WebXR-compatible browser for VR testing
* A compatible VR headset for immersive testing

Check your Node installation:

```bash
node --version
npm --version
```

---

## 📦 Installation

Clone the repository:

```bash
git clone <repository-url>
```

Move into the project:

```bash
cd drug-awareness-vr
```

Install dependencies:

```bash
npm install
```

---

# ▶️ Run Locally

Start the development server:

```bash
npm run dev
```

The application will be available through the local development URL shown by Vite.

For desktop testing, open the URL in your browser.

For VR testing, the development environment must be accessible to the VR headset and served through an appropriate secure connection.

---

# 🏗️ Production Build

Create a production build:

```bash
npm run build
```

Preview the production build locally:

```bash
npm run preview
```

---

# 🌐 Deployment

The application is designed to be deployed as an HTTPS website.

Recommended platforms:

* Vercel
* Netlify

Typical deployment flow:

```text
GitHub Repository
       ↓
Connect to Vercel / Netlify
       ↓
Build
       ↓
Deploy
       ↓
HTTPS URL
       ↓
Open URL in VR Browser
       ↓
Enter VR
```

Example final URL:

```text
https://drug-awareness-vr.vercel.app
```

---

# 🥽 Using the Experience in VR

On a compatible VR headset:

1. Put on the headset.
2. Open a compatible WebXR browser.
3. Navigate to the deployed HTTPS URL.
4. Wait for the experience to load.
5. Select **ENTER VR**.
6. Allow required browser permissions.
7. Begin the simulation.

No application installation should be required.

---

# 🔐 Safety & Ethics

This project is strictly designed for **awareness and education**.

### The project does NOT:

* Use real drugs
* Provide real substances
* Explain how to obtain drugs
* Explain how to prepare drugs
* Provide dosage information
* Encourage drug consumption
* Promote recreational drug use
* Collect sensitive personal information

The fictional **Substance X** exists only as a narrative device.

All simulated effects are simplified representations intended to communicate concepts such as impaired perception and decision-making.

---

# ♿ Accessibility & Comfort

The experience is designed with VR comfort in mind.

Features include:

* Reduced-effects mode
* Audio controls
* Captions/subtitles
* Skip simulation option
* Exit functionality
* No forced camera movement
* No required artificial locomotion
* Avoidance of intense flashing effects
* Desktop fallback

Users should remain in control throughout the experience.

---

# 🔒 Privacy

The application does not require an account.

The project should not collect:

* Names
* Email addresses
* Phone numbers
* Health information
* Sensitive personal information

If anonymous analytics are introduced in future versions, they should be optional and privacy-conscious.

---

# 🧪 Testing

Test the application in:

### Desktop

* Chrome
* Edge

### VR

Test using compatible WebXR hardware and browsers.

Verify:

* VR session initialization
* Controller interaction
* Hand tracking
* Scene transitions
* Audio
* Visual effects
* Quiz scoring
* Exit functionality
* Desktop fallback
* Asset loading
* Production deployment

---

# 📊 Success Metrics

The project can be evaluated using:

### Technical

* Successful WebXR session launch
* Stable VR performance
* Successful deployment
* Functional desktop fallback
* No major runtime errors

### Educational

* Simulation completion rate
* Quiz comprehension
* Understanding of peer-pressure responses
* Understanding of potential consequences

### User Experience

* Ease of VR interaction
* Immersion
* Comfort
* Clarity of educational messaging

---

# 🗺️ Roadmap

## Phase 1 • MVP

* [x] Project architecture
* [ ] Welcome scene
* [ ] Safety disclaimer
* [ ] Peer-pressure scenario
* [ ] Substance X decision
* [ ] Simulated effects
* [ ] Cognitive challenge
* [ ] Consequence sequence
* [ ] Reality Check
* [ ] Awareness quiz
* [ ] Desktop fallback
* [ ] WebXR integration
* [ ] Production deployment

## Phase 2 • Expansion

* [ ] Curiosity scenario
* [ ] Stress scenario
* [ ] Social situation scenario
* [ ] Improved environments
* [ ] More branching decisions
* [ ] Voice narration
* [ ] Advanced hand tracking

## Phase 3 • Advanced

* [ ] AI-powered NPC conversations
* [ ] Multi-language support
* [ ] Anonymous educator analytics
* [ ] Institutional/classroom mode
* [ ] More accessibility features

---

# 💡 Future Vision

The long-term goal is to create a platform where awareness education is **interactive rather than passive**.

Future scenarios could allow users to explore different social situations and understand how small decisions can lead to very different outcomes.

The platform could eventually support schools, colleges, awareness campaigns, exhibitions, and educational organizations.

---

# 🤝 Contributing

Contributions are welcome.

Before submitting a contribution:

1. Keep the experience educational.
2. Preserve the project's safety principles.
3. Avoid adding real-world drug-use instructions.
4. Maintain VR performance.
5. Test both desktop and VR interactions where possible.

---

# 📜 License

Add the project's chosen license here.

Example:

```text
MIT License
```

---

# 👥 Team

**Project:** Drug Awareness VR

**Purpose:** Immersive Drug Awareness & Prevention Education

Built using **WebXR + Three.js + React**.

---

## ⭐ Final Message

> **You don't need to experience the substance to understand the consequences.**

**Drug Awareness VR** turns awareness into an experience, while keeping the experience itself safe.
