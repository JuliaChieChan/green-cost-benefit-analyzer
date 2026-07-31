# Green Cost-Benefit Analyzer

## Overview
A Python-based decision-support tool that helps business and environmental professionals evaluate industrial equipment investments. The tool calculates financial payback periods, ROI percentages, and annual CO2 emission reductions, enabling side-by-side comparison of up to 3 machines.

## Problem It Solves
Business owners often struggle to justify green investments because the environmental benefits are hard to quantify in dollars. This tool bridges that gap by converting CO2 emissions into tangible metrics that financial decision-makers understand.

## Features
- Compares 3 machines simultaneously
- Calculates payback period and ROI
- Estimates annual CO2 emissions saved (lbs/year)
- Exports results to CSV for Excel analysis
- Provides clear recommendations based on financial and environmental data

## Technologies Used
- Python 3
- Google Colab / Jupyter Notebooks
- CSV file handling

## How to Run
1. Open this notebook in Google Colab
2. Run all cells
3. Input your machine data when prompted
4. View the comparison report and exported CSV file

## Sample Output
==================================================
COMPARATIVE ANALYSIS REPORT
==================================================

MACHINE 1
Cost: $9,000.00
Payback: 9.0 years
CO2 Saved: 425.0 lbs/year
ROI per year: 11.1%

MACHINE 2
Cost: $12,000.00
Payback: 6.0 years
CO2 Saved: 510.0 lbs/year
ROI per year: 16.7%

MACHINE 3
Cost: $15,000.00
Payback: 3.0 years
CO2 Saved: 595.0 lbs/year
ROI per year: 33.3%

==================================================
RECOMMENDATION: The machine with the shortest payback is the best
financial choice. The machine with the highest CO2 saved is the
greenest choice.


## Future Improvements
- Add solar panel and EV charging station use cases
- Integrate real-time utility rate APIs
- Build a web interface using Flask or Streamlit
- Add graphical visualizations using Matplotlib

## Author
Julia Chan - University of Waterloo - Environment and Business Major, Computing Minor
