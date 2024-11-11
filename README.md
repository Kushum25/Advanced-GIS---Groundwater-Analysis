# 🌍 Groundwater Analysis: Geospatial Study of Jefferson County, Texas

Welcome to the **Groundwater Analysis** project, a comprehensive geospatial study of groundwater flow dynamics in Jefferson County, Texas. This project applies advanced geospatial techniques to assess groundwater characteristics using well data and spatial modeling.

## 📊 Project Overview

This analysis involves a series of key tasks to explore groundwater flow patterns:

- **🗺️ Buffer Creation**: A 5-mile buffer around Jefferson County was created, and data was reprojected using the Albers Equal Area NAD83 CONUS 2011 system for precise spatial representation.
- **🔗 Data Integration**: Well data, including coordinates, land surface elevation, and water levels, were merged into a comprehensive dataset for analysis.
- **📈 Spatial Analysis**: Linear regression was applied to determine groundwater gradients and flow directions. The Inverse Distance Weighting (IDW) method was used to estimate transmissivity.
- **💧 Flow Visualization**: Darcy’s law was employed to calculate groundwater flow velocity, with quiver plots generated to illustrate flow directions.

## 🚀 Key Features

- **Advanced Spatial Techniques**: Includes buffering, clipping, reprojection, and spatial joins for geospatial analysis.
- **Predictive Modeling**: Uses linear regression to analyze flow trends and directions.
- **Hydraulic Calculations**: Estimates hydraulic conductivity and applies Darcy’s law for flow calculations.
- **Interactive Visualizations**: Generates clear map visualizations and quiver plots for interpreting groundwater flow.

## 🛠️ Technologies Used

- **Python Libraries**: `Geopandas`, `Matplotlib`, `Pandas`, `Scipy`
- **Data Sources**: WellMain and WaterLevels datasets, Texas County GeoPackage
- **Geospatial Methods**: Buffering, Clipping, Reprojection, IDW

## 🌐 Applications

The results from this analysis offer valuable insights for groundwater management, environmental planning, and future hydrological studies in similar geological settings.

## 📄 License

This project is licensed under the [MIT License](LICENSE).

## 📢 Contact

For questions or feedback, please reach out via GitHub issues.

---

**Explore the code, data, and visualizations provided in this repository to gain a deeper understanding of groundwater dynamics in Jefferson County, Texas.**
