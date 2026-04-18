# RS Indices Calculator 🛰️

A QGIS plugin designed to easily calculate popular Remote Sensing spectral indices used in vegetation, water, built-up, and ecological analyses. 

## ✨ Features
* **10 Built-in Indices:** Calculates NDVI, EVI, SAVI, NDWI, MNDWI, NDBI, NDBSI, UI, BSI, and WET.
* **Quick Setup:** Features an "Auto-fill" button for Landsat 8/9 band configurations to speed up your workflow.
* **Manual Assignment:** Flexible manual band assignment supporting Sentinel-2 and other multispectral sensors.
* **Instant Context:** Displays the mathematical formula, required bands, and expected value ranges directly in the UI before you run the calculation.
* **Auto-Load:** Automatically loads the calculated index raster back into your QGIS workspace.

## 📥 Installation Guide

Since this plugin is currently in its independent release phase, you can easily install it directly from a ZIP file using the built-in QGIS Plugin Manager.

1. **Download the Plugin:**
   * Go to the [Releases page](../../releases) of this repository.
   * Download the latest `rs_indices_calculator.zip` file. *(Do not unzip it)*.

2. **Install in QGIS:**
   * Open QGIS (Version 3.0 or higher).
   * From the top menu, go to **Plugins** > **Manage and Install Plugins...**
   * Select the **Install from ZIP** tab on the left panel.
   * Click the `...` button and browse to where you downloaded `rs_indices_calculator.zip`.
   * Click **Install Plugin**.
   * The plugin should now be available in your QGIS toolbar or under the **Plugins** menu!

## 🚀 How to Use

1. **Assign Bands (Tab 1):** Select your multi-band raster layer. If you are using Landsat 8 or 9, simply click the `Auto-fill Landsat 8/9 bands` button. Otherwise, manually assign the specific raster layers to their corresponding color/wavelength roles (Blue, Green, Red, NIR, SWIR1, SWIR2).
2. **Select Index & Run (Tab 2):** Choose the index you want to calculate from the dropdown menu. Choose your desired output `.tif` file path, ensure "Load result into QGIS" is set to Yes, and click **Calculate Index**.

## 🐛 Issues & Feedback
If you encounter any bugs or have feature requests, please open an issue in the [Issue Tracker](../../issues).

## 👤 Author
**Hiron Khandaker**
* Email: khandakerhiron@gmail.com
