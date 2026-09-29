# 🆘 SaharaAI — National Disaster Grid & Emergency Command

**Project built for Hack2Skill Google Build with AI: Code for Community 2nd Edition**  
*Track Alignment: Resilience | Cooperation | Governance | Sustainability*

---

## 🌟 What is SaharaAI?
SaharaAI is India's first AI-powered multi-modal emergency command and evacuation brain. When disasters strike, fragmented agency communications, language barriers, and telecom blackout windows cost human lives. SaharaAI unifies **citizens, NDRF responders, hospitals, volunteers, and district authorities** on a single coordinated, offline-resilient operational intelligence grid.

---

## 🚀 Key Modules Built & Tested

1. **Clean Command Center (Landing Page)**
   - No distracting orbs or circular radar animations.
   - Clean split-hero layout with live incident monitor, emergency hotlines (`112`, `108`, `101`, `1077`), and regional telemetry.
   - Full-width role selection tiles with clear typography and distinct accent cues.

2. **Full Light / Dark Mode Toggle**
   - High-contrast, accessibility-tested theme engine with instant toggle and `localStorage` persistence.
   - Designed for high-stress day/night operational viewing.

3. **Citizen Multimodal SOS Intake**
   - 22 Indian regional languages support (Hindi, Gujarati, Tamil, Telugu, Bengali, English).
   - Voice audio recording with simulated Gemini transcription + scene photo upload.
   - High-priority 1-tap SOS trigger with instant countdown ETA and hospital routing.

4. **Tactical CAD Map & Safe Bypass Routing (Leaflet.js)**
   - Centered on Rajkot, Gujarat (incident `#INC-001` at Ring Road).
   - 500m hazard danger radius circle.
   - Blocked road corridor detection + automated alternative North-West bypass polyline.
   - Live vehicle tracking simulation navigating to Gokul Superspeciality Hospital.
   - Street view & satellite view toggle.

5. **Hospital Surge & Casualty Preparedness**
   - Real-time ICU, OT, and blood bank reserve tracking.
   - Incoming patient roster with countdown ETAs and diagnosis breakdown.
   - Vertex AI / Gemini mass casualty surge forecaster with interactive Chart.js projection.

6. **Civil Defense & Volunteer Hub (Cooperation Track)**
   - AI skill-matching engine (e.g. Red Cross First Aid, Boat Handling, HAM Radio).
   - Real-time task claiming board for sandbagging, first aid, and community kitchens.
   - Gamified volunteer tiers (Silver Responder Tier).

7. **AI Early Warning & Google Flood Forecasting Grid**
   - Live Aji River hydrograph (Sensor 04) charting observed telemetry vs. 6-hour forecast curve.
   - Multi-channel emergency broadcast simulator (FCM mobile push, telecom SMS, IVR voice calls to Gram Panchayats).

8. **Offline Mesh Relay Simulator**
   - Demonstrating Bluetooth Low Energy (BLE) & WiFi-Direct peer-to-peer distress packet relay when cellular infrastructure goes down.

---

## 💻 How to Open & Run
The entire application is completely self-contained with **zero build dependencies**:
- Simply double click `index.html` or open it in Google Chrome, Edge, Brave, or Safari.
- Or host it instantly for free on **GitHub Pages**, **Vercel**, or **Firebase Hosting**.

---

## 🏆 Pitch Deck One-Liner for Hack2Skill Judges
> *"When disasters strike in India, responders navigate blind and systems operate in silos. SaharaAI connects citizens in 22 languages, provides turn-by-turn hazard bypass routing, prepares hospitals before ambulances arrive, and still works via phone-to-phone mesh when cellular towers collapse."*
