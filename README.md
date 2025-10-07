# 🌍 Generic Google Earth Engine Exporter

A flexible Colab/Python script for downloading multiple Earth Engine datasets  
either as gridded data (e.g., by state) or at point locations from a CSV file.

## Features
- Supports multiple datasets (Daymet, ERA5-Land, etc.)
- **GRID mode:** downloads data at each dataset's original resolution
- **POINTS mode:** samples exact coordinate locations from a CSV
- Exports results as CSV files to your Google Drive

## Usage
1. Open the notebook in [Google Colab](https://colab.research.google.com)
2. Configure `MODE`, `START_DATE`, datasets, and other parameters.
3. Run all cells — exports will appear in your Google Drive folder.


## Notes
- For GRID mode, the script uses each dataset’s **native resolution**.
- For POINTS mode, the user-defined scale is ignored.
- Requires an active [Google Earth Engine](https://earthengine.google.com/) account.
