# Replication Package: GitHub Actions Workflows Analysis

## Overview

This replication package supports our ongoing research on the evolution of **GitHub Actions workflows**. Our current focus is on extracting path/value pairs from workflow YAML files to identify key features such as triggers, environment variables, matrix strategies, and reusable workflows. These data will later serve as a basis for analyzing workflow concepts, size, and complexity over time.

## Data Source

- **GitHub Actions Workflow Histories**: Based on the dataset available on [Zenodo](https://zenodo.org/records/13985548).

## Setup Instructions

Follow the steps below to set up the project environment:

1. **Create a Project Directory**

   ```bash
   mkdir github-workflows-analysis
   cd github-workflows-analysis

2. **Set Up a Virtual Environment**

   ```bash
   python3 -m venv myenv

3. **Activate the environment**

   ```bash
   source myenv/bin/activate    # macOS/Linux
   myenv\Scripts\activate       # Windows


3. **Install Dependencies**

   ```bash
   pip install -r requirements.txt


4. **Repository Structure**

The project repository is organized as follows:

   ```bash
   github-workflows-analysis/
   ├── data-raw/         # Raw datasets (e.g., Guillaume's dataset)
   ├── data/             # Processed data (e.g., extracted paths and values)
   ├── notebooks/        # Jupyter notebooks for data extraction and analysis
   ├── README.md         # Project documentation
   ├── requirements.txt  # Project dependencies
   └── myenv/            # Python virtual environment
   ```


**Notes:**
   Project Development: This project is still in progress.
