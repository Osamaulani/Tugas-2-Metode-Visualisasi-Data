# Visualisasi Data dengan Dataset Factbook
Proyek visualisasi data menggunakan dataset factbook untuk menghasilkan berbagai visualisasi informatif menggunakan Python.

## Overview
Proyek ini fokus pada pembuatan visualisasi dari dataset factbook yang terdiri dari 29 kolom dan 149 baris data. Implementasi mencakup berbagai teknik visualisasi dan transformasi data.

## Tasks

### Task 1: Basic Visualization
Membuat visualisasi 2D dengan mark dan channel yang sesuai:

1. **Scatter Plot**
   - Implementasi menggunakan Altair dan Matplotlib
   - Visualisasi hubungan antar variabel dalam DataFrame

2. **Bubble Plot**
   - Menggunakan NumPy dan Pandas
   - Visualisasi hubungan antara:
     - Tingkat kelahiran
     - Tingkat kematian
     - Harapan hidup saat lahir

### Task 2: Advanced Visualization with Data Transformation
Visualisasi dengan transformasi data:

1. **Heatmap**
   - Menggunakan Pandas dan Seaborn
   - Visualisasi korelasi antar fitur dalam dataset

2. **Transformed Scatter Plot**
   - Transformasi data menggunakan:
     - Rasio kematian-kelahiran (death_birth_ratio)
     - Logaritma GDP (gdp_log)
   - Visualisasi data hasil transformasi

## Technologies Used
- Python
- Libraries:
  - Altair
  - Matplotlib
  - NumPy
  - Pandas
  - Seaborn

## Dataset
- File: factbook-_1_.csv
- Jumlah kolom: 29
- Jumlah baris: 149

## Tim Pengembang
- Osa Nastiyar Maulani (1305210055)
- Nurwulan Handayani (1305210102)
- Egi Dhea Nagita (1305213009)

## Setup dan Penggunaan
1. Install required libraries:
```bash
pip install pandas numpy matplotlib seaborn altair
```
2. Load dataset:
```python
import pandas as pd
df = pd.read_csv('factbook-_1_.csv')
3. Run visualizations sesuai dengan notebook yang disediakan
