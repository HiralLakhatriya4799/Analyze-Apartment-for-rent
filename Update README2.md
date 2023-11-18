## Introduction
This report entails a comprehensive statistical analysis of a dataset extracted from 'new_file.csv'. The analysis focuses on two crucial columns, 'price_display' and 'square_feet', utilizing Python programming to derive key statistical measures and draw valuable insights.
## Steps Undertaken

### Step 1: Dataset Preparation
- Extracted the 'apartment_rent_for_classified' dataset from UCL.
- Streamlined the dataset by eliminating unnecessary rows and selected pertinent columns, renaming the file to 'new_file.csv' for ease of handling.

### Step 2: Statistical Analysis in Python
- Imported essential libraries (pandas, numpy, scipy, seaborn, and matplotlib) for data analysis and visualization in a Jupyter Notebook environment.
- Employed data preprocessing techniques including handling missing values by converting columns to numeric format and dropping rows with NaN values.

### Step 3: Statistical Measures Calculated
- Computed essential statistical measures such as mean, median, mode, range, sample variance, sample standard deviation, and quartiles for 'price_display' and 'square_feet' columns.

### Outlier Identification
- Identified outliers by calculating z-scores for 'price_display' and 'square_feet' columns, highlighting observations that significantly deviate from the dataset's typical distribution.

### Graphical Representations
1. **Box Plot**: Displayed the distribution of 'price_display' and 'square_feet', highlighting the interquartile range (IQR), median, and outliers.
2. **Seaborn**: Employed scatter plots to depict the relationship between 'square_feet' and 'price_display'.
3. **Linear Regression**: Visualized the linear relationship between 'square_feet' and 'price_display', showcasing a positive correlation.
4. **HeatMap**: Illustrated the correlation between 'price_display' and 'square_feet' using a color-coded scheme.

## Conclusion and Reflection
This thorough analysis utilizing statistical methods and graphical representations provided valuable insights into the dataset's variability and underlying patterns. The combination of Python-based statistical calculations and visual representations facilitated a deeper understanding of the 'price_display' and 'square_feet' data, allowing for a comprehensive exploration.

---

*This report documents the process, analysis, and findings in detail to facilitate better understanding and utilization of the dataset for further analysis.*
