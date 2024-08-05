K-Means Clustering on Survey of Consumer Finances (SCF)
Overview

This project aims to segment households using the Survey of Consumer Finances (SCF) data, specifically focusing on individuals that have "been turned down for credit or feared being denied credit." These individuals are identified in the "TURNFEAR" column. By identifying distinct segments within this group, we can gain insights into their financial behaviors and characteristics, which can help in policy making, financial product development, and economic research.
Project Structure

Data : Contains the dataset used for the analysis.
Dataset

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

Methodology

    Exploratory Data Analysis (EDA)

    Understand the distribution of features Identify missing values and outliers Visualize relationships between features

    Data Preprocessing

    Handle missing values Standardize numerical features

    Feature Selection

    Select relevant features for clustering Use techniques like PCA for dimensionality reduction

    K-Means Clustering

    Determine the optimal number of clusters using the Elbow Method, Inertia and Silhouette Score Apply K-Means clustering to segment households

    Results and Visualization

    Visualize clusters Deploy a Dash web application for interactive exploration of household segments

Results
The K-Means clustering identified several distinct household segments within the group of individuals that have been turned down for credit or feared being denied credit. The interactive Dash application allows users to explore these segments in detail.
