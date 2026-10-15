# Medi Care — Online Healthcare Management System

A responsive, modern healthcare management web application featuring dedicated dashboards for **Administrators**, **Doctors**, and **Patients**. Built with clean HTML5, CSS3 (with dual Light & Dark mode support), and client-side JavaScript.

---

## 🌟 Key Features

- **Multi-Role Dashboards**:
  - **Admin**: Clinic overview, doctor/patient stats, user management, appointment coordination, and analytics.
  - **Doctor**: Daily schedule, consultation history, patient records, and patient feedback.
  - **Patient**: Upcoming visits, visit booking, private medical history timeline, and profile settings.
- **Dual Themes (Dark & Light Mode)**:
  - High-contrast Dark theme with midnight slate surfaces and luminous medical teal accents.
  - Clean Light theme with soft backgrounds.
  - Instant theme toggle positioned in the top-right corner, saved to `localStorage`.
- **Interactive Calendar & Status Tracking**:
  - Filter appointments by status: *Confirmed*, *Pending*, *Completed*, or *Cancelled*.
  - Monthly calendar overview with date indicator dots.
- **Nearby Emergency Services & Hospitals**:
  - Integrated browser Geolocation to quickly look up nearby clinics and hospitals on Google Maps.

---

## 🔑 Demo Login Credentials

All demo accounts use the single shared password below:

> **Password for All Roles:** `Pulse@2026`

| Role | Name | Email (Login ID) | Password |
| :--- | :--- | :--- | :--- |
| **Admin** | Marcus Vance | `director.vance@medicare.health` | `Pulse@2026` |
| **Doctor** | Dr. Elena Rostova | `dr.elena.rostova@medicare.health` | `Pulse@2026` |
| **Patient** | Lucas Bennett | `lucas.bennett@healthmail.net` | `Pulse@2026` |

---

## 🚀 How to Run Locally

### Option 1: Direct in Browser
Open `index.html` directly in any modern browser (Chrome, Edge, Firefox, Safari).

### Option 2: Local Node Server
Run the built-in lightweight Node server (no external dependencies required):

```bash
npm start
```
Then visit [http://localhost:3000](http://localhost:3000).

---

## 🌐 Live GitHub Pages Deployment

To host this site live on GitHub Pages for free:
1. Go to your repository **Settings** on GitHub.
2. In the left sidebar, click **Pages**.
3. Under **Build and deployment > Source**, select **Deploy from a branch**.
4. Choose the `main` branch and `/ (root)` folder, then click **Save**.
5. Your live app will be published at `https://<your-username>.github.io/<repo-name>/`.
