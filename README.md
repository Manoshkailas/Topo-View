# 🗺️ TopoView – Automated Topographic & Site Analysis Platform

TopoView is an intelligent, automated land‑analysis platform that generates accurate topographic maps, identifies vacant land, extracts buildings and roads, and provides clean, professional outputs for planning, documentation, and verification. The system is designed for speed, clarity, and reliability, making it ideal for architects, surveyors, real‑estate professionals, and landowners.

---

## 🚀 Features

### 🗺️ 1. Topo View (Topographic Analysis)
Topo View converts any location into a detailed topographic map within seconds.  
It automatically extracts:
- Building footprints  
- Road networks with names  
- Vacant land regions  
- Site boundaries  
- Accurate area calculations  
- Clean, non‑overlapping labels  

Vacant land is automatically detected and clearly marked as **“Vacant Land”** using a light grey fill and dashed outline.

Only the **Topographic Plot** output is available.  
All **Site Layout** related buttons, UI, and backend logic have been removed.

---

## 🧭 2. Accurate Location Detection
The system fetches the user’s current location with improved accuracy and fallback logic.  
If location detection fails, the system retries and provides a clear error message.

Users can also find their plot by **sharing the Google Maps location link**, as mentioned in the Quick Start Guide.

---

## 🛠️ 3. Site Plan Editor
The Site Plan Editor allows users to:
- Move roads, buildings, and elements freely  
- Rotate and reshape elements  
- Edit without restrictions  
- Maintain clean label visibility  

Labels never appear behind map elements in both the generated topo and the editing interface.

---

## 💳 4. Payment System (₹100 Per Generation)
Each topo or site plan generation requires a **₹100 payment**.

Strict rule:
- **₹100 = 1 generation only**
- Even if the user stays on the same page, a new generation requires a new payment
- No free re‑generation
- No bypassing by refreshing or staying in the same tab

Backend validation ensures that each generation credit is used exactly once.

---

## ⭐ 5. Premium Membership (₹2000)
Premium membership unlocks full access to the platform.

### Membership Rules:
- Membership is stored in the backend (start date, end date, active status)
- Premium users retain access across all devices and browsers
- Membership is checked on every login
- No accidental redirects to /premium for active members
- Membership lasts for 183 days

---

## 🔁 6. Smooth Navigation Flow
The entire navigation system is rebuilt for stability.

### Flow:
1. `/auth` → Login  
2. `/premium` → Membership activation  
3. `/dashboard` → Main workspace  
4. `/site-plan` or `/map` → After ₹100 payment  

No unwanted redirects.  
No loops between `/dashboard` and `/premium`.  
Back/forward navigation works smoothly.

---

## 🎨 7. Unified UI Design
The `/map` page now uses the same background design and theme as the authentication page, ensuring a consistent visual experience across the platform.

---

## 📦 Outputs
- **Topographic Plot (PDF)**  
- Clean, readable, professional layout  
- Labels never overlap or hide behind elements  

---

## 📘 Quick Start Guide
1. Login or create an account  
2. Activate premium membership (₹2000)  
3. Go to Dashboard  
4. Share your Google Maps location link to find your plot  
5. Pay ₹100 to generate a topo or site plan  
6. Download the Topographic Plot  

---

## 🧩 Tech Highlights
- Automated OSM data extraction  
- Vacant land detection  
- Label collision avoidance  
- Backend‑validated payment credits  
- Persistent membership system  
- Smooth routing with protected pages  
- Unified UI/UX across all pages  

---

## 🛡️ Security
- Membership and payment data stored securely  
- Backend validation prevents bypassing  
- No frontend‑only checks  
- Session persistence across devices  
