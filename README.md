<div align="center">

# A.U.R.A.

### Autonomous Universal Resonant Assistant

<img src="./assets/hero.svg" alt="Animated project header" />

<p><a href="./README.md"><strong>English</strong></a> · <a href="./README.de.md">Deutsch</a> · <a href="./README.tr.md">Türkçe</a></p>

<p>
  <a href="https://github.com/tahakubilay"><img src="https://img.shields.io/badge/Taha%20Kubilay-GitHub-181717?style=for-the-badge&logo=github" alt="Taha Kubilay on GitHub" /></a>
  <a href="https://github.com/tahakubilay/Aura"><img src="https://img.shields.io/badge/Repository-A.U.R.A.-0A66C2?style=for-the-badge&logo=github" alt="Repository" /></a>
  <img src="https://img.shields.io/badge/Physical%20AI-Experimental%20Prototype-7C3AED?style=for-the-badge" alt="Experimental physical AI prototype" />
</p>

</div>

---

## Overview

A.U.R.A. — **Autonomous Universal Resonant Assistant** — is an experimental physical AI assistant designed to give conversational intelligence a visible, spatial and expressive presence.

The concept combines embedded systems, directional audio sensing, magnetic levitation, wireless power, motion control and an expressive circular interface inside a compact transparent spherical form.

## Physical Concept

- Approximately 12 cm transparent spherical core
- Magnetic levitation above a dedicated base
- Contactless wireless power transfer
- Multi-microphone directional audio sensing
- 360° orientation toward the active speaker
- Circular display for expressive eye animations
- AI interaction layer connected to physical motion and visual feedback

## Interaction Flow

```mermaid
flowchart LR
    USER[Speaker] --> MIC[Microphone Array]
    MIC --> DOA[Direction / TDOA Estimation]
    DOA --> MOTION[Orientation Control]
    USER --> AI[AI Interaction Layer]
    AI --> DISPLAY[Expressive Circular Display]
    BASE[Magnetic Base] --> LEV[Levitation]
    BASE --> WPT[Wireless Power]
    WPT --> CORE[A.U.R.A. Core]
    CORE --> MIC
    CORE --> DISPLAY
    CORE --> MOTION
```

## Directional Audio

A.U.R.A. uses a multi-microphone concept to estimate where a voice originates around the device. Relative arrival-time differences between microphones can be used to estimate the speaker direction and drive physical orientation.

```mermaid
flowchart TD
    S[Speech] --> M1[Microphone 1]
    S --> M2[Microphone 2]
    S --> M3[Microphone 3]
    S --> M4[Microphone 4]
    M1 --> T[TDOA / Direction Estimation]
    M2 --> T
    M3 --> T
    M4 --> T
    T --> A[Estimated 0°–360° Direction]
    A --> R[Orient Toward Speaker]
```

## Core Systems

| System | Role |
|---|---|
| **Magnetic Levitation** | Suspend the spherical core without visible mechanical support |
| **Wireless Power** | Deliver energy from the base without a physical cable to the sphere |
| **Microphone Array** | Capture directional audio around the device |
| **Direction Estimation** | Estimate speaker angle using timing differences |
| **Orientation Control** | Rotate the assistant toward the active speaker |
| **Expressive Display** | Communicate attention and system state through animated eyes |
| **AI Layer** | Connect conversational intelligence to physical interaction |

## Engineering Focus

A.U.R.A. combines software and hardware concerns that are usually developed separately:

- Embedded systems
- Audio signal processing
- Human-computer interaction
- Sensor fusion
- Motion control
- Wireless power
- Physical prototyping
- AI integration
- Real-time state coordination
- Product-oriented industrial design

## Project Nature

A.U.R.A. is an experimental prototype concept. The repository presents the system architecture and interaction design without representing the hardware as a finished commercial product.

---

<div align="center">

### Built by [Taha Kubilay](https://github.com/tahakubilay)

`Physical AI` · `Embedded Systems` · `IoT` · `Audio Processing` · `Human-Computer Interaction`

</div>