# iLevel Calculations

![Status](https://img.shields.io/badge/status-actively%20maintained-brightgreen)
![Deprecation](https://img.shields.io/badge/superseded%20by-Power%20BI%20Dasboard-orange)

## Overview

iLevel Calculations is an R script designed to retrieve data from Salesforce via API and generate outputs containing various metrics published to the iLevel platform. The script supports multiple levels of aggregation to meet requirements of iLevel reporting.

## Features
- Connects to Salesforce API to extract relevant data
- Computes and aggregates metrics at multiple levels
- Outputs structured data to be copied into iLevel
- Actively maintained until expected deprecation in Q2 2025

## Prerequisites
- R (version 4.3.2 or later)
- Required R packages:
  - `tidyverse`
  - `data.table`
  - `salesforcer`
  - `yaml`
  - `rlang`
  - `lubridate`
  - `openxlsx`
  - `readxl`
- Salesforce API credentials with appropriate access permissions

## Installation
1. Clone this repository:
   ```sh
   git clone https://github.com/NAVEX-Analytics/iLevel-Calculations.git
   cd iLevel-Calculations
   ```
2. Install required R packages:
   ```r
   install.packages(c("tidyverse", "data.table", "salesforcer", "yaml", "rlang", "lubridate", "openxlsx", "readxl"))
   ```

## Usage
1. Configure your Salesforce API credentials in the appropriate environment file or script parameters.
2. Run the R script:
   ```r
   source("iLevel Automation.Rmd")
   ```
3. The output data will be stored in the designated output directory.

## Roadmap
- Maintain functionality until Power BI dashboard replacement in Q2 2025

