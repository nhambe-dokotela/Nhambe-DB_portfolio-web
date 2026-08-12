# Project 7: Provincial Agricultural Economic Dashboard

## Overview
An interactive dashboard analysing how agricultural production, livestock 
sales, and farming income shifted across South Africa's 9 provinces between 
2007 and 2017, using official Statistics South Africa data.

## Problem Statement
Provincial agricultural change data in South Africa is often locked in 
static government census reports, making it difficult for extension 
officers, policymakers, and agribusinesses to quickly identify which 
provinces are growing, which commodities are shifting, and where 
opportunity or risk is emerging over time.

## Objective
Transform raw provincial agricultural census data into a clean, interactive 
dashboard that answers:
- Which provinces grew fastest in crop and livestock sales between 2007 and 2017?
- How has the composition of farming income shifted per province (field crops, 
  horticulture, animals, other)?
- Which commodities/livestock categories are gaining or losing share?
- What does current (2017) land use and production look like across provinces?

## Tools & Technologies
| Layer | Tool |
|---|---|
| Data Extraction | Excel (Power Query) |
| Cleaning & Analysis | Excel (Power Query) |
| Visualisation | Looker Studio |
| Report | PDF |

## Dataset
- **Source:** Statistics South Africa, Census of Commercial Agriculture 2017, 
  Report No. 11-02-01
- **Coverage:** All 9 South African provinces
- **Variables:** Crop sales volume, livestock sales volume (Cattle, Sheep, 
  Chickens), % contribution to gross farming income by category, planted 
  land area (2017 snapshot)
- **Time comparison:** 2007 vs 2017

## Key Findings
*(to be updated after dashboard build)*
- Fastest-growing province by crop sales
- Fastest-growing province by livestock sales
- Biggest shift in income composition by province
- Current land use leader by province

## Scope Notes
- Livestock analysis limited to Cattle, Sheep, and Chickens — the top 3 
  nationally sold livestock categories per StatsSA — Pigs and Goats were 
  tracked in the original census but excluded from this dashboard.
- Land use (Crop-Area) data reflects a 2017 snapshot only; no 2007 
  comparison was available in the source.

## AI Collaboration
Built this dashboard as part of my agri-data portfolio. Used Claude for Power Query troubleshooting and documentation, the analysis and cleaning decisions are mine.
