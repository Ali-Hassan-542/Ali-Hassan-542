<!-- ============================================= -->
<!--   SafeTrack - Header                         -->
<!-- ============================================= -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=180&section=header&text=SafeTrack&fontSize=50&fontAlignY=40&animation=twinkling" width="100%" alt="SafeTrack Header" />
</p>

<h1 align="center">📡 SafeTrack — Consent-Based Online Tracking Web App</h1>

<p align="center">
  <i>A privacy-first, consent-based live location tracking demo — request permission, manage consents, and view live locations on a Leaflet map. Your data stays in your browser (or an optional PHP backend).</i>
</p>

<!-- ============================================= -->
<!--   Badges                                      -->
<!-- ============================================= -->
<p align="center">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white" alt="PHP" />
  <img src="https://img.shields.io/badge/Bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white" alt="Bootstrap" />
  <img src="https://img.shields.io/badge/Leaflet-199900?style=for-the-badge&logo=leaflet&logoColor=white" alt="Leaflet" />
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL" />
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Status-For%20Educational%20Use-F59E0B?style=flat-square" alt="Status" />
  <a href="https://github.com/Ali-Hassan-542">
    <img src="https://img.shields.io/badge/Author-Ali%20Hassan-0D1B2E?style=flat-square&logo=github&logoColor=36BCF7" alt="Author" />
  </a>
</p>

---

## 📖 Overview

**SafeTrack** demonstrates modern location-tracking patterns while keeping **user consent and privacy** at the center. Request location permission, manage who you share with, and watch live positions on an interactive Leaflet map. With no backend configured, everything runs locally in the browser; a lightweight **PHP + MySQL** backend is included for server-side persistence.

> ⚠️ **Educational use only.** Always obtain explicit consent before tracking anyone's location.

---

## ✨ Key Features

- 🗺️ **Live Location Mapping** — real-time positions on a Leaflet interactive map
- 🔐 **Consent Management** — request, approve & revoke tracking permission
- 🔒 **Privacy-First** — browser-only mode keeps data on-device by default
- ⚙️ **Optional PHP Backend** — persistent storage with MySQL when enabled
- 📱 **Responsive UI** — clean Bootstrap 5 interface

---

## 🖼️ Screenshots

<p align="center">
  <img src="Image-1.jpg" alt="SafeTrack Screenshot 1" width="48%" />
  <img src="image-2.jpg" alt="SafeTrack Screenshot 2" width="48%" />
</p>

---

## 🛠️ Tech Stack

| Layer | Technologies |
| --- | --- |
| **Frontend** | HTML5, CSS3, JavaScript, Bootstrap 5 |
| **Maps** | Leaflet.js |
| **Backend (optional)** | PHP (`api.php`) |
| **Database (optional)** | MySQL (`schema.sql`) |

---

## 📁 Project Structure

```text
Online-Tracking-Web-App/
├── index.html          # Landing page
├── tracking.html       # Live tracking view
├── script.js           # Core tracking logic
├── api.js              # API / data helpers
├── database.js         # Database helper
├── style.css           # Styles
├── Image-1.jpg         # Screenshot
├── image-2.jpg         # Screenshot
└── backend/            # Optional PHP backend
    ├── api.php         # REST endpoints
    ├── config.php      # DB configuration
    ├── db.php          # Database connection
    ├── helpers.php     # Utility functions
    ├── providers.php   # Location providers
    └── schema.sql      # MySQL schema
```

---

## 🚀 Getting Started

### Option 1 — Browser Only (no backend)

1. **Clone the repository**
   ```bash
   git clone https://github.com/Ali-Hassan-542/Online-Tracking-Web-App.git
   ```
2. Open `tracking.html` directly in your browser, or serve the folder with **Live Server** (VS Code).

### Option 2 — With PHP + MySQL Backend

1. Clone the repo and move it into `C:\xampp\htdocs\safetrack`.
2. Start **Apache** and **MySQL** in XAMPP.
3. Import the database schema:
   ```bash
   mysql -u root -p < backend/schema.sql
   ```
4. Update the DB credentials in `backend/config.php`.
5. Open `http://localhost/safetrack/tracking.html`.

---

## 🗺️ Roadmap

- [ ] Push notifications on consent changes
- [ ] Geofencing alerts & zone management
- [ ] Route history with playback
- [ ] End-to-end encrypted location updates
- [ ] Docker-based deployment

---

## 🤝 Contributing

Contributions, issues and feature requests are welcome! Feel free to open a pull request or report a bug in the [Issues](https://github.com/Ali-Hassan-542/Online-Tracking-Web-App/issues) tab.

---

## 📬 Author

**Ali Hassan** — Full Stack Developer & Backend AI Engineer

<p align="left">
  <a href="https://github.com/Ali-Hassan-542">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
  </a>
  <a href="https://www.linkedin.com/in/ali-hassan-a294a4411">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="https://portfolio-ali-hassan.netlify.app">
    <img src="https://img.shields.io/badge/Portfolio-0D1B2E?style=for-the-badge&logo=react&logoColor=36BCF7" alt="Portfolio" />
  </a>
  <a href="mailto:ali78601hassan@gmail.com">
    <img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
</p>

---

<p align="center">
  <i>"Code with Logic. Build with Passion."</i>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=120&section=footer" width="100%" alt="Footer" />
</p>
