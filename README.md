# ClearDose

<img src="./frontend/public/Logo_Animation.gif" alt="Header image" width="100%" height="auto">

Keeping a pool balanced shouldn't require juggling scattered notes, looking up thermodynamic formulas on your phone, and cross-referencing chemical warning labels while your hands are wet. 

ClearDose was built out of the frustration of manual pool maintenance. It replaces guesswork and fragmented notes with a single, precision instrument. You input your pool's current physical condition and test strip results, and the engine outputs the exact chemical math, safety warnings, and step-by-step dosing instructions required to restore equilibrium.

## How It Works

Instead of just telling you a number is "low" or "high," ClearDose looks at the water as an interconnected system. 

1. **Input Conditions:** Select visual and physical attributes describing the pool's current state (e.g., cloudy water, algae blooms, temperature).
2. **Log Test Results:** Enter your raw data from standard test strips or drop kits (pH, Total Alkalinity, Free Chlorine, Cyanuric Acid, Calcium Hardness).
3. **Get the Diagnosis:** The engine calculates the Langelier Saturation Index (LSI) and identifies whether the water is corrosive, scale-forming, or balanced.
4. **Follow the Steps:** Receive a deterministic, sequenced action plan. 

## Core Features

* **Real-Time Dosing Math:** Calculates exact gram and milliliter measurements based on your specific pool volume and selected chemicals (standardized to HTH product specs).
* **Unified Context:** Displays the necessary formulas, historical notes, and chemical wait-times exactly when you need them, eliminating the need to check external references.
* **Safety & Order of Operations:** Automatically sequences instructions to prevent dangerous chemical interactions (e.g., hard-locking acid and liquid chlorine from being added in the same step) and flags exothermic reactions.
* **Offline-First:** Built as a Progressive Web App (PWA) that loads instantly poolside, even with zero cell signal.

## Getting Started

### Prerequisites
* Node.js (v18+)
* npm or pnpm

### Installation

1. Clone the repository:
   ```bash
   git clone [https://github.com/yourusername/cleardose.git](https://github.com/bvltra/cleardose.git)
