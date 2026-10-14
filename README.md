# Medical Research Facility - IT Management & SOP Portal

## Overview
The Medical Research Facility IT Management & Standard Operating Procedures (SOP) Portal is a centralized web-based dashboard designed for facility staff, administrators, and IT personnel. It provides immediate, organized access to IT governance, network architecture summaries, and core operational policies.

---

## Infrastructure Scope
* **Admin Block:** 3 floors, supporting 50 users and 1 central server.
* **Laboratory Buildings:** 3 separate buildings, 5 floors each, supporting 150 total PC workstations and 15 networked printers.
* **Network Design:** Layer 3 Core, Layer 2 access switches utilizing Spanning Tree Protocol (RSTP) for loop prevention, and robust fiber/Cat6 cabling backbones.

---

## Technologies Used
* **HTML5:** Semantic document markup structuring the dashboard interface.
* **Tailwind CSS (CDN):** Utility-first styling framework providing responsive grid layouts, card containers, and modern styling without external CSS compilation sheets.
* **FontAwesome (CDN):** Vector icon library powering the visual UI icons for navigation and policy modules.
* **Google Fonts:** Clean, professional typography utilizing the *Inter* font family.

---

## Project Directory Structure
```text
medical-research-facility/
│
├── index.html              # Main dashboard webpage containing all SOP modules
└── images/
    └── organizational_structure_image.png  # Embedded MS Visio organizational governance chart