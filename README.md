# HYSP GeoViewer (HyGV)

HYSP GeoViewer (HyGV) is an interactive visualization tool for atmospheric science applications.

It provides a unified environment for exploring atmospheric model outputs, satellite products, and observational datasets through an intuitive graphical interface.

---

## Beta Version

This repository hosts the **private beta** releases of HYSP GeoViewer.

The software is under active development. Features, file formats, and user interfaces may change between releases.

---

## Main Features

- Interactive map visualization
- Multiple IMAGE and OBS layers
- Raster and contour visualization
- Time navigation
- Bounding-box (BBOX) analysis
- Time-series generation
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

# Downloads

Download the latest beta release from the **Releases** page.

Each release contains:

| File | Description |
|------|-------------|
| **HyGV-*-Windows.zip** | Stand-alone Windows executable (recommended for most users) |
| **HyGV-*-Python.zip** | Compiled Python (.pyc) version for users with Python installed |
| **HyGV-*-Data.zip** | Sample datasets |

---

# Installation

## Option 1 (Recommended): Windows Executable

1. Download **HyGV-*-Windows.zip**.
2. Extract the ZIP file.
3. Run

```
HyGV.exe
```

No Python installation is required.

---

## Option 2: Compiled Python Version (.pyc)

The Python package contains **compiled Python bytecode (.pyc)** rather than Python source code.

### Requirements

- Python 3.13
- Packages listed in `requirements.txt`

### Create a virtual environment

Windows

```powershell
py -3.13 -m venv .venv
.venv\Scripts\activate
```

macOS / Linux

```bash
python3.13 -m venv .venv
source .venv/bin/activate
```

### Install required packages

```bash
python -m pip install --upgrade pip
pip install -r requirements.txt
```

### Run HyGV

Use the launcher included in the Python package.

Refer to the documentation included with the package for the appropriate startup command.

---

# Reporting Issues

Please report problems through **GitHub Issues**.

When reporting a bug, include

- HyGV version
- Operating system
- Python version (if applicable)
- Steps to reproduce
- Complete error message
- Screenshot (if available)

---

# Citation

If HYSP GeoViewer contributes to published research, please cite the appropriate publication once available.

---

# Author

Designed by

**Hyun Cheol Kim**

---

# Development Status

**Private Beta**

Feedback and bug reports are welcome.
