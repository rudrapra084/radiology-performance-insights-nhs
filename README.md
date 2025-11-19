# NHS Diagnostic Imaging Analytics: End-to-End Data Cleaning, Transformation, and Performance Dashboard

This repository documents a complete analytics workflow using raw data from the NHS Diagnostic Imaging Dataset (2024/25).
It includes Python-based data preparation and a Tableau dashboard analyzing national radiology performance.

## 1. Project Overview

This project transforms raw monthly Excel tables from NHS England into a tidy, analysis-ready dataset and visualizes key performance indicators for radiology service delivery.
The pipeline covers:

- Data ingestion of raw Excel files

- Cleaning and standardization of provider names, modalities, and date fields

- Reshaping and merging heterogeneous tables into a single long-format dataset

- Exporting a tidy CSV for analysis and visualization

- Building an interactive Tableau dashboard to support evidence-driven operational decisions

## 2. Data Source

Raw data originates from the official NHS England Statistical Work Areas:

Diagnostic Imaging Dataset 2024/25
Source:
https://www.england.nhs.uk/statistics/statistical-work-areas/diagnostic-imaging-dataset/diagnostic-imaging-dataset-2024-25-data/

The repository includes the three original Excel tables as /raw_data for transparency and reproducibility.

## 3. Methods 
Python Processing

Key Python tasks (pandas workflow):

- Load all Excel sheets

- Normalize inconsistent headers

- Handle thousands separators and numeric parsing

- Melt wide tables to long format

- Merge across providers and modalities

- Export a single tidy CSV

Visualization (Tableau)

The Tableau dashboard provides:

- Total imaging activity

- Median waiting times before scan

- Median reporting times after scan

- Efficiency comparisons across modalities

Provider-level performance

Interactive filters for modality and provider

Link to Tableau Public:
https://public.tableau.com/app/profile/pranab.rudra/viz/RadiologyEfficiencyandThroughputInsightsNHS202425/Dashboard1?publish=yes

## 4. Goals and Use Cases

This project supports:

- Hospital performance monitoring

- Workforce and resource planning

- Modality throughput assessment

- Operational and process improvement

- Benchmarking across providers

## 5. Technologies

Python 

pandas

Tableau Public

Excel

## 6. Author

Created by Pranab Rudra
