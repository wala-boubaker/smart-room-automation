#  Smart room Automation 

A smart home automation project built with **ETS 5** (KNX) and **Loxone Config**,
controlling lighting, shutters, and dimmers in a real room environment.

## How It Works
The system allows individual and centralized control of all devices in the room.
A special **Night Mode** can be activated to automatically set the ambiance:
-  Lights → OFF
-  Shutters → CLOSED
-  Dimmer → 30%

##  Features
-  Individual lighting control (ON/OFF)
-  Shutter control (open/close)
-  Dimmer control (adjustable brightness)
-  Night Mode (one-click automation scene)
- Full KNX integration via ETS 5
- Visual programming via Loxone Config

##  Tech Stack
- **ETS 5** — KNX group address configuration
- **Loxone Config** — Logic programming & visualization
- **KNX Protocol** — Building automation standard

[demo video ]
(https://drive.google.com/drive/folders/1jNGu6Ba8GgCuyv-eUbbSvaj3j8sob7z3)

## 📁 Project Structure
smart-home-automation/
├── config/
│   ├── project.loxone        # Loxone configuration file
│   └── project.knxproj       # ETS 5 project file
├── screenshots/              # Project screenshots
├── docs/                     # Documentation / report
└── README.md
