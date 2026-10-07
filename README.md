# GIS with Python in Google Colab
### Vector GIS · Spatial Analysis · Raster GIS · Terrain Analysis

[![Python](https://img.shields.io/badge/Python-3.x-blue.svg)](https://www.python.org/)
[![Google Colab](https://img.shields.io/badge/Google-Colab-orange.svg)](https://colab.research.google.com/)
[![GeoPandas](https://img.shields.io/badge/GeoPandas-Vector%20GIS-139C5A.svg)](https://geopandas.org/)
[![Rasterio](https://img.shields.io/badge/Rasterio-Raster%20GIS-8A2BE2.svg)](https://rasterio.readthedocs.io/)
[![Folium](https://img.shields.io/badge/Folium-Web%20GIS-2E8B57.svg)](https://python-visualization.github.io/folium/)
[![Course](https://img.shields.io/badge/Course-10%20Notebooks-blueviolet.svg)](#เส้นทางการเรียนรู้)

ชุดบทเรียน **GIS with Python in Google Colab** สำหรับเรียนรู้ตั้งแต่พื้นฐาน `Vector GIS`, `CRS`, การวัดระยะและพื้นที่, `Spatial Query`, `Spatial Join`, `Buffer`, `Overlay`, `Spatial Statistics` ไปจนถึง `Raster Interpolation`, `DEM` และ `Terrain Analysis` โดยใช้ข้อมูลจริงของประเทศไทย

เนื้อหาถูกออกแบบให้เรียนต่อเนื่องจากง่ายไปยาก เหมาะสำหรับนิสิตที่ต้องการเข้าใจทั้งแนวคิด GIS และการเขียน Python เพื่อทำงานวิเคราะห์เชิงพื้นที่อย่างเป็นระบบและทำซ้ำได้

---

## เริ่มต้นใช้งานอย่างรวดเร็ว

วิธีที่ง่ายที่สุดคือเปิด Notebook ผ่าน **Google Colab** โดยไม่จำเป็นต้องติดตั้ง GIS software หรือ Python environment ในเครื่อง

1. เริ่มจาก **Notebook 01**
2. กด **Open in Colab**
3. รัน cell จากบนลงล่าง
4. ตรวจผลลัพธ์ ตาราง และแผนที่ที่ได้
5. ทำ `Concept Check` และ `Exercise`
6. เรียนต่อไปตามลำดับหมายเลข Notebook

### เริ่มจาก Notebook 01

- [เปิด Notebook 01 บน GitHub](https://github.com/nattaponm/Teach_GIS_Python_Colab/blob/main/01_Python_GIS_Fundamentals_World_Map.ipynb)
- [เปิด Notebook 01 ใน Google Colab](https://colab.research.google.com/github/nattaponm/Teach_GIS_Python_Colab/blob/main/01_Python_GIS_Fundamentals_World_Map.ipynb)

---

## เกี่ยวกับชุดบทเรียนนี้

Repository นี้ถูกออกแบบเป็น **เส้นทางการเรียนรู้ GIS แบบต่อเนื่อง** ไม่ใช่เพียงการรวมตัวอย่าง code แยกกัน

แนวคิดหลักของการเรียนคือ

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

นิสิตจะเริ่มจากการตรวจข้อมูลและทำแผนที่ ก่อนค่อย ๆ เพิ่มความสามารถในการวัด วิเคราะห์ เชื่อมโยง layer สร้าง raster และวิเคราะห์ภูมิประเทศ

---

## เหมาะสำหรับใคร

ชุดบทเรียนนี้เหมาะสำหรับ

- นิสิตปริญญาตรีชั้นปีที่ 3–4
- นิสิตปริญญาโทชั้นปีที่ 1–2
- Environmental Science
- Geography
- Geoinformatics / GIS
- Natural Resources
- Hydrology
- สาขาอื่น ๆ ที่เกี่ยวข้องกับข้อมูลเชิงพื้นที่และสิ่งแวดล้อม

### พื้นฐานที่ควรมี

มีความรู้ GIS เบื้องต้นจะช่วยให้เข้าใจได้เร็วขึ้น แต่ไม่จำเป็นต้องมีประสบการณ์เขียน Python ขั้นสูง

Notebook ถูกออกแบบให้แนะนำแนวคิดทีละขั้น โดยเริ่มจาก code ขนาดเล็กและตรวจผลลัพธ์ก่อนเข้าสู่การวิเคราะห์ที่ซับซ้อนขึ้น

---

## เมื่อเรียนจบแล้วจะทำอะไรได้บ้าง

นิสิตควรสามารถ

- อ่านและตรวจสอบ `Vector` และ `Raster` GIS data
- เข้าใจ `CRS`, `EPSG`, `Projection` และ `Reprojection`
- ทำ `Attribute Query` และ `Spatial Query`
- เข้าใจลำดับเขตการปกครอง `Province → District → Tambon`
- ใช้ `Point-in-Polygon` และ `Spatial Join`
- คำนวณ `Distance`, `Area`, `Count` และ `Density`
- สร้าง `Buffer` และ `Concentric Rings`
- ใช้ `Dissolve`, `Clip`, `Intersection` และ `Difference`
- เข้าใจ `Spatial Autocorrelation` และ `Moran's I`
- เปลี่ยน point observations เป็น continuous raster surface
- เปรียบเทียบ `IDW`, `Thin Plate Spline` และ `Trend Surface`
- ทำ `Zonal Statistics`
- อ่านและวิเคราะห์ `Digital Elevation Model (DEM)`
- คำนวณ `Slope`, `Hillshade` และ `Aspect`
- สร้าง static map ที่เหมาะสำหรับรายงานหรือ publication
- สร้าง interactive map ด้วย `Folium`
- Export ผลลัพธ์เป็น `GeoPackage`, `Shapefile ZIP`, `CSV`, `GeoTIFF`, `PNG` และ `HTML`

---

# เส้นทางการเรียนรู้

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

คำถามหลัก:

> ข้อมูล GIS คืออะไร และเราจะวัดระยะทาง พื้นที่ และ scale ให้ถูกต้องได้อย่างไร?

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

คำถามหลัก:

> Vector layers ถูกจัดโครงสร้าง เชื่อมโยง Query และสรุปเชิงพื้นที่อย่างไร?

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

คำถามหลัก:

> Spatial pattern เปลี่ยนตามระยะทางอย่างไร และเราจะทดสอบ pattern ทางสถิติได้อย่างไร?

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

คำถามหลัก:

> Point observations สามารถเปลี่ยนเป็น continuous raster surface ได้อย่างไร และ elevation สามารถแปลงเป็น terrain information ได้อย่างไร?

---

# รายการ Notebooks

| No. | Notebook | คำถามหลัก | Core Concepts | Colab |
|---:|---|---|---|---|
| 01 | [Python GIS Fundamentals & World Map](https://github.com/nattaponm/Teach_GIS_Python_Colab/blob/main/01_Python_GIS_Fundamentals_World_Map.ipynb) | GIS data ใน Python คืออะไร? | `GeoDataFrame`, Vector geometry, Attributes, Query, Mapping | [Open in Colab](https://colab.research.google.com/github/nattaponm/Teach_GIS_Python_Colab/blob/main/01_Python_GIS_Fundamentals_World_Map.ipynb) |
| 02 | [CRS, Projection, Distance, Area & Map Scale](https://github.com/nattaponm/Teach_GIS_Python_Colab/blob/main/02_CRS_Projection_Distance_Area_and_Map_Scale.ipynb) | เราจะวัดข้อมูลเชิงพื้นที่ให้ถูกต้องได้อย่างไร? | `CRS`, `EPSG`, `Reprojection`, Distance, Area, Map Scale | [Open in Colab](https://colab.research.google.com/github/nattaponm/Teach_GIS_Python_Colab/blob/main/02_CRS_Projection_Distance_Area_and_Map_Scale.ipynb) |
| 03 | [Thailand Province Area Statistics & Choropleth](https://github.com/nattaponm/Teach_GIS_Python_Colab/blob/main/03_Thailand_Province_Area_Statistics_and_Choropleth.ipynb) | เราจะสรุป spatial pattern ระดับจังหวัดได้อย่างไร? | Area Statistics, Classification, Choropleth | [Open in Colab](https://colab.research.google.com/github/nattaponm/Teach_GIS_Python_Colab/blob/main/03_Thailand_Province_Area_Statistics_and_Choropleth.ipynb) |
| 04 | [District Hierarchy & Spatial Query](https://github.com/nattaponm/Teach_GIS_Python_Colab/blob/main/04_Thailand_District_Hierarchy_and_Spatial_Query.ipynb) | Administrative layers สัมพันธ์กันอย่างไร? | Hierarchy, Attribute Query, Spatial Relationship, Spatial Join, QA/QC | [Open in Colab](https://colab.research.google.com/github/nattaponm/Teach_GIS_Python_Colab/blob/main/04_Thailand_District_Hierarchy_and_Spatial_Query.ipynb) |
| 05 | [Tambon Detailed Polygon Analysis](https://github.com/nattaponm/Teach_GIS_Python_Colab/blob/main/05_Thailand_Tambon_Detailed_Polygon_Analysis.ipynb) | เราจะจัดการ polygon รายละเอียดสูงได้อย่างไร? | ADM3, Area, Hierarchy, Web GIS, Detailed Cartography | [Open in Colab](https://colab.research.google.com/github/nattaponm/Teach_GIS_Python_Colab/blob/main/05_Thailand_Tambon_Detailed_Polygon_Analysis.ipynb) |
| 06 | [Village Points, Spatial Join & Density](https://github.com/nattaponm/Teach_GIS_Python_Colab/blob/main/06_Thailand_Village_Point_Spatial_Join_and_Density.ipynb) | Point กลายเป็น spatial information ได้อย่างไร? | Point-in-Polygon, Spatial Join, Count, Density | [Open in Colab](https://colab.research.google.com/github/nattaponm/Teach_GIS_Python_Colab/blob/main/06_Thailand_Village_Point_Spatial_Join_and_Density.ipynb) |
| 07 | [Distance, Buffer & Concentric-Ring Analysis](https://github.com/nattaponm/Teach_GIS_Python_Colab/blob/main/07_Distance_Buffer_and_Concentric_Ring_Analysis.ipynb) | Spatial pattern เปลี่ยนตามระยะทางอย่างไร? | Centroid, Distance, Buffer, Concentric Rings, Cumulative Count | [Open in Colab](https://colab.research.google.com/github/nattaponm/Teach_GIS_Python_Colab/blob/main/07_Distance_Buffer_and_Concentric_Ring_Analysis.ipynb) |
| 08 | [Clip, Overlay, Dissolve & Spatial Statistics](https://github.com/nattaponm/Teach_GIS_Python_Colab/blob/main/08_Clip_Overlay_Dissolve_and_Spatial_Statistics.ipynb) | เราจะ integrate layers และทดสอบ spatial pattern ได้อย่างไร? | Dissolve, Clip, Intersection, Difference, Moran's I, Local Moran | [Open in Colab](https://colab.research.google.com/github/nattaponm/Teach_GIS_Python_Colab/blob/main/08_Clip_Overlay_Dissolve_and_Spatial_Statistics.ipynb) |
| 09 | [Village Point → Raster Spatial Interpolation](https://github.com/nattaponm/Teach_GIS_Python_Colab/blob/main/09_Village_Point_to_Raster_Spatial_Interpolation.ipynb) | Point observations จะเปลี่ยนเป็น continuous raster ได้อย่างไร? | IDW, TPS, Trend Surface, Raster Resolution, Zonal Statistics | [Open in Colab](https://colab.research.google.com/github/nattaponm/Teach_GIS_Python_Colab/blob/main/09_Village_Point_to_Raster_Spatial_Interpolation.ipynb) |
| 10 | [DEM & Terrain Analysis: Phitsanulok](https://github.com/nattaponm/Teach_GIS_Python_Colab/blob/main/10_DEM_Terrain_Analysis_Phitsanulok.ipynb) | Elevation จะเปลี่ยนเป็น terrain information ได้อย่างไร? | DEM, Terrain Profile, Slope, Hillshade, Aspect, Zonal Statistics | [Open in Colab](https://colab.research.google.com/github/nattaponm/Teach_GIS_Python_Colab/blob/main/10_DEM_Terrain_Analysis_Phitsanulok.ipynb) |

---

# Concept Progression

Notebook ทั้ง 10 ถูกออกแบบให้ต่อกันผ่านคำถามหลักดังนี้

```text
01  GIS data คืออะไร?

02  เราวัดมันได้ถูกต้องหรือไม่?

03  เราสรุป spatial pattern อะไรได้บ้าง?

04  Layers สัมพันธ์กันทางพื้นที่อย่างไร?

05  เราจัดการ detailed polygons อย่างไร?

06  Points กลายเป็น spatial information ได้อย่างไร?

07  Spatial pattern เปลี่ยนตาม distance อย่างไร?

08  เรารวม layers และทดสอบ spatial pattern ได้อย่างไร?

09  Point observations กลายเป็น continuous raster ได้อย่างไร?

10  Elevation กลายเป็น terrain information ได้อย่างไร?
```

---

# ข้อมูลที่ใช้ในชุดบทเรียน

## Vector datasets

| Dataset | Geometry | การใช้งานหลัก |
|---|---|---|
| World Countries | Polygon | พื้นฐาน GIS ระดับโลก |
| Thailand ADM1 — Province | Polygon | Province analysis, Choropleth, Mask |
| Thailand ADM2 — District | Polygon | Administrative hierarchy, Distance analysis |
| Thailand ADM3 — Tambon | Polygon | Detailed polygon analysis, Zonal Statistics |
| Thailand Village Points | Point | Spatial Join, Density, Distance, Interpolation |

## Raster datasets

| Dataset | Type | การใช้งานหลัก |
|---|---|---|
| `data/wrl_dem_phk1.tif` | SRTM DEM | Elevation และ Terrain Analysis ใน Notebook 10 |

Notebook หลายบทจะดาวน์โหลด GIS data ที่ต้องใช้จาก GitHub โดยตรง เพื่อให้สามารถรันซ้ำใน Google Colab ได้สะดวก

---

# Python GIS Stack

| Library | หน้าที่หลัก |
|---|---|
| **GeoPandas** | Vector GIS |
| **Shapely** | Geometry operations |
| **PyProj** | CRS และ Projection |
| **Pandas / NumPy** | Data analysis |
| **Matplotlib** | Static map และ publication-quality figure |
| **Folium** | Interactive Web GIS |
| **Rasterio** | Raster GIS และ GeoTIFF |
| **SciPy** | Spatial Interpolation และ numerical methods |
| **PySAL / ESDA** | Spatial Statistics |
| **xyzservices** | Web basemap providers |

---

# หลัก GIS สำคัญที่ใช้ตลอดชุดบทเรียน

ชุดนี้เน้นการเข้าใจเหตุผลของการวิเคราะห์ ไม่ใช่เพียงทำให้ code รันได้

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

# รูปแบบการเรียนในแต่ละ Notebook

Notebook ส่วนใหญ่ใช้โครงสร้างคล้ายกัน

```text
Concept
↓
Small Python code
↓
Inspect result
↓
Map
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

แนวคิดคือให้เรียนทีละเรื่องและเห็นผลลัพธ์ทันที ก่อนจะรวมเป็น workflow ที่ซับซ้อนขึ้น

---

# การทำแผนที่

## Static Maps

Static map ใช้สำหรับการตีความเชิงวิชาการและการสร้างรูปสำหรับรายงาน

องค์ประกอบที่เน้น ได้แก่

- Title ที่ชัดเจน
- Legend หรือ Colorbar ที่เหมาะสม
- North Arrow เมื่อจำเป็น
- Scale Bar เมื่อเหมาะสม
- CRS และหน่วยที่ถูกต้อง
- Label ที่อ่านได้
- Export 300 dpi

## Interactive Maps

ใช้ `Folium` สำหรับ exploratory GIS และการเปรียบเทียบ layer

องค์ประกอบที่ใช้บ่อย ได้แก่

- OpenTopoMap
- Esri World Topographic
- Esri World Imagery
- Operational layers
- Tooltip / Popup
- LayerControl
- Choropleth

---

# แบบฝึกหัด

Notebook ส่วนใหญ่ประกอบด้วย 3 ระดับ

### Concept Check

คำถามสั้น ๆ เพื่อทบทวนแนวคิดหลัก

### Core Exercise

แบบฝึกหัดที่ปรับ parameter หรือเปลี่ยนพื้นที่ศึกษาโดยใช้ workflow เดิม

### MSc Challenge

หัวข้อขั้นสูง เช่น

- CRS sensitivity
- Count vs Density
- Buffer interval sensitivity
- Queen vs Rook vs KNN
- Interpolation validation
- DEM resolution sensitivity

---

# ผลลัพธ์ที่สามารถ Export ได้

ขึ้นอยู่กับ Notebook แต่ละบท นิสิตจะได้ฝึก Export ข้อมูลในรูปแบบ

```text
PNG
CSV
GeoPackage
Shapefile ZIP
GeoTIFF
HTML
```

ตัวอย่างโครงสร้าง output:

```text
outputs/
├── maps/
├── vectors/
├── rasters/
├── tables/
└── html/
```

---

# โครงสร้าง Repository

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

# ลำดับการเรียนที่แนะนำ

แนะนำให้เรียนตามลำดับ

```text
01 → 02 → 03 → 04 → 05 → 06 → 07 → 08 → 09 → 10
```

หากมีพื้นฐานแล้ว สามารถเลือกเริ่มตามหัวข้อได้ เช่น

- เริ่ม **02** หากต้องการทบทวน `CRS` และการวัด
- เริ่ม **04** หากสนใจ `Spatial Relationship` และ `Spatial Join`
- เริ่ม **07** หากสนใจ `Distance` และ `Buffer`
- เริ่ม **09** หากสนใจ `Raster Interpolation`
- เริ่ม **10** หากสนใจ `DEM` และ `Terrain Analysis`

อย่างไรก็ตาม การเรียนตามลำดับ 01–10 จะช่วยให้เห็นความเชื่อมโยงของแนวคิดได้ดีที่สุด

---

# แนวคิดการสอน

เป้าหมายของชุดบทเรียนนี้ไม่ใช่เพียงให้ code รันได้

นิสิตควรสามารถอธิบายได้ว่า

- ทำไมต้องเลือก CRS แบบนั้น
- ทำไม spatial operation หนึ่งจึงเหมาะกับคำถามหนึ่ง
- ทำไม Count กับ Density ให้ความหมายต่างกัน
- ทำไม Resolution และ Scale มีผลต่อผลวิเคราะห์
- ทำไม visual pattern ยังไม่ใช่ statistical evidence
- ทำไม Vector และ Raster เหมาะกับคำถามคนละประเภท
- ทำไมแผนที่ที่สวยไม่ได้แปลว่าถูกต้องทางวิทยาศาสตร์เสมอไป

---

# ผู้จัดทำ

**รองศาสตราจารย์ ดร.นัฐพล มหาวิค**  
ภาควิชาทรัพยากรธรรมชาติและสิ่งแวดล้อม  
คณะเกษตรศาสตร์ ทรัพยากรธรรมชาติและสิ่งแวดล้อม  
มหาวิทยาลัยนเรศวร

ความสนใจด้านการสอนและวิจัย ได้แก่ GIS, Remote Sensing, Weather Radar, Spatial Analysis, Environmental Applications และ Geospatial Programming

---

# การนำชุดบทเรียนไปใช้

Repository นี้เหมาะสำหรับ

- การเรียนการสอนในชั้นเรียน
- Laboratory exercise
- Self-study
- GIS / Python workshop
- การปรับใช้กับพื้นที่ศึกษาอื่น
- การประยุกต์กับข้อมูลสิ่งแวดล้อมและทรัพยากรธรรมชาติ

หลังจากเข้าใจ workflow แล้ว นิสิตควรทดลองเปลี่ยนพื้นที่ศึกษา Dataset Parameter และรูปแบบการแสดงผลด้วยตนเอง

---

# Acknowledgement

Repository นี้ใช้ Open-source Python geospatial libraries และข้อมูลภูมิสารสนเทศที่เปิดให้ใช้เพื่อการศึกษา

หากนำ workflow ไปใช้ในงานวิจัยหรือการปฏิบัติงานจริง ควรตรวจสอบข้อมูลต้นฉบับ เงื่อนไขการใช้ข้อมูล และ Software documentation ของแต่ละเครื่องมือเพิ่มเติม

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

> **เข้าใจแนวคิด GIS ก่อน แล้วใช้ Python เพื่อทำให้การวิเคราะห์ reproducible**
