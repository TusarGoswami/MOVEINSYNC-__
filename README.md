# MoveInSync • Play Store Strategy & User Experience Optimization
## Forward Deployed Engineer (FDE) Case Study Deliverable

**Author:** Tusar  
**Role:** Forward Deployed Engineer (FDE)  
**Target:** MoveInSync Product & Engineering Leadership  
**Date:** October 2026  

---

## 📌 Overview

This repository contains the complete case study submission for the MoveInSync Forward Deployed Engineer role. It provides an empirical forensic audit into recent user sentiment on the Google Play Store (covering Jan 2025 – Oct 2026 releases), isolating systemic mobile failure modes, algorithmic routing constraints, and hostile rating mechanics.

---

## 📂 Deliverables in this Repository

| File | Description |
| :--- | :--- |
| **[`MoveInSync_PlayStore_Recommendation.md`](./MoveInSync_PlayStore_Recommendation.md)** | **Core Strategy Document:** Complete forensic audit, root-cause engineering analyses, 3-tier roadmap (Now/Next/Later), and autonomous telemetry architecture. |
| **[`MoveInSync_Executive_Deck.pdf`](./MoveInSync_Executive_Deck.pdf)** | **Executive Slide Deck (PDF):** 16:9 widescreen presentation featuring problem statements, real user quotes, diagrams, and prioritized action plan. |
| **[`MoveInSync_PlayStore_Recommendation.pdf`](./MoveInSync_PlayStore_Recommendation.pdf)** | **Executive Report (PDF):** Formatted report ready for executive reading. |
| **[`MoveInSync_Executive_Deck.pptx`](./MoveInSync_Executive_Deck.pptx)** | **PowerPoint Presentation:** Standard editable 16:9 widescreen presentation. |
| **[`index.html`](./index.html)** | **Interactive Web Presentation:** Self-contained slide deck with dual Light/Dark modes, quick-jump thumbnail navigation, and high-contrast styling. |

---

## 🎯 Key Findings & 3-Tier Roadmap Summary

### 🚨 Critical Findings
1. **The #1 Crash Bug ("Not Installed from Play Store"):** Google Play Integrity API attestation failure causing client-side hard kills on Android 14–17 and Pixel devices.
2. **Hostile Rating Loophole:** Forced unskippable rating modals combined with a 4-5★ lock are actively driving angry commuters to leave 1★ retaliatory reviews on the Play Store.
3. **Session Dropout at Gates:** Wi-Fi to cellular handover outside campus turnstiles triggers socket timeouts that wipe local authentication tokens right when the cab arrives.
4. **Algorithmic Detour Fatigue ("Bharat Darshan"):** 40-minute commutes turning into 2.5 hours due to over-optimized seat pooling without detour ceilings.

### 🛠️ Phased Execution Plan
* **Tier 1 (Week 1 — "Stop The Bleeding"):** Relax startup Play Integrity hard-abort; add visible "Skip" button to rating dialogs; cache offline ride metadata & OTP.
* **Tier 2 (Month 1 — "Restore Trust"):** Real-time GPS WebSocket streaming; map auto-zoom gesture override; multi-tier WhatsApp OTP fallback; in-app driver messaging.
* **Tier 3 (Quarter 1 — "Competitive Edge"):** Algorithmic detour ceiling ($T_{\text{max}} \le 1.4 \times T_{\text{direct}}$); native Dark Mode for late-night shifts; automated LLM feedback triage pipeline.

---
*Authored with dedication by Tusar.*
