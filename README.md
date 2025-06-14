1. **Project Title + Tagline**
   Uncovering the Forgotten Temple: A Digital Archaeology Quest in the Amazon Rainforest

2. **Project Overview**
   This project aims to identify a hidden archaeological site deep in the Amazon rainforest using open-source satellite imagery, Lidar, and vegetation data. Our goal is to uncover what may be a forgotten temple or village structure          buried under the forest canopy.

3. **Objectives / Problem Statement**
    Detect man-made geometric shapes hidden under dense trees.
    Combine multiple open data sources to support your claim.
    Provide a reproducible method that can be reused to discover more sites.
 
4. **Tools & Technologies Used**
    Mention what tools and libraries you used.
   - Python, Jupyter Notebook
   - Google Earth Engine
   - Rasterio, Geopandas
   - QGIS for map overlays
   - Sentinel-2 and Lidar from ICESat-2

5. **Data Sources**
   [Sentinel-2 Imagery](https://scihub.copernicus.eu/)
   [ICESat-2 Lidar (ATL08)](https://nsidc.org/data/ATL08)

6. **Key Results / Findings**
   Found rectangular raised structures not natural in shape
   NDVI showed inconsistent vegetation recovery in that area
   Overlap between elevation and spectral changes = potential ruins!

7. **Visuals**
   [Site Detection Map](images/temple_site.png)

8. **How to Run the Code**
   1. Clone this repo
   2. Install requirements using `pip install -r requirements.txt`
   3. Open the notebook in `notebooks/temple_detection.ipynb`

 9. **Submission Info / Track**
    Submitted for: Kaggle OpenAI to Z Challenge (Track: Exploration & Discovery)

10. **License + Acknowledgement**
    thanks to Kaggle, OpenAI, and data providers. And add MIT license if needed.


