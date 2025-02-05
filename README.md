# Uber Drive Data Analysis

## Project Overview
This project analyzes an Uber drive dataset to extract insights about ride patterns, trip purposes, and distance distributions. The goal is to understand how Uber trips are utilized and to visualize key trends in ride data.

## Dataset Description
- **Source**: Uber drive logs
- **Features**:
  - `START_DATE*`, `END_DATE*`: Ride timestamps
  - `CATEGORY*`: Business or personal trips
  - `START*`, `STOP*`: Locations
  - `MILES*`: Distance covered
  - `PURPOSE*`: Purpose of the trip (e.g., Meeting, Errand, Customer Visit)

## Key Insights
- Most trips cover short distances, as seen in the mileage distribution.
- Business trips dominate the dataset, with meetings and customer visits being the most frequent purposes.
- Some missing values exist in the `PURPOSE*` column.

## Visualizations Included
- **Mileage Distribution**: Histogram of distances traveled per trip.
- **Trip Purpose Count**: Bar chart of the most common trip purposes.
- **Correlation Heatmap**: Relationship between numerical features.

## How to Run the Notebook
1. Clone the repository:
   ```bash
   git clone https://github.com/MuditNautiyal-21/Uber-Drive-Analysis.git

2. Install required Python libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn
   ```
3. Open and run the Jupyter Notebook:
   ```bash
   jupyter notebook uber_drive_analysis.ipynb
   ```

## Author: Mudit Nautiyal
