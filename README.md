# NOLE
NOLE - Nautical Open Learning Explorer. A hands-on discovery map for kids who love boats, wildlife, and Tampa Bay. Find boats, islands, and wildlife with real data and marine charts. Learn the bay your way - look deeply, explore freely, one discovery at a time.



# NOLE — Nautical Open Learning Explorer

**NOLE** is an interactive learning map designed for kids who love boats, water, wildlife, and understanding how things work. It helps young explorers learn about Tampa Bay using **real marine data**, **authentic navigation charts**, and **hands-on discovery**—at their own natural learning rhythm.

Dedication

This project is created **for Nole** who loves boats.  
His curiosity is the heart of NOLE.

May this map be a place where exploration feels natural, information is real, and learning happens just by looking closely.


Project Purpose

NOLE is a **kid-friendly, research-grade learning tool** that blends:

- Real **marine and coastal data**
- Interactive **map layers**
- Gentle **exploration-based learning**
- Respect for **sensory sensitivity and accessibility**

Phase 1 — Tampa Bay Explorer (Current focus)

### Core Map
- Interactive map centered on **Tampa Bay**
- **OSM Basemap** + **OpenSeaMap seamarks** for buoy & light symbols
- Map is **bounded** so navigation stays within Tampa Bay (no overload / no lag)

### Layers to Include
| Layer | Description | Source |
|------|-------------|--------|
| Channels | Navigable water routes | NOAA ENC (converted to GeoJSON) |
| Aids to Navigation (AtoN) | Buoys, beacons, markers | NOAA ENC / OpenSeaMap |
| Seagrass & Manatee Zones | Wildlife-sensitive areas | MarineCadastre / State of FL |
| Bridges, Landmarks | Orientation points | OSM |

### Interaction Features
- **Hover**: Name or simple description appears gently
- **Click**: Shows info + optional “See photos” / “Learn more”
- **No pop-ups that flash, bounce, or auto-play**

### Accessibility & Sensory Design
- **Three viewing modes**:
  1. **Level 1 — Simple** (minimal labels, soft colors)
  2. **Level 2 — Explorer** (more details, seamarks)
  3. **Level 3 — Detail** (channels, depths, wildlife zones)
- Large touch targets
- Adjustable text size
- Optional dyslexia-friendly font
- No sudden motion or visual noise



 
 Phase 2 — Learning Library (Optional Add-Ons Later)

A curated panel of **kid-safe discovery links**, such as:

| Resource | Topic |
|---------|-------|
| Smithsonian Ocean Portal (Kids) | Marine animals & ocean exploration |
| NOAA Kids | Weather, tides, coasts, and ocean science |
| National Park Service Junior Ranger (Coastal) | Habitat + stewardship activities |
| Local Public Library Marine Books | Printable reading lists |
| Virtual Harbor & Ship Cameras | Real world observation practice |

These won’t appear all at once — they’ll be carefully chosen, quiet, and easy to explore.

Future Direction (if needed)
- Expand from Tampa Bay → Gulf of Mexico → **Florida coast**
- Convert large datasets into **PMTiles vector tiles** for smooth performance
- Optional “Ship Trails” layer using archived AIS data (educational, privacy-safe)

---

## 🤝 Open Project
NOLE is **open-source** and built for shared learning.  
As development continues, a license and contributor guidelines will be added.

---

## ❤️ Thank You
To everyone who supports kids who learn deeply, differently, and with their whole hearts.
