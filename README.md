# 🩺 Kitui Vaccine Dashboard

[![GitHub stars](https://img.shields.io/github/stars/AdepoEO/kitui-vaccine-dashboard?style=social)](https://github.com/AdepoEO/kitui-vaccine-dashboard)
[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)
[![YOLOv10n](https://img.shields.io/badge/YOLOv10n-3.8MB-green.svg)](https://github.com/ultralytics/ultralytics)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

**Real-time YOLOv10n vaccine vial verification dashboard** for Kitui Health Centre by [AdepoEO](https://github.com/AdepoEO). Features field pilot simulation, provenance tracking, GPS validation, and edge-deployed computer vision pipeline achieving **92% mAP** with **25ms Android inference**.

![Dashboard Screenshot](screenshots/dashboard.png)

## 🚀 Features

- **YOLOv10n Edge Detection** (3.8MB model) - Optimized for Android deployment
- **Real-time Field Simulation** - 42 days Kitui County vaccine verification data
- **Provenance Tracking** - SHA256 hash verification for supply chain integrity
- **GPS Location Validation** - Geolocated field verifications
- **Live Dashboard** - Responsive metrics, charts, and recent verifications table
- **Fitzpatrick I-VI Bias Audited** - Skin tone inclusive computer vision
- **Production Ready** - Q2 2026 Kitui Health Centre deployment pipeline

## 🎯 Quick Demo

```bash
# Clone AdepoEO's repo
git clone https://github.com/AdepoEO/kitui-vaccine-dashboard
cd kitui-vaccine-dashboard
pip install -r requirements.txt
jupyter notebook dashboard.ipynb
