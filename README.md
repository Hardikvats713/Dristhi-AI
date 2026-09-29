<div align="center">

# DRISHTI AI

### Intelligent Video Analytics Platform for Border Surveillance

**Smart India Hackathon 2026 · SIH26187**

<p>
  <img src="https://img.shields.io/badge/SIH-2026-0A66C2?style=for-the-badge">
  <img src="https://img.shields.io/badge/Problem%20Statement-SIH26187-111827?style=for-the-badge">
  <img src="https://img.shields.io/badge/Theme-Blockchain%20%26%20Cybersecurity-7C3AED?style=for-the-badge">
  <img src="https://img.shields.io/badge/Category-Software-059669?style=for-the-badge">
</p>

**Team Sudo -l · Team ID: T57**

*Turning existing CCTV infrastructure into an intelligent, context-aware and auditable surveillance layer.*

</div>

---

## Overview

**Drishti AI** is an AI-powered video analytics platform designed for intelligent surveillance using **existing IP-CCTV infrastructure**.

Instead of replacing deployed cameras, Drishti adds an intelligence layer that processes video streams, detects relevant objects, tracks movement, understands event context, prioritizes security events and preserves evidence with cryptographic integrity.

### Core Pipeline

```text
CAMERA
   ↓
VIDEO INGESTION
   ↓
AI PERCEPTION
   ↓
TRACKING
   ↓
CONTEXT ANALYSIS
   ↓
EVENT PRIORITY
   ↓
HUMAN VERIFICATION
   ↓
SECURE EVIDENCE
   ↓
SHA-256 + BLOCKCHAIN ANCHOR
```

> **Detect → Track → Understand → Alert → Verify → Preserve**

---

# Problem Statement

Traditional CCTV systems primarily operate as **passive recording infrastructure**.

Large surveillance networks generate continuous video streams, but human operators cannot continuously analyze every feed. This creates challenges such as:

- Manual monitoring dependency
- Missed or delayed detection
- Alert overload
- Isolated camera views
- Difficulty tracking movement across cameras
- Limited contextual understanding of events
- Evidence integrity concerns

Drishti AI addresses these limitations by adding a **software-defined intelligence layer** to existing IP-CCTV infrastructure.

---

# Our Solution

Drishti AI converts raw camera streams into **context-aware security events**.

### From

```text
Camera → Recording → Manual Investigation
```

### To

```text
Camera
   ↓
AI Analysis
   ↓
Tracking
   ↓
Context
   ↓
Risk / Priority
   ↓
Human Verification
   ↓
Auditable Evidence
```

The platform is designed around five major capabilities:

| Capability | Purpose |
|---|---|
| **AI Perception** | Detect and classify relevant objects/events |
| **Cross-Camera Tracking** | Correlate movement across cameras |
| **Context Engine** | Understand object + location + time + movement |
| **Human Verification** | Keep operators in the decision loop |
| **Secure Evidence** | Maintain cryptographically verifiable records |

---

# System Architecture

<div align="center">

<img src="assets/drishti-technical-architecture.png" width="100%">

</div>

### Seven-Layer Architecture

```text
┌────────────────────────────────────────────┐
│ 01  CAMERA INFRASTRUCTURE                 │
│     Existing IP-CCTV · RTSP · ONVIF       │
└──────────────────────┬─────────────────────┘
                       ↓
┌────────────────────────────────────────────┐
│ 02  VIDEO INGESTION & PREPROCESSING       │
│     Stream Processing · Enhancement       │
└──────────────────────┬─────────────────────┘
                       ↓
┌────────────────────────────────────────────┐
│ 03  AI PERCEPTION ENGINE                  │
│     Detection · OCR · Event Analysis      │
└──────────────────────┬─────────────────────┘
                       ↓
┌────────────────────────────────────────────┐
│ 04  TRACKING & BEHAVIOUR ANALYSIS         │
│     Multi-Object Tracking · Trajectory    │
└──────────────────────┬─────────────────────┘
                       ↓
┌────────────────────────────────────────────┐
│ 05  CONTEXT & EVENT ENGINE                │
│     Rules · Correlation · Priority        │
└──────────────────────┬─────────────────────┘
                       ↓
┌────────────────────────────────────────────┐
│ 06  OPERATOR ACTION LAYER                 │
│     Alerts · Dashboard · Verification     │
└──────────────────────┬─────────────────────┘
                       ↓
┌────────────────────────────────────────────┐
│ 07  SECURITY & EVIDENCE LAYER             │
│     RBAC · SHA-256 · Blockchain           │
└────────────────────────────────────────────┘
```

---

# Technology Stack

<div align="center">

### AI / Computer Vision

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![YOLO](https://img.shields.io/badge/YOLOv8-111827?style=flat-square)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)

### Tracking / Analytics

![DeepSORT](https://img.shields.io/badge/DeepSORT-Tracking-6366F1?style=flat-square)
![OCR](https://img.shields.io/badge/OCR%20%2F%20ANPR-Analysis-0891B2?style=flat-square)
![Computer Vision](https://img.shields.io/badge/Computer%20Vision-Analysis-7C3AED?style=flat-square)

### Backend / Infrastructure

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)

### Camera / Security

![RTSP](https://img.shields.io/badge/RTSP-Video%20Streaming-374151?style=flat-square)
![ONVIF](https://img.shields.io/badge/ONVIF-Camera%20Integration-2563EB?style=flat-square)
![SHA-256](https://img.shields.io/badge/SHA--256-Integrity-E11D48?style=flat-square)
![Blockchain](https://img.shields.io/badge/Blockchain-Audit%20Layer-7C3AED?style=flat-square)

</div>

## Technology → Responsibility

| Technology | Role in Drishti |
|---|---|
| **Python** | AI and system development |
| **YOLOv8** | Real-time object detection |
| **OpenCV** | Video/frame processing |
| **PyTorch / TensorFlow** | ML model execution |
| **DeepSORT** | Multi-object tracking |
| **CRNN / OCR** | Number-plate recognition pipeline |
| **FastAPI** | Backend/API direction |
| **SQLite** | Local metadata storage |
| **RTSP** | IP-camera video streaming |
| **ONVIF** | Camera interoperability |
| **Docker** | Containerized deployment |
| **Kubernetes** | Future scalable deployment |
| **SHA-256** | Evidence integrity |
| **Blockchain** | Tamper-evident audit anchoring |
| **Edge GPU** | Near-source inference |

> **Note:** The stack represents the technical direction of the SIH solution. Components are being implemented progressively and should not be interpreted as production-deployed unless explicitly marked as such.

---

# How Drishti Works

## 01 — Camera Integration

Drishti connects with existing IP-CCTV infrastructure.

```text
Existing Camera
      │
      ├── RTSP
      │
      └── ONVIF
             ↓
      Drishti Ingestion
```

No replacement of the existing camera infrastructure is required in the proposed architecture.

---

## 02 — Video Preprocessing

Incoming streams are prepared for AI analysis.

Processing can include:

- Frame extraction
- Stream handling
- Low-light enhancement
- Noise reduction
- Image quality enhancement

---

## 03 — AI Perception

The AI layer detects relevant entities from video.

```text
Video Frame
     ↓
Object Detection
     ↓
┌──────────┬──────────┬──────────┐
│ Person   │ Vehicle  │ Plate    │
└──────────┴──────────┴──────────┘
```

---

## 04 — Tracking

Detections are converted into continuous movement trajectories.

```text
CAM 01
  ↓
Person detected
  ↓
CAM 02
  ↓
Same trajectory
  ↓
CAM 03
  ↓
Movement continues
```

This allows the system to reason about **movement rather than isolated frames**.

---

# Context-Aware Intelligence

Detection alone does not determine whether an event is important.

Drishti combines:

```text
        OBJECT
           +
        LOCATION
           +
          TIME
           +
        MOVEMENT
           ↓
   CONTEXTUAL ANALYSIS
           ↓
      EVENT PRIORITY
```

### Example

```text
Person Detected
      ↓
Restricted Zone?
      ↓
      YES
      ↓
Unusual Time?
      ↓
      YES
      ↓
Movement Analysis
      ↓
High-Priority Event
      ↓
Human Verification
```

This helps reduce unnecessary alerts caused by normal activity.

---

# Cross-Camera Intelligence

Traditional CCTV often treats each camera independently.

Drishti is designed to correlate activity across connected cameras.

```text
┌────────┐
│ CAM 01 │────┐
└────────┘    │
              ↓
┌────────┐  Movement  ┌────────┐
│ CAM 02 │───────────→│ CAM 03 │
└────────┘            └────────┘
              ↓
       Unified Movement
            Trail
```

The objective is to create a unified understanding of:

**Object + Location + Time + Movement**

---

# Secure Evidence Architecture

Security incidents require evidence that can be verified later.

Drishti separates **bulk evidence storage** from **integrity verification**.

```text
Video / Snapshot
       ↓
    Metadata
       ↓
    SHA-256
       ↓
 Integrity Hash
       ↓
Blockchain Anchor
```

### Important Design Principle

```text
Raw Video
   │
   └──────────────→ Off-Chain Storage

Metadata + Hash
   │
   └──────────────→ Blockchain Audit Layer
```

This avoids storing large video files directly on-chain while maintaining an integrity reference for the evidence.

---

# Security Layer

Security is built into the architecture.

### RBAC

Role-Based Access Control for authorized operators.

### Encryption

Protection of sensitive data in transit and at rest.

### SHA-256

Cryptographic hashing for evidence integrity verification.

### Blockchain Audit

Hash and metadata anchoring for a tamper-evident audit trail.

---

# Human-in-the-Loop

Drishti AI is designed as a **decision-support system**, not an autonomous enforcement system.

```text
AI Detection
     ↓
Context Analysis
     ↓
Priority Alert
     ↓
Human Review
     ↓
Operator Decision
```

The operator receives the relevant context required to verify the event.

---

# Prototype

<div align="center">

## Drishti AI Monitoring Dashboard

<img src="assets/drishti-prototype-dashboard.png" width="95%">

</div>

### Prototype demonstrates

- Multi-camera monitoring
- Live-view concept
- Recent security alerts
- Event priority
- Camera status
- Detection statistics
- Operator-oriented interface

### Live Prototype

**https://frontend-jade-five-73.vercel.app**

> The current prototype demonstrates the intended operational interface. AI inference, production-scale deployment and blockchain integration are being developed according to the implementation roadmap.

---

# Operational Scenario

## Night-Time Restricted-Zone Intrusion

```text
Existing CCTV
      ↓
Person Detected
      ↓
Movement Tracked
      ↓
Restricted Zone Detected
      ↓
Context:
02:00 + Restricted Zone
      ↓
Priority Increased
      ↓
Operator Alert
      ↓
Human Verification
      ↓
Evidence Captured
      ↓
SHA-256 Hash
      ↓
Blockchain Anchor
```

### Result

The system moves from:

**"A person was detected."**

to:

**"A potentially significant event occurred in a restricted zone at a specific time and location, with traceable evidence."**

---

# Edge & Connectivity Resilience

Border and remote surveillance environments may experience connectivity limitations.

Drishti's proposed architecture supports local edge processing.

### Normal

```text
Camera
  ↓
Edge AI
  ↓
Central Monitoring
```

### Network Disruption

```text
Camera
  ↓
Edge AI
  ↓
Local Event Buffer
  ↓
Local Operator
```

### Recovery

```text
Local Buffer
     ↓
Secure Synchronization
     ↓
Central Records
```

This architecture is intended to maintain local operational continuity during temporary connectivity loss.

---

# Current Status

| Component | Status |
|---|:---:|
| Problem Analysis | ✅ |
| System Architecture | ✅ |
| Technical Workflow | ✅ |
| UI Prototype | ✅ |
| Context-Aware Event Model | ✅ |
| Security Architecture | ✅ |
| Evidence Integrity Design | ✅ |
| RTSP/ONVIF Integration | 🔄 |
| AI Detection Pipeline | 🔄 |
| Multi-Object Tracking | 🔄 |
| Cross-Camera Correlation | 🔄 |
| Context Engine | 🔄 |
| SHA-256 Evidence Pipeline | 🔄 |
| Blockchain Integration | 🔄 |
| Edge Deployment | 📋 |
| End-to-End Testing | 📋 |

### Legend

```text
✅  Designed / Demonstrated
🔄  Under Implementation
📋  Planned
```

---

# Development Roadmap

```text
                 DRISHTI AI
                     │
        ┌────────────┴────────────┐
        ↓                         ↓
   Architecture              Prototype
        │                         │
        └────────────┬────────────┘
                     ↓
             Video Ingestion
                     ↓
               AI Detection
                     ↓
              Object Tracking
                     ↓
           Cross-Camera Analysis
                     ↓
            Contextual Engine
                     ↓
              Alert System
                     ↓
             Human Verification
                     ↓
            Evidence Integrity
                     ↓
             Blockchain Anchor
                     ↓
              Edge Deployment
                     ↓
              End-to-End Demo
```

---

# Research Foundation

The technical direction of Drishti is informed by research and established approaches in:

- Real-time object detection
- Multi-object tracking
- OCR / ANPR
- Surveillance anomaly detection
- Low-light image enhancement
- Edge AI
- Evidence integrity
- Blockchain audit systems

Relevant foundations include:

| Research / Technology | Application |
|---|---|
| **YOLOv8** | Object detection |
| **DeepSORT** | Multi-object tracking |
| **CRNN / OCR** | Number-plate recognition |
| **UCF-Crime** | Surveillance anomaly research |
| **LLVIP / ExDark** | Low-light processing |
| **Anti-UAV Research** | UAV detection research |

---

# Repository Structure

```text
Dristhi-AI/
│
├── README.md
├── LICENSE
├── SECURITY.md
├── .gitignore
├── .env.example
│
├── assets/
│   ├── drishti-prototype-dashboard.png
│   ├── drishti-technical-architecture.png
│   └── context-aware-intelligence.png
│
└── docs/
    ├── ARCHITECTURE.md
    ├── PROJECT_OVERVIEW.md
    ├── DEMO.md
    ├── IMPLEMENTATION_ROADMAP.md
    └── SIH_SCOPE.md
```

---

# SIH 2026

<div align="center">

### Smart India Hackathon 2026

**Problem Statement:** SIH26187

**AI-Based Intelligent Video Analytics Platform for Border Surveillance using Existing CCTV Infrastructure**

**Theme:** Blockchain & Cybersecurity  
**Category:** Software  
**Team:** Sudo -l  
**Team ID:** T57

</div>

---

# Team

<div align="center">

### Sudo -l

**Smart India Hackathon 2026**

*Building Drishti AI — Intelligent Surveillance Through Existing Infrastructure*

</div>

---

# Vision

Traditional CCTV provides the **eyes**.

Drishti AI adds the **intelligence layer**.

```text
┌─────────────────────────────────────────────┐
│                                             │
│        EXISTING SURVEILLANCE NETWORK       │
│                    +                        │
│              DRISHTI AI                    │
│                    ↓                        │
│       CONTEXT-AWARE INTELLIGENCE            │
│                    +                        │
│          SECURE EVIDENCE                    │
│                                             │
└─────────────────────────────────────────────┘
```

> **Drishti AI is not a replacement for the surveillance network.  
> It is the intelligence layer designed to make existing surveillance infrastructure actionable, contextual and auditable.**

---

## Disclaimer

This repository represents the **SIH 2026 project concept, architecture, prototype and implementation roadmap**.

Features marked as **Under Implementation** or **Planned** should not be interpreted as production-ready functionality.

The system is intended for authorized security and surveillance environments with appropriate access control, privacy and operational safeguards.
