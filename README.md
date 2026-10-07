# GIS with Python in Google Colab
### Vector GIS · Spatial Analysis · Raster GIS · Terrain Analysis

[![Python](https://img.shields.io/badge/Python-3.x-blue.svg)](https://www.python.org/)
[![Google Colab](https://img.shields.io/badge/Google-Colab-orange.svg)](https://colab.research.google.com/)
[![GeoPandas](https://img.shields.io/badge/GeoPandas-Vector%20GIS-139C5A.svg)](https://geopandas.org/)
[![Rasterio](https://img.shields.io/badge/Rasterio-Raster%20GIS-8A2BE2.svg)](https://rasterio.readthedocs.io/)
[![Folium](https://img.shields.io/badge/Folium-Web%20GIS-2E8B57.svg)](https://python-visualization.github.io/folium/)
[![Course](https://img.shields.io/badge/Course-10%20Notebooks-blueviolet.svg)](#course-roadmap)

A progressive, hands-on GIS course using **Python and Google Colab**, designed to build spatial thinking from basic vector GIS to raster interpolation and terrain analysis using real geospatial datasets from Thailand.

ชุดบทเรียนนี้ออกแบบให้นิสิตเรียนรู้ GIS ด้วย Python แบบเป็นลำดับ ตั้งแต่การอ่านข้อมูล Vector, CRS, การวัดระยะและพื้นที่, spatial query, spatial join, buffer, overlay, spatial statistics ไปจนถึง raster interpolation, DEM และ terrain analysis โดยใช้ข้อมูลจริงของประเทศไทย

---

## Quick Start

The easiest way to use this repository is through **Google Colab**. No local GIS installation is required.

1. Start with **Notebook 01**.
2. Click **Open in Colab**.
3. Run cells from top to bottom.
4. Inspect the outputs, maps, and tables.
5. Complete the Concept Check and Exercises.
6. Continue in numerical order for the full learning pathway.

### Start here

- [Notebook 01 on GitHub](https://github.com/nattaponm/Teach_GIS_Python_Colab/blob/main/01_Python_GIS_Fundamentals_World_Map.ipynb)
- [Open Notebook 01 in Google Colab](https://colab.research.google.com/github/nattaponm/Teach_GIS_Python_Colab/blob/main/01_Python_GIS_Fundamentals_World_Map.ipynb)

---

## About This Course

This repository is designed as a **progressive GIS learning pathway**, not as a collection of independent code examples.

The main learning philosophy is:

```text
Inspect
↓
Map
↓
Query
↓
Measure
↓
Relate
↓
Analyze
↓
Interpolate
↓
Model Terrain
↓
Communicate
```

The notebooks gradually move from simple inspection and mapping toward analytical GIS workflows that combine vector, raster, statistics, and interactive Web GIS.

---

## Who Is This For?

The materials are suitable for:

- Undergraduate students in Years 3–4
- MSc students in Years 1–2
- Environmental Science
- Geography
- Geoinformatics / GIS
- Natural Resources
- Hydrology and related environmental disciplines

### Recommended background

Basic GIS concepts are helpful, but advanced programming experience is **not required**.

The notebooks are designed so that each new concept is introduced with small, readable Python examples before moving to analysis.

---

## What Students Will Learn

By the end of the course, students should be able to:

- Read and inspect vector and raster GIS data
- Understand coordinate reference systems (CRS), EPSG codes, projections, and reprojection
- Perform attribute and spatial queries
- Work with administrative hierarchies: Province → District → Tambon
- Use Point-in-Polygon and Spatial Join
- Calculate distance, area, count, and density
- Build buffers and concentric rings
- Use dissolve, clip, intersection, and difference
- Understand spatial autocorrelation and Moran's I
- Convert point observations to raster surfaces
- Compare IDW, Thin Plate Spline, and Trend Surface interpolation
- Perform raster-to-polygon zonal statistics
- Inspect and analyze Digital Elevation Models (DEM)
- Derive slope, hillshade, and aspect
- Build publication-quality static maps
- Build interactive Folium Web GIS maps
- Export GeoPackage, Shapefile ZIP, CSV, GeoTIFF, PNG, and HTML outputs

---

# Course Roadmap

## Stage 1 — GIS Foundations

**Notebook 01–02**

```text
GIS Data
↓
CRS
↓
Projection
↓
Distance / Area / Scale
```

Main question:

> What is GIS data, and how can we measure it correctly?

---

## Stage 2 — Vector GIS & Spatial Relationships

**Notebook 03–06**

```text
Province
↓
District
↓
Tambon
↓
Village Point
```

Main question:

> How are vector layers organized, related, queried, and summarized?

---

## Stage 3 — Spatial Analysis

**Notebook 07–08**

```text
Distance
↓
Buffer
↓
Concentric Rings
↓
Overlay
↓
Spatial Statistics
```

Main question:

> How do spatial patterns change with distance, and how can we test them analytically?

---

## Stage 4 — Raster GIS & Terrain Analysis

**Notebook 09–10**

```text
Point
↓
Interpolation
↓
Raster
↓
Zonal Statistics
↓
DEM
↓
Terrain Derivatives
```

Main question:

> How can point observations become continuous surfaces, and how can elevation be transformed into terrain information?

---

# Notebooks

| No. | Notebook | Main Question | Core Concepts | Colab |
|---:|---|---|---|---|
| 01 | [Python GIS Fundamentals & World Map](https://github.com/nattaponm/Teach_GIS_Python_Colab/blob/main/01_Python_GIS_Fundamentals_World_Map.ipynb) | What is GIS data in Python? | GeoDataFrame, vector geometry, attributes, query, static & interactive mapping | [Open in Colab](https://colab.research.google.com/github/nattaponm/Teach_GIS_Python_Colab/blob/main/01_Python_GIS_Fundamentals_World_Map.ipynb) |
| 02 | [CRS, Projection, Distance, Area & Map Scale](https://github.com/nattaponm/Teach_GIS_Python_Colab/blob/main/02_CRS_Projection_Distance_Area_and_Map_Scale.ipynb) | Can I measure spatial data correctly? | CRS, EPSG, reprojection, distance, area, map scale | [Open in Colab](https://colab.research.google.com/github/nattaponm/Teach_GIS_Python_Colab/blob/main/02_CRS_Projection_Distance_Area_and_Map_Scale.ipynb) |
| 03 | [Thailand Province Area Statistics & Choropleth](https://github.com/nattaponm/Teach_GIS_Python_Colab/blob/main/03_Thailand_Province_Area_Statistics_and_Choropleth.ipynb) | What spatial patterns can I summarize? | Area statistics, classification, choropleth mapping | [Open in Colab](https://colab.research.google.com/github/nattaponm/Teach_GIS_Python_Colab/blob/main/03_Thailand_Province_Area_Statistics_and_Choropleth.ipynb) |
| 04 | [District Hierarchy & Spatial Query](https://github.com/nattaponm/Teach_GIS_Python_Colab/blob/main/04_Thailand_District_Hierarchy_and_Spatial_Query.ipynb) | How are administrative layers spatially related? | Hierarchy, attribute query, spatial relationship, spatial join, QA/QC | [Open in Colab](https://colab.research.google.com/github/nattaponm/Teach_GIS_Python_Colab/blob/main/04_Thailand_District_Hierarchy_and_Spatial_Query.ipynb) |
| 05 | [Tambon Detailed Polygon Analysis](https://github.com/nattaponm/Teach_GIS_Python_Colab/blob/main/05_Thailand_Tambon_Detailed_Polygon_Analysis.ipynb) | How do I manage detailed polygons? | ADM3 polygons, hierarchy, area, web GIS, detailed cartography | [Open in Colab](https://colab.research.google.com/github/nattaponm/Teach_GIS_Python_Colab/blob/main/05_Thailand_Tambon_Detailed_Polygon_Analysis.ipynb) |
| 06 | [Village Points, Spatial Join & Density](https://github.com/nattaponm/Teach_GIS_Python_Colab/blob/main/06_Thailand_Village_Point_Spatial_Join_and_Density.ipynb) | How do points become spatial information? | Point-in-polygon, spatial join, count, density | [Open in Colab](https://colab.research.google.com/github/nattaponm/Teach_GIS_Python_Colab/blob/main/06_Thailand_Village_Point_Spatial_Join_and_Density.ipynb) |
| 07 | [Distance, Buffer & Concentric-Ring Analysis](https://github.com/nattaponm/Teach_GIS_Python_Colab/blob/main/07_Distance_Buffer_and_Concentric_Ring_Analysis.ipynb) | How does spatial pattern change with distance? | Centroid, distance, buffers, concentric rings, cumulative counts | [Open in Colab](https://colab.research.google.com/github/nattaponm/Teach_GIS_Python_Colab/blob/main/07_Distance_Buffer_and_Concentric_Ring_Analysis.ipynb) |
| 08 | [Clip, Overlay, Dissolve & Spatial Statistics](https://github.com/nattaponm/Teach_GIS_Python_Colab/blob/main/08_Clip_Overlay_Dissolve_and_Spatial_Statistics.ipynb) | How do I integrate layers and test spatial pattern? | Dissolve, clip, intersection, difference, Moran's I, Local Moran | [Open in Colab](https://colab.research.google.com/github/nattaponm/Teach_GIS_Python_Colab/blob/main/08_Clip_Overlay_Dissolve_and_Spatial_Statistics.ipynb) |
| 09 | [Village Point → Raster Spatial Interpolation](https://github.com/nattaponm/Teach_GIS_Python_Colab/blob/main/09_Village_Point_to_Raster_Spatial_Interpolation.ipynb) | How can point observations become a continuous raster? | IDW, TPS, trend surface, raster resolution, zonal statistics | [Open in Colab](https://colab.research.google.com/github/nattaponm/Teach_GIS_Python_Colab/blob/main/09_Village_Point_to_Raster_Spatial_Interpolation.ipynb) |
| 10 | [DEM & Terrain Analysis: Phitsanulok](https://github.com/nattaponm/Teach_GIS_Python_Colab/blob/main/10_DEM_Terrain_Analysis_Phitsanulok.ipynb) | How can elevation become terrain information? | DEM, terrain profile, slope, hillshade, aspect, zonal statistics | [Open in Colab](https://colab.research.google.com/github/nattaponm/Teach_GIS_Python_Colab/blob/main/10_DEM_Terrain_Analysis_Phitsanulok.ipynb) |

---

# Concept Progression

The 10 notebooks follow a deliberate sequence of scientific questions:

```text
01  What is GIS data?

02  Can I measure it correctly?

03  What spatial patterns can I summarize?

04  How are layers spatially related?

05  How do I manage detailed polygons?

06  How do points become spatial information?

07  How does spatial pattern change with distance?

08  How do I integrate layers and test spatial pattern?

09  How can point observations become a continuous raster?

10  How can elevation become terrain information?
```

---

# Datasets

The course uses real GIS datasets for Thailand and global examples.

## Vector datasets

| Dataset | Geometry | Main Use |
|---|---|---|
| World Countries | Polygon | Introductory global GIS |
| Thailand ADM1 — Province | Polygon | Province-level analysis, choropleth, masks |
| Thailand ADM2 — District | Polygon | Administrative hierarchy, distance analysis |
| Thailand ADM3 — Tambon | Polygon | Detailed polygon analysis, zonal statistics |
| Thailand Village Points | Point | Spatial join, density, distance, interpolation |

## Raster datasets

| Dataset | Type | Main Use |
|---|---|---|
| `data/wrl_dem_phk1.tif` | SRTM DEM | Elevation and terrain analysis in Notebook 10 |

The notebooks also demonstrate how to download supporting GIS datasets directly from GitHub so that the workflow can be reproduced in Google Colab.

---

# Python GIS Stack

| Library | Main Role |
|---|---|
| **GeoPandas** | Vector GIS |
| **Shapely** | Geometry operations |
| **PyProj** | CRS and projection |
| **Pandas / NumPy** | Data analysis |
| **Matplotlib** | Static and publication-quality maps |
| **Folium** | Interactive Web GIS |
| **Rasterio** | Raster GIS and GeoTIFF |
| **SciPy** | Spatial interpolation and numerical methods |
| **PySAL / ESDA** | Spatial statistics |
| **xyzservices** | Web basemap providers |

---

# Important GIS Principles

This course emphasizes reasoning, not only code.

> **Correct-looking geometry ≠ correct measurement**

> **One CRS does not solve every GIS problem**

> **Attribute relationship ≠ Spatial relationship**

> **Basemap ≠ Analytical data**

> **Count ≠ Density**

> **Name ≠ Unique Identifier**

> **Euclidean distance ≠ Road distance ≠ Travel time**

> **Distance-defined study area ≠ Administrative boundary**

> **Numerator and denominator must refer to the same spatial support**

> **A visual cluster ≠ statistically demonstrated spatial autocorrelation**

> **Cell size ≠ Search radius**

> **Higher spatial resolution ≠ automatically better**

> **Smoothest interpolation surface ≠ most accurate interpolation**

> **DEM value = elevation, not terrain shape by itself**

> **Hillshade is visualization, not elevation**

> **Aspect is circular data**

> **A map is an analytical argument, not merely decoration**

---

# Typical Notebook Structure

Most notebooks follow a similar teaching pattern:

```text
Concept
↓
Small Python code
↓
Inspect the result
↓
Map the data
↓
Ask a GIS question
↓
Analyze
↓
Interpret
↓
Export
↓
Exercise
```

The notebooks are intentionally broken into small steps so that students can connect the code to the GIS concept being taught.

---

# Mapping Approach

## Static Maps

Static maps are used for scientific interpretation and publication-style outputs.

Typical elements include:

- Clear title
- Appropriate legend or colorbar
- North arrow when useful
- Scale bar when useful
- Correct CRS and units
- Readable labels
- 300 dpi export

## Interactive Maps

Folium maps are used for exploratory GIS and layer comparison.

Typical elements include:

- OpenTopoMap
- Esri World Topographic
- Esri World Imagery
- Operational vector layers
- Tooltip / popup information
- LayerControl
- Choropleth layers

---

# Exercises

Most notebooks contain three levels of practice:

### Concept Check

Short questions to confirm understanding of the GIS concept.

### Core Exercise

A practical task using the same workflow with modified parameters or another area.

### MSc Challenge

An optional advanced task focused on sensitivity analysis, validation, spatial statistics, or methodological interpretation.

Examples include:

- CRS sensitivity
- Count vs density interpretation
- Buffer interval sensitivity
- Queen vs Rook vs KNN spatial weights
- Interpolation validation
- DEM resolution sensitivity

---

# Outputs

Depending on the notebook, students learn to export:

```text
PNG
CSV
GeoPackage
Shapefile ZIP
GeoTIFF
HTML
```

Typical output organization:

```text
outputs/
├── maps/
├── vectors/
├── rasters/
├── tables/
└── html/
```

---

# Repository Structure

```text
Teach_GIS_Python_Colab/
│
├── data/
│   └── wrl_dem_phk1.tif
│
├── 01_Python_GIS_Fundamentals_World_Map.ipynb
├── 02_CRS_Projection_Distance_Area_and_Map_Scale.ipynb
├── 03_Thailand_Province_Area_Statistics_and_Choropleth.ipynb
├── 04_Thailand_District_Hierarchy_and_Spatial_Query.ipynb
├── 05_Thailand_Tambon_Detailed_Polygon_Analysis.ipynb
├── 06_Thailand_Village_Point_Spatial_Join_and_Density.ipynb
├── 07_Distance_Buffer_and_Concentric_Ring_Analysis.ipynb
├── 08_Clip_Overlay_Dissolve_and_Spatial_Statistics.ipynb
├── 09_Village_Point_to_Raster_Spatial_Interpolation.ipynb
├── 10_DEM_Terrain_Analysis_Phitsanulok.ipynb
│
└── README.md
```

---

# Recommended Learning Order

For the full course, run the notebooks in numerical order.

If you already know basic GIS and Python:

- Start with **02** for CRS and measurement
- Start with **04** for spatial relationships and spatial join
- Start with **07** for proximity analysis
- Start with **09** for raster interpolation
- Start with **10** for DEM and terrain analysis

However, the strongest learning progression is still:

```text
01 → 02 → 03 → 04 → 05 → 06 → 07 → 08 → 09 → 10
```

---

# Teaching Philosophy

The objective is not only to make the code run.

Students should be able to explain:

- Why a CRS is appropriate
- Why a spatial operation answers a particular question
- Why normalization changes interpretation
- Why scale and resolution matter
- Why visual patterns require statistical caution
- Why raster and vector representations answer different kinds of questions
- Why a beautiful map is not automatically a scientifically correct map

---

# Author

**Assoc. Prof. Dr. Nattapon Mahavik**  
Department of Natural Resources and Environment  
Faculty of Agriculture, Natural Resources and Environment  
Naresuan University, Thailand

Teaching and research interests include GIS, remote sensing, weather radar, spatial analysis, environmental applications, and geospatial programming.

---

# Use of This Repository

These materials are intended for:

- Classroom teaching
- Laboratory exercises
- Self-study
- GIS / Python workshops
- Adaptation to other environmental datasets and study areas

Students are encouraged to modify the study area, datasets, parameters, and map design after understanding the workflow.

---

# Acknowledgement

This repository uses open-source Python geospatial libraries and publicly available geospatial datasets for educational purposes.

Users should consult the original data providers and software documentation when applying the workflows to research or operational applications.

---

## Final Learning Path

```text
Vector GIS
↓
CRS & Measurement
↓
Spatial Relationships
↓
Spatial Analysis
↓
Spatial Statistics
↓
Raster Interpolation
↓
DEM & Terrain Analysis
↓
Scientific Mapping & Communication
```

> **Learn the GIS concept first. Use Python to make the analysis reproducible.**
