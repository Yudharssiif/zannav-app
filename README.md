# ZanNav — Public Transit & Daladala Navigation

Official website portal and distribution repository for **ZanNav**, an offline-first public transit and Daladala navigation application built exclusively for **Unguja, Zanzibar**.

* **Live Website**: [https://yudharssiif.github.io/zannav-app/](https://yudharssiif.github.io/zannav-app/)
* **Developer**: [GeoNovex](https://geonovex.netlify.app/)
* **Platform**: Android (APK) & Web Portal
* **Coverage Scope**: Unguja Island, Zanzibar, Tanzania

---

## Overview

ZanNav solves the everyday transit challenges of commuters, students, and visitors across Unguja. Public transport on the island is powered by Daladalas (local minibuses) and connecting transit corridors that traditionally lacked digital mapping, route numbers, or verified stop coordinates.

ZanNav provides an offline-first mobile navigation experience with on-device graph routing, stop directories, and multi-modal transit calculation that operates with zero mobile data consumption.

---

## Key Features

### 1. 100% Offline Navigation
* Download the compact Unguja vector map pack (~8.7 MB) once.
* All route calculation, stop searches, road networks, and trip planning algorithms execute entirely on the user's phone without requiring internet access or active cellular data.

### 2. Verified Daladala Routes & Terminals
* Comprehensive coverage across major Unguja transit corridors, including:
  * **Line 504**: Mnazi Mmoja Terminal ↔ Kisimani (Fuoni)
  * **Line 507**: Mnazi Mmoja Terminal ↔ Kiembe Samaki Mwisho
  * Major transit hubs including Mnazi Mmoja, Darajani, and Mwanakwerekwe.
* Terminals and terminus stops are automatically recognized and prioritized.

### 3. Multi-Modal Smart Transfers
* When no direct bus connects the origin and destination, ZanNav calculates multi-modal paths combining:
  * Walking legs to the closest verified boarding stop.
  * Daladala transit segments.
  * Clear cross-street transfer instructions (e.g., at Makada Bus Stop) to switch between intersecting lines.

### 4. Native Location Intent Sharing
* Registers with the Android operating system to handle standard geographic intents (`geo:` URIs and web map links).
* When a location pin is shared via WhatsApp, Telegram, or SMS, users can tap "Open with ZanNav" to initiate immediate transit routing.

### 5. Bilingual Experience
* Native bilingual support in both **Kiswahili** and **English** with instant switching.

### 6. Privacy-by-Design
* Zero user accounts, registration, or logins required.
* Live GPS coordinates never leave the device and are never sent to remote servers.
* No advertising SDKs, background tracking, or commercial telemetry.

---

## Android APK Installation

To install ZanNav directly on an Android device:

1. **Download APK**: Download `zannav-app.apk` directly from this repository or via the [official website](https://yudharssiif.github.io/zannav-app/).
2. **Enable Unknown Sources**: If prompted by Android, permit installation from your browser or file manager (**Settings > Security > Install unknown apps**).
3. **Install & Launch**: Tap the APK file and select **Install**.
4. **Download Offline Map**: On first launch, allow location access and tap the prompt in Settings to download the ~8.7 MB Unguja offline vector map pack.

### System Requirements
* **Operating System**: Android 8.0 (API Level 26) or higher.
* **Storage Space**: ~45 MB for application + ~8.7 MB for the offline map pack.
* **Permissions**: Fine & Coarse Location (optional for manual route entry; required for live GPS centering and boarding detection).

---

## Repository Structure

```text
zannav-app/
├── index.html            # Main landing page & interactive corridor preview
├── style.css             # Vanilla CSS design system & responsive layout
├── terms.html            # Public Terms of Service
├── privacy.html          # Public Privacy Policy
├── favicon.svg           # Vector app branding icon (Material bus mark)
├── zannav-app.apk        # Android application package (release build)
├── TERMS.md              # Markdown source for Terms of Service
└── README.md             # Project documentation
```

---

## GitHub Pages Deployment

This repository is pre-configured for instant deployment on GitHub Pages:

1. Fork or push this repository to your GitHub account (`https://github.com/Yudharssiif/zannav-app`).
2. Navigate to **Settings > Pages** in your repository.
3. Under **Build and deployment**:
   * **Source**: `Deploy from a branch`
   * **Branch**: `main`, Folder: `/ (root)`
4. Click **Save**. Your site will be published at `https://<username>.github.io/zannav-app/`.

---

## Open Data & Attribution

* **Transit & Map Data**: OpenStreetMap contributors. Map data is available under the [Open Database License (ODbL)](https://www.openstreetmap.org/copyright).
* **Community Contributions**: Missing bus stop submissions and corridor verifications are validated and contributed back to OpenStreetMap to support the broader Zanzibar mapping ecosystem.

---

## Developer & Contact

ZanNav is designed, developed, and maintained by **GeoNovex**.

* **Website**: [https://geonovex.netlify.app/](https://geonovex.netlify.app/)
* **Inquiries**: [https://geonovex.netlify.app/](https://geonovex.netlify.app/)
* **Location**: Zanzibar, Tanzania

---

## Legal

* [Terms of Service](terms.html)
* [Privacy Policy](privacy.html)

Copyright 2026 ZanNav. Developed by GeoNovex. All rights reserved.
