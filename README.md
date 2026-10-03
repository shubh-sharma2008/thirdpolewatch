# ThirdPoleWatch – Digital Monitoring of Glacier Melting in the Himalayas

**Educational Product (Website)**  
CA-1 Project | Environmental Studies (CHE110)  
Lovely Professional University | Section K3P26MH | Group 17

## Team
- **Shubh Sharma** (RK3P26MHB53 / 12621940)
- **Md Idban Mallick** (RK3P26MHB55 / 12601601)

**Submitted to:** Dr. Aditi

## How to Run (Working Model)

### Option 1 – Double-click (simplest)
1. Open the folder `glacier_website`
2. Double-click `index.html`
3. The website will open in your default browser

### Option 2 – Local server (recommended for best experience)
```bash
# From inside the glacier_website folder:
python3 -m http.server 8080
```
Then open: http://localhost:8080

## Folder Structure
```
glacier_website/
├── index.html          ← Main page
├── css/
│   └── style.css       ← All styles
├── js/
│   └── main.js         ← Navigation & animations
├── images/             ← Glacier photos from research video
└── README.md
```

## Features
- Fully responsive (mobile + desktop)
- Modern clean UI
- Sections: Introduction, Digital Monitoring, Machine Learning, GLOF Risk, SDGs, Team
- Smooth scroll navigation
- No external dependencies except Google Fonts (works offline after first load if fonts are cached)

## Topic Covered
Digital monitoring of glacier melting in the Himalayan region using:
- Optical satellites (Sentinel-2, Landsat) + NDSI
- Synthetic Aperture Radar (Sentinel-1)
- DEM differencing (TanDEM-X, ALOS)
- Deep learning (CNN / U-Net) for debris-covered glaciers
- GLOF early-warning systems
- Linkage to UN SDGs 6, 13 & 15
