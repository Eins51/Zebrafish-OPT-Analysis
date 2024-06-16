# Zebrafish Optical Projection Tomography Analysis

This repository contains MATLAB scripts for analyzing optical projection tomography (OPT) volumetric data of a zebrafish. The provided scripts implement Maximum Intensity Projection (MIP) techniques to project the volumetric data along three orthogonal axes: X, Y, and Z.

## Description

The project aims to facilitate the visualization and analysis of internal structures of a zebrafish using optical projection tomography data. Two MATLAB scripts are included that handle data processing from raw `.tif` image files to enhanced visual outputs.

## Contents

- `task4.mlx`: Extends the basic MIPs with image swapping, adaptive histogram equalization, Gaussian filtering, and edge sharpening to improve image clarity and detail.

## Getting Started

### Prerequisites

Ensure you have MATLAB installed on your computer (MATLAB R2021a or later is recommended). Additionally, the Image Processing Toolbox should be installed to run the scripts successfully.

### Installation

Clone the repository to your local machine using the following command:

```bash
git clone https://github.com/Eins51/Zebrafish-OPT-Analysis.git
```

### Usage
Open MATLAB and navigate to the directory where the scripts are located. Run task4.mlx to perform the analysis. Ensure that your data files are in the specified path as referenced in the scripts.

## Visuals
![MIP Result](https://github.com/Eins51/Zebrafish-OPT-Analysis/blob/main/Visualization.png "Maximum Intensity Projection Output")
