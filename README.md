NYC Crime Prediction & Spatial Analytics 
Project Overview
In this project, I performed a deep-dive analysis of over 200,000+ NYPD crime records. As a 3rd-year AI student, my goal was to bridge the gap between raw urban data and actionable predictive insights. I built an end-to-end pipeline that visualizes crime density and predicts the severity of offenses based on spatial and temporal features.

Key Features & Workflow
Data Engineering: Cleaned and preprocessed a massive dataset using Pandas, handling missing values and performing feature extraction (e.g., peak hour analysis).

Spatial Intelligence: Developed interactive Heatmaps using Folium to pinpoint high-density crime "hotspots" across New York City.

Predictive Modeling: Implemented a Random Forest Classifier to categorize crime severity (Felony, Misdemeanor, Violation).

Imbalance Handling: Applied Class Weight Balancing techniques to ensure the model accurately recognizes rare but severe crimes, moving beyond simple majority-class guessing.

Technical Stack
Language: Python 

Libraries: Pandas, Scikit-Learn, Folium, Matplotlib, Seaborn.

Environment: Google Colab / Jupyter Notebook.

Key Highlights & Insights
Temporal Patterns: Identified specific hours of the day where certain crime types peak.

Spatial Density: Successfully mapped how crime types shift between different boroughs and coordinates.

Performance: Optimized the model to handle the inherent "noise" and imbalance found in real-world governmental datasets.

How to Run
Clone this repository.

Install dependencies: pip install pandas scikit-learn folium matplotlib.

Run the .ipynb notebook to see the visualizations and model performance.
