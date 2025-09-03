# Medical Data Visualizer

This project is part of the **FreeCodeCamp Data Analysis with Python Certification**.  
The task is to visualize and analyze medical examination data using **Pandas**, **Matplotlib**, and **Seaborn**.

## 📊 Project Overview
- Import and preprocess medical data (`medical_examination.csv`)
- Add calculated BMI and `overweight` column
- Normalize cholesterol and glucose values
- Generate a **categorical plot** to compare features across patients with/without cardiovascular disease
- Clean the dataset and generate a **heatmap** to explore correlations between medical variables

## 🛠️ Technologies Used
- Python 3
- Pandas
- Matplotlib
- Seaborn
- NumPy

## 📂 Files
- `medical_examination.csv` → dataset provided
- `medical_data_visualizer.py` → main script with `draw_cat_plot` and `draw_heat_map` functions
- `catplot.png` → generated categorical plot
- `heatmap.png` → generated correlation heatmap

## 🚀 Usage
Run the script to generate both visualizations:

```bash
python medical_data_visualizer.py
