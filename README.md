# unsupervised-learning-final-project
Final project for Unsupervised Learning: Customer Segmentation



## Project Overview
This project applies **unsupervised learning** methods to segment mall customers based on age, income, and spending score.

- **Dataset**: Mall Customers (200 records, Age, Income, Spending Score, Gender)
- **Methods**: KMeans, Gaussian Mixture Models (GMM), DBSCAN
- **Goal**: Identify customer segments for targeted marketing strategies

## Deliverables
1. **Jupyter Notebook**: [`UnML.ipynb`](./UnML.ipynb)  
2. **HTML Report**: [`UnML.html`](./UnML.html)  
3. **Presentation Script**: [`presentation_script.md`](./presentation_script.md)  
4. **Video Presentation**: [YouTube Link](https://youtu.be/xxxx) (or .mp4 file if required)  

##  Key Results
- Best model: **GMM with 4 clusters** (selected by BIC)
- KMeans (5 clusters) is intuitive and business-friendly
- DBSCAN detects noise and anomalies

##  Future Work
- Incorporate gender and other demographics
- Use t-SNE/UMAP for visualization
- Validate with business KPIs such as campaign response or CLV
