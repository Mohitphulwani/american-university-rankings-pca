# american-university-rankings-pca
Performing Principal Component Analysis on American university rankings to identify underlying patterns and reduce dimensionality, highlighting key factors influencing university performance.
# Principal Component Analysis on American University Rankings Dataset

## Overview
This project applies **Principal Component Analysis (PCA)** to the **American University Rankings dataset** to uncover underlying factors that drive university performance.  

The aim is to reduce dimensionality, extract key patterns, and interpret relationships among ranking features such as tuition, graduation rates, faculty resources, and student-faculty ratios.

---

## Dataset
The dataset includes various metrics of American universities, such as:
- Tuition and fees  
- Graduation and retention rates  
- Faculty resources and student-faculty ratios  
- Enrollment and financial indicators  
- Other performance-related metrics  

*(Include dataset link if public or specify if included in `data/` folder.)*

---

## Objectives
- Normalize features to account for differing scales.  
- Apply PCA to identify principal components that capture most of the variance.  
- Interpret the meaning of top components (e.g., academic quality, financial input, accessibility).  
- Visualize cumulative explained variance to determine the number of components to retain.  

---

## Key Insights
- **PC1** likely represents **financial and academic input dimensions**, including tuition, expenses, and faculty resources.  
- **PC2** may capture **accessibility and scale**, like student-faculty ratio or university size.  
- Retaining components explaining ~85-90% of the variance reduces dimensionality while preserving meaningful information.  

---

## Technologies Used
- **Python**  
- **Pandas & NumPy** for data manipulation  
- **Matplotlib & Seaborn** for visualization  
- **Scikit-learn** for PCA and preprocessing  
- **Jupyter Notebook** for analysis and presentation  

---

## Installation

1. Clone the repository:
```bash
git clone https://github.com/mohitphulwani001/american-university-rankings-pca.git
cd american-university-rankings-pca
