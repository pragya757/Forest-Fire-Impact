# Forest-Fire-Impact
Geospatial and data enthusiast working with remote sensing, GIS, and Python to analyze environmental patterns. Interested in satellite imagery, spatial modeling, and building reproducible workflows for real-world applications.

📌 Overview
This project analyzes the impact of forest fires on vegetation using multi‑temporal satellite data. By integrating burn severity, thermal stress, and vegetation indices, the study evaluates how fire events influence ecosystem health over time through a coupled analytical framework.

🎯 Objectives
Analyze vegetation changes before, during, and after fire events

Compute burn severity using spectral indices

Evaluate land surface temperature variations

Model vegetation response to fire impact

Perform statistical analysis to understand relationships

🗺️ Study Area
Similipal Biosphere Reserve — a fire‑prone forest region selected due to its recurring seasonal wildfire events and ecological importance.

🛰️ Data Sources
Sentinel‑2 Surface Reflectance imagery

MODIS Land Surface Temperature (LST)

Google Earth Engine for satellite data processing

⚙️ Methodology

1️⃣ Data Acquisition
Multi‑date satellite images were collected for:

Pre‑fire period

During fire period

Post‑fire period

2️⃣ Pre‑processing
Cloud filtering

Use of atmospherically corrected datasets

3️⃣ Index Computation
NDVI → Vegetation health

BRI → Burn severity

LST → Thermal stress

4️⃣ Multi‑Temporal Analysis
Comparison of indices across time periods to detect vegetation changes caused by fire.

5️⃣ Coupled Impact Modeling
Vegetation response analyzed as a function of burn severity and temperature.

6️⃣ Statistical Analysis
Correlation and regression used to quantify relationships between indices.

📊 Results
Increase in burn severity and temperature observed during fire

Significant decrease in NDVI indicating vegetation stress

Post‑fire partial recovery observed

Strong inverse relationship between NDVI and fire indicators

🛠️ Tools & Technologies
Google Earth Engine

Python (Rasterio, NumPy, Pandas, Matplotlib, SciPy)

Jupyter Notebook

Visual Studio Code

Remote sensing & GIS concepts

🧩 Environment Setup
All analyses were performed using a dedicated Conda environment to ensure reproducibility and avoid dependency conflicts. The environment was managed using Anaconda and executed through Jupyter Notebook in Visual Studio Code.

🐍 Creating Conda Environment
```bash
conda create -n fire_project python=3.10
conda activate fire_project
```
📦 Installing Required Libraries
```bash
conda install -c conda-forge rasterio numpy pandas matplotlib scipy
```
📓 Setting up Jupyter Kernel
```bash
python -m ipykernel install --user --name fire_project --display-name "fire_project"
```
💻 Running in VS Code
Open project folder in Visual Studio Code

Install Python and Jupyter extensions

Select interpreter → Python 3.10 (fire_project)

Open notebook (.ipynb)

Select kernel → fire_project

Run all cells

📂 Project Structure
```bash
Similipal_Project/
├── Pre_Fire/
├── During_Fire/
├── Post_Fire/
├── analysis.ipynb
└── README.md
```
▶️ How to Run
Activate conda environment

Open notebook in VS Code

Run cells sequentially

Results (tables & graphs) will be generated

📁 Data Availability
All supplementary datasets including GeoTIFF files, processed outputs, maps, and figures are available in the Google Drive repository below:

🔗 https://drive.google.com/drive/folders/1oaJ3xk4oBPa8LQ_vN4q3tLmBwCY1IbK5?usp=sharing

This folder contains:

Pre‑fire, during‑fire, and post‑fire GeoTIFF datasets

Generated maps and visualizations

Supporting images used in analysis

Additional project outputs

📈 Key Contribution
This project demonstrates a coupled analytical framework integrating spectral and thermal indicators to quantify vegetation response to wildfire events using multi‑sensor satellite data.

🔮 Future Scope
Extend analysis to multiple years

Include additional fire indices

Apply machine learning models for prediction

👩‍💻 Author
Geospatial Intelligence student passionate about remote sensing, spatial analysis, and environmental monitoring.

