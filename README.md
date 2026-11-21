# NEUROFORM — Advanced Neurology & Physiotherapy Center
### Futuristic, Cinematic 3D Medical Web Experience

A luxury digital platform built for a premium neurological wellness and physical rehabilitation center. Inspired by cutting-edge medical technology interfaces, featuring high-fidelity real-time 3D particle simulations, holographic anatomical diagnostics, and direct clinical scheduling.

---

## Key Features & Visual Architecture

1. **Cinematic Hero Experience with 3D Particle Brain**
   - 4,000+ tiny glowing particles in dual cerebral hemispheres, sulci & gyri fold harmonics, cerebellum, and brain stem.
   - Real-time rotation, organic breathing pulsation, synaptic signal firings, and orbiting satellite particles.
   - Interactive pointer tracking and floating callout telemetry tags directly anchored to neural lobes (Motor Cortex, Neuroplastic circuits, Central highway) matching the design reference.
   - Bold left typography: *"Restore. Reconnect. Move Again."* with supporting clinical badges and telemetry indicators.

2. **Interactive 3D Holographic Human Body & Spine**
   - Glowing anatomical silhouette with glowing magenta/purple vertebrae discs and synovial joint nodes (matching Reference Image 2).
   - 8 interactive clickable/hoverable hotspots: **Brain, Neck, Central Spine, Shoulder, Arms, Lower Back, Knees, Legs**.
   - Live clinical diagnosis drawer with associated symptoms and targeted physiotherapy rehabilitation protocols.

3. **Subtle Neural Ambient Soundscape (Web Audio API)**
   - Synthesizes 108Hz relaxing harmonic frequency and delicate interaction clicks without external audio files. Toggleable directly from the navigation bar.

4. **Complete Clinical Service Matrix**
   - 6 specialized medical cards with 3D tilt effects, clinical indications, protocol checklists, and 1-click appointment pre-selection:
     - Neurology
     - Physiotherapy
     - Stroke Rehabilitation
     - Spine & Nerve Care
     - Pain & Mobility Management
     - Balance & Coordination Therapy

5. **5-Phase Visual Recovery Timeline**
   - 01 Consultation → 02 Assessment → 03 Personalized Plan → 04 Rehabilitation → 05 Progress Review with glowing connecting progress rail.

6. **Medical Leadership Profiles**
   - Detailed, editable profiles for **Dr. Sarah Lin, MD, PhD** (Neurologist) and **Marcus Vance, MPT, OCS** (Physiotherapist) with qualifications, experience, specializations, and booking triggers.

7. **Multi-Channel Appointment System**
   - Interactive form with frontend validation and automatic unique clinical reference code generation.
   - **One-click WhatsApp Appointment Booking**: Automatically formats patient inquiry data into a pre-filled WhatsApp message sent to the clinic desk.

8. **Single Centralized Configuration File**
   - Edit all clinic details, doctors, WhatsApp number, services, hours, and branding in one place:
     - `src/config/clinicData.js`
     - `src/config/clinicData.ts`

---

## How to Run

### Method 1: Instant Local Run (Recommended - Zero Dependencies)
Run the bundled Python launcher:
```powershell
python serve.py
```
Open **`http://localhost:3000`** in any browser.

### Method 2: Direct Browser File
Double-click **`index.html`** or open it directly in Chrome, Edge, Safari, or Firefox.

### Method 3: React / Vite Workflow
If you have Node.js installed on your development machine:
```bash
npm install
npm run dev
```

---

## File Structure

```text
neuroform-clinic/
├── index.html                   # Complete standalone 3D production web experience
├── serve.py                     # Python local server launcher on port 3000
├── package.json                 # React, Three.js, R3F, Framer Motion dependencies
├── tsconfig.json                # TypeScript configuration
├── vite.config.ts               # Vite configuration
├── tailwind.config.js           # Tailwind dark luxury theme
├── README.md                    # Project documentation
└── src/
    ├── App.tsx                  # Modular React application
    ├── main.tsx                 # React DOM root
    ├── index.css                # Global styles
    ├── components/
    │   └── BrainCanvas.tsx      # React Three Fiber 3D particle brain component
    └── config/
        ├── clinicData.js        # Centralized editable clinic configuration
        └── clinicData.ts        # TypeScript interfaces and clinic definitions
```
