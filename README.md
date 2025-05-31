# PCA and Factor Analysis Political Opinion

This repository presents an exploratory data analysis and multivariate statistical modeling project, focused on uncovering the complex dimensions of political opinions in the United States. By leveraging Principal Component Analysis (PCA) and Factor Analysis (FA) on survey data from the Pew Research Center, the project identifies latent structures that influence public attitudes on key societal issues.

## 📊 Project Overview

Political opinions are often classified using simple labels like "liberal" or "conservative." However, this oversimplification may overlook the nuanced perspectives within a population. This project aims to explore political opinion as a multidimensional construct by:

- Applying PCA and Factor Analysis to survey data.
- Identifying key latent factors influencing political attitudes.
- Visualizing and interpreting the factors for actionable insights.

## 🔍 Data Source

The dataset used in this project comes from the [Pew Research Center](https://www.pewresearch.org/), a nonpartisan organization that conducts public opinion polling. The data was originally provided in SPSS format (`.sav`) and contains responses from a broad U.S. population sample on various political, economic, and social topics.  
*Note: The dataset is included in this repository for reference purposes only.*

## 🧰 Methods and Workflow

1. **Data Preparation**
   - Extracted relevant survey questions related to political opinions (columns 26–98).
   - Removed columns with excessive missing values; applied dummy encoding to categorical variables.

2. **Dimensionality Reduction**
   - Performed PCA to reduce dimensionality while retaining variance.
   - Identified the optimal number of components using scree plots and cumulative variance analysis.

3. **Factor Analysis**
   - Conducted Factor Analysis on selected components.
   - Applied varimax rotation to simplify factor loadings.
   - Interpreted factors based on high-loading variables (threshold: 0.4).

4. **Key Findings**
   - Seven key dimensions of political opinion were identified:
     - Trust in government and economic systems
     - Social fairness concerns
     - Foreign policy stances
     - Tax fairness perspectives
     - Emotional reactions to governance
     - Perceptions of discrimination
     - The role of religion in politics

## 📈 Visualizations

The repository includes data visualizations such as:

- Scree plots for PCA component selection.
- Factor loadings heatmaps.
- Bar charts summarizing factor themes and high-loading variables.
