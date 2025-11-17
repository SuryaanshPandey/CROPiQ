# CROPiQ — Crop Intelligence & Quantification Platform

**Smart India Hackathon 2025 — Team Nyxoraa (Team ID: 64431)**

**Problem:** Farm-level yield estimation using very-high spatial resolution data and robust crop models.

## Project structure
CROPiQ/
├── backend/ # FastAPI backend
├── frontend/ # React + Mapbox dashboard
├── data/
│ ├── raw/ # raw satellite / drone data (do not commit large files)
│ ├── processed/ # processed NDVI/tiles/GeoTIFFs
│ └── models/ # model artifacts for deployment
├── ml/
│ ├── notebooks/
│ ├── scripts/
│ └── models/
├── remote_sensing/
│ ├── sentinel/
│ ├── ndvi_outputs/
│ └── hotspot_outputs/
└── docs/
├── architecture/
├── design/
└── SIH_pitch/
