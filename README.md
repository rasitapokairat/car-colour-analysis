# Transportation Data Cleaning and Analytics Pipeline

Developed an end-to-end data cleaning and standardization pipeline for multi-source transportation survey datasets collected in 2022. The project focused on resolving real-world data quality issues, consolidating inconsistent raw files, and generating infographic-based analytical outputs for transportation insights.



## Project Overview

The objective of this project was to transform inconsistent transportation survey data into a clean, standardized, and analysis-ready dataset.

The raw datasets contained multiple data quality challenges, including:
- inconsistent date and time formats
- schema mismatches
- duplicate records
- missing values
- inconsistent vehicle classifications
- formatting irregularities

The final outputs included:
- cleaned master datasets
- validated CSV exports
- infographic-based analytical summaries



## Tech Stack

- Python
- Pandas
- NumPy
- MatPlotLib
- Jupyter Notebook



## Key Data Cleaning Processes

### Data Standardization
- Standardized date and time formats
- Rounded timestamps into consistent intervals
- Removed unintended spaces and inconsistent letter casing

### Data Validation
- Removed invalid and incomplete records
- Applied occupancy validation rules by vehicle type
- Filtered records outside valid collection periods

### Schema Alignment
- Corrected mismatched headers and misplaced values
- Standardized column names and vehicle categories
- Merged columns with equivalent analytical objectives

### Duplicate Resolution
- Identified duplicate observations using:
  - date
  - time
  - direction
  - source file
- Prioritized records containing richer analytical attributes



## Data Processing Workflow

```text
Raw CSV Files
      ↓
Data Cleaning & Validation
      ↓
Schema Standardization
      ↓
Duplicate Resolution
      ↓
Dataset Consolidation
      ↓
Analysis & Infographic Generation
```



## Final Output

The project produced:
- A standardized transportation dataset
- Cleaned CSV exports for downstream analysis
- Infographic-based visual summaries for stakeholder reporting

The cleaned dataset enabled analysis of:
- Traffic flow patterns
- Vehicle occupancy trends
- Vehicle type distributions
- Directional movement behaviour



## About the Author

Rasita Pokairat

Master of Science in Data Science  
University of Bath
