<p align="center">
  <a href="https://yudharssiif.github.io/zannav-app/">
    <img src="logo.png" alt="ZanNav Mapper Logo" width="140" height="140" style="border-radius: 20px;">
  </a>
</p>

<h1 align="center">ZanNav Mapper</h1>

<p align="center">
  <strong>Community Daladala Route Mapping &amp; Public Transit Field Data Collection for Unguja, Zanzibar</strong>
</p>

<p align="center">
  <a href="https://github.com/Yudharssiif/zannav-app/releases/latest/download/zannav-mapper-v1.0.6.apk"><img src="https://img.shields.io/badge/Download%20APK-v1.0.6-8b5cf6?style=for-the-badge&logo=android&logoColor=white" alt="Download ZanNav Mapper APK"></a>
  <a href="https://yudharssiif.github.io/zannav-mapper-app/"><img src="https://img.shields.io/badge/iOS%20Web%20App-Safari%20PWA-10b981?style=for-the-badge&logo=safari&logoColor=white" alt="iOS Web App"></a>
  <a href="https://yudharssiif.github.io/zannav-app/"><img src="https://img.shields.io/badge/Live%20Portal-GitHub%20Pages-0ea5e9?style=for-the-badge&logo=githubpages&logoColor=white" alt="Live Portal"></a>
  <a href="https://geonovex.netlify.app/"><img src="https://img.shields.io/badge/Developer-GeoNovex-6366f1?style=for-the-badge" alt="GeoNovex"></a>
</p>

---

## Overview

**ZanNav Mapper** is an open, community-driven spatial data collection tool created exclusively for **Unguja, Zanzibar**. 

Every day, hundreds of thousands of islanders rely on **Daladalas** (local minibuses) to commute between urban hubs and residential corridors. However, Zanzibar's public transit network has historically lacked formal open digital maps, standardized route codes, or verified bus stage (*vituo*) coordinates.

ZanNav Mapper puts data collection directly in the hands of commuters, students, researchers, and transport advocates. Using on-device GPS logging and offline point-of-interest tagging, contributors trace actual Daladala paths and verify boarding stages to build Zanzibar's first open public transit database.

* **Live Community Portal**: [https://yudharssiif.github.io/zannav-app/](https://yudharssiif.github.io/zannav-app/)
* **Direct Android APK Download**: [ZanNav Mapper APK v1.0.6](https://github.com/Yudharssiif/zannav-app/releases/latest/download/zannav-mapper-v1.0.6.apk)
* **iOS Web App (Safari PWA)**: [https://yudharssiif.github.io/zannav-mapper-app/](https://yudharssiif.github.io/zannav-mapper-app/)
* **Lead Developer**: [GeoNovex](https://geonovex.netlify.app/)
* **Target Region**: Unguja Island, Zanzibar, Tanzania

---

## Priority Corridors Needing Mapping

The mapping effort is prioritized across high-demand commuter arteries connecting Zanzibar's central business district with growing residential and commercial zones:

| Corridor | Key Stops / Landmarks | Status | Progress | Priority |
| :--- | :--- | :---: | :---: | :---: |
| **Fuoni ↔ Mnazi Mmoja** | Mnazi Mmoja • Mwanakwerekwe • Kisimani Fuoni | In Progress | **80%** | Moderate |
| **Kiembe Samaki ↔ Mnazi Mmoja** | Mnazi Mmoja • Kwerekwe • Kiembe Samaki Mwisho | In Progress | **60%** | Moderate |
| **Bububu ↔ Mnazi Mmoja** | Mnazi Mmoja • Darajani • Mtoni • Bububu Kituoni | Not Started | **0%** | **High** |
| **Bububu ↔ Fuoni** | Bububu • Masingini • Mwanakwerekwe • Fuoni | Not Started | **0%** | **High** |
| **Uwanja wa Ndege ↔ Mnazi Mmoja** | Mnazi Mmoja • Kilimani • Airport Terminal (AAKT) | Not Started | **0%** | **High** |
| **Chukwani ↔ Mnazi Mmoja** | Mnazi Mmoja • Mbweni • Chukwani Mwisho | Not Started | **0%** | Normal |
| **Daraja Bovu ↔ Mnazi Mmoja** | Mnazi Mmoja • Kariakoo • Daraja Bovu | Not Started | **0%** | Normal |
| **Secondary Feeder Routes** | Rural arteries, peripheral hubs, & cross-town spurs | Needs Help | **0%** | Open |

> *Want to claim one of these corridors? Download the APK and start recording during your daily commute.*

---

## Core Features

### 1. High-Precision GPS Trace Recording
* Record clean breadcrumb trails while riding any Daladala.
* Configurable waypoint intervals to balance positional accuracy with battery efficiency.
* Native export to standard **GPX** and **GeoJSON** spatial formats.

### 2. Rapid Bus Stage (*Kituo*) Pinning
* Drop a bus stop marker in two taps without interrupting GPS logging.
* Log local Swahili names (e.g. *Kituo cha Makada*, *Darajani Terminal*, *Kiembe Samaki Mwisho*).
* Designate shelter availability, boarding direction, and cross-street transfer points.

### 3. 100% Offline Field Capability
* Collect data in remote or low-connectivity corridors with zero cellular data requirements.
* Stores traces and bus stages safely in local SQLite storage until you are ready to export or upload.

### 4. Open-Data First Ethos
* All collected geometry feeds into the open Zanzibar transit repository.
* Data is prepared for upstream integration into **OpenStreetMap (OSM)** and General Transit Feed Specification (**GTFS**).

### 5. Privacy & Contributor Autonomy
* No forced account creation, passwords, or personal profile tracking.
* Only spatial transit tracks you intentionally choose to save and submit are recorded.

---

## Download & Platform Access

ZanNav Mapper is available across platforms:

### 1. Android Native App (v1.0.6 APK)
Distributed directly via GitHub Releases:
1. **Download APK**: Download [`zannav-mapper-v1.0.6.apk`](https://github.com/Yudharssiif/zannav-app/releases/latest/download/zannav-mapper-v1.0.6.apk) directly to your Android device.
2. **Enable Unknown Apps**: When prompted by your browser or file manager, allow permission (**Settings > Apps > Special app access > Install unknown apps**).
3. **Install & Open**: Tap the downloaded file and select **Install**.
4. **Grant Location**: Allow Fine Location permission so your phone's GPS can track route geometry.

* **Requirements**: Android 8.0 (API Level 26) or higher • GPS receiver • ~25 MB storage.

### 2. Apple iOS Web App (Safari PWA)
Exported for iPhone & iPad users without requiring App Store or TestFlight:
1. **Open Safari**: Visit [https://yudharssiif.github.io/zannav-mapper-app/](https://yudharssiif.github.io/zannav-mapper-app/).
2. **Share**: Tap the **Share** button (box with upward arrow) in the bottom navigation bar.
3. **Add to Home Screen**: Scroll down and select **"Add to Home Screen"**, then tap **"Add"**.
4. **Launch**: Open from your Home Screen for a standalone, full-screen offline-ready mapping experience with live GPS location tracking.

---

## How to Map a Route (Contributor Guide)

```text
1. BOARD DALADALA  ──>  2. TAP "START ROUTE"  ──>  3. PIN EACH STOP (KITUO)  ──>  4. FINISH & EXPORT
```

1. **Plan Your Trip**: Select an unmapped corridor from the list above.
2. **Start Recording**: Board the Daladala at its origin terminal and tap **Start GPS Recording** in ZanNav Mapper.
3. **Pin Bus Stops**: Whenever the Daladala stops to pick up or drop off passengers, tap **Pin Stop** and enter the local name.
4. **Finish at Terminus**: When you reach the final destination stage, tap **Stop & Save**.
5. **Share Your Track**: Export the GPX/GeoJSON or submit directly through the portal to have your contribution reviewed and added to the official network map.

---

## Repository Structure

All website files, manifests, icons, and documentation reside in the root repository folder:

```text
.
├── index.html                   # Community portal & corridor mapping web application
├── style.css                    # Modern CSS design system & layout styling
├── logo.png                     # Official ZanNav Mapper brand logo (1000x1000)
├── favicon-96x96.png            # 96x96 PNG browser favicon
├── favicon.ico                  # Standard ICO browser favicon
├── favicon.svg                  # High-resolution vector SVG favicon
├── apple-touch-icon.png         # iOS 180x180 Apple Touch home-screen icon
├── site.webmanifest             # PWA web manifest configuration
├── web-app-manifest-192x192.png # PWA 192px application icon
├── web-app-manifest-512x512.png # PWA 512px application icon
├── terms.html                   # Contributor & user Terms of Service
├── privacy.html                 # Contributor & user Privacy Policy
├── PRIVACY_POLICY.md            # Markdown source for Privacy Policy
└── README.md                    # Project documentation & contributor guide
```

---

## GitHub Pages Deployment

The ZanNav Mapper web portal is hosted directly via GitHub Pages:

1. Push or fork this repository to your GitHub account (`https://github.com/Yudharssiif/zannav-app`).
2. Go to **Settings > Pages**.
3. Under **Build and deployment**:
   * **Source**: `Deploy from a branch`
   * **Branch**: `main`, Folder: `/ (root)`
4. Click **Save**. The website will be live at `https://<username>.github.io/zannav-app/`.

---

## Open Transit Data & Attribution

* **Transit Geometry**: Contributed by the Zanzibar transit community under the [Open Database License (ODbL)](https://www.openstreetmap.org/copyright).
* **Basemaps & Cartography**: © [OpenStreetMap](https://www.openstreetmap.org/) contributors.
* **Community Validation**: All collected corridor lines and bus stops are cross-referenced with local transit operators to guarantee passenger safety and data reliability.

---

## Developer & Contact

ZanNav Mapper is conceptualized, engineered, and maintained by **GeoNovex**.

* **Website**: [https://geonovex.netlify.app/](https://geonovex.netlify.app/)
* **Inquiries & Partnerships**: [https://geonovex.netlify.app/](https://geonovex.netlify.app/)
* **Headquarters**: Zanzibar, Tanzania

---

## Legal

* [Terms of Service](terms.html)
* [Privacy Policy](privacy.html)

&copy; 2026 ZanNav Mapper. Developed by GeoNovex. All rights reserved.
