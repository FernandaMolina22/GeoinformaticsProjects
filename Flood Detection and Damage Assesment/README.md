# Flood Impact and Damage Assessment in St. Peter, Minnesota

## Abstract

This study investigates the flood impact and damage assessment in St. Peter, Minnesota, following a severe flood event from June 19th to 21st, 2024, using Landsat 8 multispectral imagery. The research focuses on data from June 26th, five days after the last heavy rainfall, to identify flooded areas and assess damage to buildings and roads. Key data processing steps included cloud masking, histogram matching, pansharpening, and the calculation of the Normalized Difference Water Index (NDWI) to detect changes in water coverage. Results revealed significant flooding near the Minnesota River, affecting key infrastructure, including roads and non-residential buildings. This study demonstrates the effectiveness of remote sensing and multispectral imagery in disaster assessment, highlighting the importance of advanced preprocessing techniques to improve accuracy.

## Project Overview

- **Objective**: To assess the impact of a severe flood event on infrastructure using Landsat 8 imagery.
- **Tools and Techniques**: Landsat 8 multispectral imagery, cloud masking, histogram matching, pansharpening, NDWI calculation.
- **Key Findings**: Significant flooding near the Minnesota River, affecting roads and buildings.

## Folder Structure

The project folder is organized into several directories, each corresponding to a specific processing step. Inside each directory, you will find both the inputs and outputs related to the respective Jupyter scripts:

- **`Pansharpening/`**: Contains both the input data and output results from running the Pansharpening_HSV Jupyter script. Files related to this process are located here without further subdirectories.
- **`CloudMasking/`**: Includes the inputs and outputs obtained from the cloud masking Jupyter script, all mixed together in this folder.
- **`Nan Bands/`**: Contains the inputs and outputs from the convert_zero_to_nan Jupyter script, with all files mixed in this directory.
- **`Matching/`**: Contains the inputs and outputs from the histogram matching Jupyter script, all placed in this folder.

In addition to these folders, you will find the following Jupyter scripts in the root directory of the project:

- **`Pansharpening_HSV.ipynb`**: The Jupyter notebook for performing pansharpening.
- **`Cloud Masking.ipynb`**: The Jupyter notebook for cloud masking.
- **`convert_zero_to_nan.ipynb`**: The Jupyter notebook for converting zero values to NaN.
- **`Match_Histograms.ipynb`**: The Jupyter notebook for histogram matching.



