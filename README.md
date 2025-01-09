# Replication Package

## Purpose
This replication package provides the necessary files and instructions to reproduce the analysis of this research.

## Data Source
- A dataset of GitHub Actions workflow histories - https://zenodo.org/records/13985548

## Setup Instructions
1. Create and activate a virtual environment:
   ```bash
   pip install virtualenv
   virtualenv myenv
   source myenv/bin/activate

### Summary of Commands
Here’s a quick reference for all the commands we’ve discussed:

# Create project directory
mkdir github-workflows-analysis
cd github-workflows-analysis

# Set up virtual environment (on macOs)
python3 -m venv myenv

# Activate virtual environment
source myenv/bin/activate

# Install dependencies
pip install -r requirements.txt

# Directory Structure
# Your project directory should look something like this if you followed the given instructions:
github-workflows-analysis/
├── data-raw/         # Folder for raw datasets (e.g., Guillaume’s dataset)
├── data/             # Folder for processed/generated datasets
├── notebooks/        # Folder for Jupyter notebooks
├── README.md         # Project documentation
├── requirements.txt  # List of dependencies
└── venv/             # Virtual environment folder

