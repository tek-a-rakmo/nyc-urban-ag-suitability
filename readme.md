# Rooftop Agriculture Suitability Analysis for NYC

## Overview This project develops a GIS-based suitability model to identify optimal rooftop sites for urban agriculture across New York City. Using integrated spatial criteria—including zoning, building height, structural capacity, and solar radiation—it identifies over 36,000 buildings suitable for intensive and extensive farming.

## Repository Structure

notebooks/: Numbered analysis steps.

01_data_preprocessing: High-performance loading of PLUTO and Building Footprints.

02_solar_radiation_model: GRASS GIS integration for solar analysis.

03_suitability_analysis: Multi-criteria filtering and final classification.

outputs/: Generated interactive maps and static figures.

docs/: Final academic report.

## How to Reproduce

Install Dependencies: pip install -r requirements.txt

External Requirement: Install GRASS GIS (required for notebook 02).

Download Data:

Download MapPLUTO (Release 24v1) from NYC Planning.

Download NYC Building Footprints from NYC Open Data.

Place these in the data/raw/ folder.

Run Notebooks: Execute the notebooks in numerical order.
