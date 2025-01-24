# Detection of Spatial and Functional Signatures for Environmental Measurements

This repository contains the codebase accompanying the paper **"Urban Contexts: A Geospatial Approach to Identifying In-Situ Measurement Sites for Urban Acoustic Environments"**. It provides reproducible workflows for analyzing urban spatial and functional characteristics to support environmental and acoustic measurements in urban areas.

## Objectives

1. Develop robust methodologies for urban spatial analysis.
2. Create scalable workflows for extracting urban form and function metrics.
3. Generate urban signature types based on morphometric variables.

## Features

- Analysis of urban form and function using Enclosed Tessellation Cells (ETCs).
- Integration of environmental and demographic variables with urban morphometric analysis.
- Application of clustering techniques (e.g., GMM) to detect urban signature types.
- Context-informed purposive sampling for identifying optimal measurement sites.

## Development Status

This repository is actively under development. While the current codebase includes workflows for urban form and function analysis, clustering, and environmental integration, additional features, including the purposive sampling framework, will be added in future updates.

Future refinements will:
- Optimize workflows for greater scalability.
- Include detailed purposive sampling strategies based on urban signature variability.
- Enhance documentation for broader accessibility and usability.

We welcome feedback and contributions to help refine this codebase!


## Requirements

- Python 3.9+
- Libraries:
  - [Momepy](https://docs.momepy.org/en/stable/)
  - Geopandas
  - Pandana
  - Contextily
  - Scikit-learn
  - Matplotlib
  - Numpy
  - Pandas
  - PySAL (for spatial interpolation)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Doutrespace/Urban_Contexts
   cd Urban_Contexts
