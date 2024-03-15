# Computational Social Science Project: Analysis & Automated Valuation of German Real Estate
## The Project
This work is a project for a Computational Social Science lecture at the LMU. The Professor in charge of the course is [Christoph Kern (LMU)](https://www.stat.lmu.de/soda/en/team/contact-page/christoph-kern-11bd67d0.html).

### Introduction
The German real estate market plays a crucial role in the country's economy, experiencing significant growth and transformation in recent years. With the emergence of prominent online platforms for real estate advertising, there has been a shift towards greater transparency and liquidity in both sales and rental markets. Leveraging detailed data from various online real estate platforms, this study aims to provide insights into the German real estate landscape.

### Objectives
Investigate variations in apartment and house rental prices across different regions of Germany.
Identify factors influencing rental pricing to better understand the German real estate market.
Evaluate the efficacy of machine learning models in predicting rental prices based on internal and external features.
Provide visualizations depicting rental prices across Germany to highlight regional disparities within the real estate market.
Methodology
Data collection: Scraping data from prominent German real estate websites such as 'immonet.de', 'kleinanzeigen.de', and 'engelvoelkers.de'.
Feature engineering: Isolating spatial features from the models to analyze location effects on rental prices.
Model development: Utilizing tree-based bagging and boosting ensembling methods, particularly XGBoost, to predict rental prices.
Visualization: Leveraging OpenStreetMaps to visualize rental prices across Germany.
Key Findings
Areas around prominent cities such as Munich, Hamburg, Frankfurt, and Berlin exhibit the highest rental prices.
Interior size and zip code are identified as the most important features influencing apartment and house prices.
The XGBoost model outperforms CatBoost and Random Forest Regressor models, achieving superior predictive accuracy.
Repository Structure
data: Contains datasets used in the analysis.
notebooks: Jupyter notebooks documenting the data analysis process.
visualizations: Visualization outputs, including heatmaps and scatter plots.
models: Trained machine learning models for rental price prediction.
README.md: Overview of the project and repository contents.
Getting Started
To explore our analysis and findings, you can navigate through the notebooks and visualizations provided in this repository. Additionally, feel free to clone or download the repository to your local machine for further exploration.

Contributors
[Your Name]
[Collaborator Name]
We hope you find our analysis insightful and informative. If you have any questions or feedback, please don't hesitate to reach out.

Thank you for visiting!
