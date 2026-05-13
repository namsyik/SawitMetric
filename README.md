# SawitMetric QGIS Plugin

Deep Learning-based Oil Palm Detection & Counting for sustainable rural development. 
This project implements the **OPTIMAL-IPB** approach for precision spatial information systems.

## 🚀 Objectives
- **Precise Detection:** Using YOLOv8 to identify palm crowns in high-res imagery.
- **Contrast Adaptation:** Integrated CLAHE preprocessing to handle varied satellite imagery.
- **Scientific Metrics:** Estimating palm age and yield based on Canopy Projection Area (CPA).
- **RTRW Alignment:** Outputting UTM (EPSG:32647) geometries for spatial plan compliance.

## 🛠️ Installation & Setup

### 1. Prerequisites
- **QGIS 3.40**
- **Python 3.12**
- **Dependencies:**
  ```bash
  pip install ultralytics opencv-python numpy
