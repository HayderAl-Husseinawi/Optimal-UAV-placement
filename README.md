# Optimal UAV Placement — Installation & Setup Guide

# Overview

This project implements an Optimal UAV Placement Framework using the Python programming language for UAV deployment optimization and performance evaluation.

---

# System Requirements

Before running the project, ensure the following are installed:

- Python 3.10 or newer
- pip (Python package manager)

---

# Project Setup

 1. Extract the Zip file and open the project folder manually.

---

 2. Create a Virtual Environment

Using a virtual environment is recommended to avoid dependency conflicts.

#Windows

bash
python -m venv venv
venv\Scripts\activate


After activation, `(venv)` should appear in the terminal.


 3. Install Required Libraries

bash
pip install -r requirements.txt


 4. Run the Project

bash
python main.py
or open the code: Code .


Replace `main.py` with the main project file if different.

Example:

bash
python optimal_uav_placement.py

We have used four datasets from KIS-ORCA, Kingfisher Information Service, which can be found online. This code requires an Excel file of the dataset with the ID number and coordinates of each turbine; then the name/path of the file can be changed within the code. Although PDF files of the datasets are provided in the file named "data".
KIS-ORCA, 2025a. Kingfisher Information Service – Offshore Renewable & Cable Awareness. Walney 1–4 offshore wind farm chart. January 2025.
KIS-ORCA, 2025b. Kingfisher Information Service – Offshore Renewable & Cable Awareness. Gunfleet Sands and Demonstration Site offshore wind farm chart. January 2025.
KIS-ORCA, 2025c. Kingfisher Information Service – Offshore Renewable & Cable Awareness. Gwynt y Mor offshore wind farm chart. January 2025.
KIS-ORCA, 2025d. Kingfisher Information Service – Offshore Renewable & Cable Awareness. Sheringham Shoal offshore wind farm chart. January 2025.

# Contact

Author: Hayder Al-husseinawi
halhusseinawi01@qub.ac.uk
