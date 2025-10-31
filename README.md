# Sensor Data Analysis

Simple pandas project.

## Installation

```bash
pip install -r requirements.txt
```

## Usage

```bash
python process_sensor_data.py
```

## Files

- `sensor_data.csv`: Input data
- `sensor_data.xlsx`: Input excel data
- `process_sensor_data.py`: Analysis script
- `sensor_data_analyzed.csv`: Output results
- `sensor_data_analyzed.xlsx`: Output excel results

## What It Does

1. Loads CSV and Excel data
2. Cleans missing values
3. Calculates averages by equipment
4. Flags high temperature readings (>50°C)
5. Exports results to CSV and Excel

## Requirements

- Python 3.7+
- pandas
- openpyxl