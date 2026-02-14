# slope-terrain-feasibility-analysis
Slope-based terrain suitability assessment for preliminary civil infrastructure planning using DEM analysis in QGIS.
🏗️ Slope-Based Terrain Suitability Analysis — Aksa Energy Site, Ghana
📌 Project Overview

This project evaluates terrain suitability for preliminary civil infrastructure planning using slope analysis derived from a Digital Elevation Model (DEM).

Terrain slope is a critical parameter influencing:

Construction feasibility

Earthwork requirements (cut-and-fill)

Road alignment design

Drainage behavior and erosion risk

The objective was to classify land into engineering-relevant slope categories to support early-stage site assessment.

📍 Study Area

The study focuses on a site associated with the Aksa Energy project in Ghana.

A locator inset was used to contextualize the site within national boundaries.

🛰️ Data Used
Dataset	Source	Resolution
SRTM DEM	USGS/NASA	30 m

Projection:
WGS 84 / UTM Zone 30N

⚙️ Methodology

The workflow was completed in QGIS using the following steps:

1️⃣ DEM clipped to Area of Interest
2️⃣ Hillshade generated for terrain visualization
3️⃣ Slope calculated using percent rise (civil engineering standard)
4️⃣ Slope classified into suitability categories:

Slope (%)	Interpretation
0–5%	Suitable
5–10%	Acceptable
10–15%	Moderate Constraint

5️⃣ Results composed into a feasibility-style layout map.

📊 Result

The resulting map highlights that:

Majority of the site falls within 0–10% slope, indicating favorable buildability.

Moderate slopes are concentrated along ridge systems.

Localized areas may require cut-and-fill grading.

Terrain conditions are generally appropriate for low- to mid-density development.

Final Map:

⚠️ Limitations

The 30 m DEM resolution limits detection of micro-topographic variation.

Higher-resolution DEM (≤10 m or LiDAR) would improve engineering precision for detailed design stages.

🧠 Key Takeaway

This workflow demonstrates how geospatial terrain analysis can support evidence-based decision-making in civil engineering site evaluation.

👤 Author

Victor Morton-Bruce
Civil Engineering Student | Geospatial Analysis
Kwame Nkrumah University of Science and Technology (KNUST)