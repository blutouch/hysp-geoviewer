# HYSP GeoViewer (HyGV)

HYSP GeoViewer (HyGV) is an interactive visualization tool for atmospheric science applications.

It provides a unified environment for exploring model outputs, satellite products, and observational datasets with a simple graphical interface.

---

## Beta Version

This repository contains a **beta release** of HYSP GeoViewer.

The software is under active development. Features, file formats, and user interfaces may change without notice.

---

## Main Features

- Interactive map display
- Multiple IMAGE and OBS layers
- Raster and contour visualization
- Time navigation
- Bounding-box (BBOX) analysis
- Time series generation
- Scatter plots
- Project management
- Case management
- Archive browsing
- Figure capture

Supported data include

- HYSPLIT
- CMAQ
- Satellite products
- Surface observations
- NetCDF
- Additional atmospheric datasets

---

## Downloads

The latest beta release contains:

| File | Description |
|------|-------------|
| **HyGV-YYMMDD-NNN-Windows.zip** | Stand-alone Windows executable |
| **HyGV-YYMMDD-NNN-Python.zip** | Python version |
| **HyGV-YYMMDD-NNN-Data.zip** | Sample datasets |

---

## System Requirements

### Windows

- Windows 10 or newer

Executable version:

- No Python installation required.

Python version:

- Python 3.13 recommended

---

## Installation

### Windows Executable

1. Download the latest Windows package.
2. Extract the ZIP file.
3. Run

```
HyGV.exe
```

---

### Python Version

Create a virtual environment

```bash
python -m venv .venv
```

Activate

Windows

```powershell
.venv\Scripts\activate
```

macOS/Linux

```bash
source .venv/bin/activate
```

Install packages

```bash
pip install -r requirements.txt
```

Run

```bash
python hysp_geoviewer.py
```

---

## Reporting Issues

Please use GitHub Issues.

Include

- HyGV version
- Operating system
- Python version (if applicable)
- Steps to reproduce
- Error message
- Screenshot (if available)

---

## Citation

If HyGV contributes to published research, please cite the appropriate publication once available.

---

## Author

Designed by

**Hyun Cheol Kim**

---

## Development

Current status

**Private Beta**
