# PAW1 – Traffic Collision Severity (Workshop 1)

## Team Members
- Andrew Silveira (Student ID:5077086 )
- Rohit Krishnamurthy Iyer (Student ID:8993045)
- Sabrina Ronnie George Karippatt (Student ID: 8991911)

## Project Overview
This project explores the **severity of traffic collisions** and investigates how environmental and roadway factors contribute to accident outcomes.  
It is developed as part of **Problem Analysis Workshop 1** in the Applied AI & Machine Learning program.  

**Research Question:**  
Which road & environmental features are most associated with severe injuries in collisions?

## Setup & Configuration
This project uses Python 3.13 in a virtual environment (`.venv`).  
Install dependencies using:

```bash
python -m venv .venv
. .\.venv\Scripts\Activate.ps1
pip install -r requirements.txt 
```

## Data Source
The dataset was downloaded from the [FARS Traffic Accident Data](https://www.kaggle.com/) repository.  
It includes three key files: `accident.csv`, `person.csv`, and `vehicle.csv`.

## Data Cleansing (Planned)
Based on Unit 1 (Slides 22–23), the dataset will need:
- Merging accident, person, and vehicle tables.
- De-duplication of records.
- Standardization of categorical values and codes.
- Handling missing values in weather/light conditions.
- Creating a binary target variable (`severe = 1 if FATALS > 0`).

## Repository Structure
WS_1/
├── data/         # raw CSV data (accident.csv, person.csv, vehicle.csv)
├── notebooks/    # Jupyter notebooks (01_trafficcollision.ipynb)
├── outputs/      # analysis outputs (to be generated)
├── src/          # helper scripts (if needed later)
├── .venv/        # virtual environment
└── README.md     # project documentation


