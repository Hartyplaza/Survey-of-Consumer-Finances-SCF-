# K-Means Clustering on Survey of Consumer Finances (SCF)
## Overview

This project aims to segment households using the Survey of Consumer Finances (SCF) data, specifically focusing on household that have "been turned down for credit or feared being denied credit." These households are identified in the "TURNFEAR" column. By identifying distinct segments within this group, we can gain insights into their financial behaviors and characteristics, which can help in policy making, financial product development, and economic research.


### Project Structure

[data](https://drive.google.com/file/d/18JFOTNY3d_lS1Z53Fscu5l2HHlO7-rsy/view?usp=drive_link): Contains the dataset used for the analysis.
    
## Dataset

The dataset used in this project is from the Survey of Consumer Finances (SCF). It includes various features related to household finances such as income, assets, debts, and demographic information. Key features include:

    Age of head of household
    Household income
    Total assets
    Total debts
    Education level
    Employment status
    Homeownership status
    TURNFEAR (Indicator if the individual has been turned down for credit or feared being denied credit)
    Other financial indicators

### Methodology
1. Exploratory Data Analysis (EDA)

    Understand the distribution of features
    Identify missing values and outliers
    Visualize relationships between features

2. Data Preprocessing

    Handle missing values
    Standardize numerical features

3. Feature Selection

    Select relevant features for clustering
    Use techniques like PCA for dimensionality reduction

4. K-Means Clustering

    Determine the optimal number of clusters using the Elbow Method and Silhouette Score
    Apply K-Means clustering to segment households

5. ## Results and Visualization

    Visualize clusters in 2D and 3D plots
    Deploy a Dash web application for interactive exploration of household segments

   ## Results

The K-Means clustering identified several distinct household segments within the group of households that have been turned down for credit or feared being denied credit. 
The interactive Dash application allows users to explore these segments in detail. Here is a detailed [Report](./kMeans%20project%20on%20consumer%20finance_1.pdf) about the project

### Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes

## Acknowledgements

[Data Source](https://www.federalreserve.gov/datadownload/Choose.aspx?rel=FOR)
## Contact

For any questions or inquiries, please contact [LinkedIn](www.linkedin.com/in/hart-ofigwe) and [Email](ofigwehart@gmail.com).
