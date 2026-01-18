# Smart Farming Python Project

This project analyzes smart farming trial results and recommends the best crop varieties for each soil type.

## Datasets Used
The program reads processed datasets from:
- data/processed/trial_results_summary_by_soilvariety.csv
- data/processed/soil_types_cleaned.csv
- data/processed/crop_varieties_standardized.csv

## How to Run
### 1) Create and activate a virtual environment (recommended)

Windows PowerShell:
python -m venv .venv
.venv\Scripts\Activate.ps1

### 2) Install requirements
pip install -r requirements.txt

### 3) Run the program
python project.py

## Tests
Run tests with:
pytest
