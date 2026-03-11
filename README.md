# Fire Safety Check‑in (MVP)

An interactive MVP for a campus fire‑safety management system featuring immutable audit logging, gamified user engagement, and UK GDPR‑compliant data tools.

> **Note:** This repository is a **university assignment** and is kept **private** to maintain academic integrity and prevent plagiarism.

---

## ✨ Features

### 🔥 Fire Safety & Engagement Tools
- Interactive location check‑in UI (assembly points, workshops, library, dining hall)
- Gamified points system with safety and engagement rewards
- Role-based interface (Student / Fire Warden / Staff)
- Badge unlocking system tied to safety activity
- Fire‑drill simulator toggling UI, states, and facility status

### 📊 Data Integrity & Logging
- Append‑only "immutable‑style" transaction log
- Per-entry session tokens
- Tamper-evident hashing (simulated)
- Duplicate-check guard preventing repeat check‑ins

### 🔐 Privacy, GDPR & User Control
- Full JSON data export (Article 15 – Right of Access)
- Local data deletion workflow (Article 17 – Right to Erasure)
- Visibility controls (leaderboard privacy)
- Preference management (notifications, reminders, analytics opt‑in)

### 💾 Local Persistence
- All data stored in `localStorage` / `sessionStorage`
- Survives refresh and browser restart
- No server required

---

## 🧱 Technologies Used

- **HTML5**  
- **CSS3** (custom UI, grid layouts, responsive design)  
- **Vanilla JavaScript**  
- **localStorage / sessionStorage** for offline persistence  
- **SHA‑style simulated hashing**  
- **No frameworks required**  

---

## 🧪 How to Demonstrate (For Markers)

To test the application during assessment:

1. Open `fire-safety-checkin.html` in any modern browser.
2. Select a location and click **Check In**.
3. Toggle **Simulate Fire Drill** to change system state.
4. Go to **Privacy & GDPR** → Export → Download JSON.
5. Refresh the page and observe:
   - Points are preserved
   - Immutable log grows
   - Preferences remain saved
6. Attempt duplicate check‑ins to verify fraud‑prevention logic.

---

## 🚀 Quick Start

1. Clone or download the repo:
   ```bash
   git clone <your-private-repo-url>
