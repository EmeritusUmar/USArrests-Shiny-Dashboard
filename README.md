# USArrests Shiny Dashboard

This interactive Shiny dashboard delves into the **USArrests** dataset, presenting crime statistics for the 50 U.S. states in 1973. It offers various data visualizations and analytical tools to examine arrest rates for **Murder**, **Assault**, and **Rape**, alongside the percentage of the population residing in urban areas.

## Web app :

You can access the live version of the dashboard at: [USArrests Shiny Dashboard](https://umarmusa.shinyapps.io/1973_us_arrest/)


## Features

- **Dataset Overview**: Access comprehensive summaries and understand the structure of the dataset.
- **Visualizations**:
  - **Crime Trends by State**: Analyze bar charts illustrating crime trends across different states.
  - **Distribution**: Examine histograms and box plots depicting the distribution of crime rates.
  - **Correlation Matrix**: Investigate the relationships between various crime types through an interactive correlation matrix.
  - **Relationships**: Explore scatter plots highlighting correlations between crime types and urban population percentages.
- **Choropleth Map**: Visualize arrest rates for specific crime types across U.S. states using a choropleth map.

## Dataset

The `USArrests` dataset, included in the base R distribution, provides:

- Arrest counts per 100,000 residents for **Assault**, **Murder**, and **Rape**.
- The percentage of the population living in urban areas for each state.

## How to Run

To launch this Shiny application:

## 1. Clone the Repository:

   ```bash
   git clone https://github.com/EmeritusUmar/USArrests-Shiny-Dashboard.git
   ```

## 2. Install Required Packages

Before running the application, ensure that you have the following R packages installed:

```r
install.packages(c("shiny", "shinydashboard", "DT", "dplyr", "plotly", "ggplot2", "ggtext", "maps", "ggcorrplot", "shinycssloaders"))
```

## 3. Run the Application

To run the Shiny dashboard, use the following command in your R console:

```r
shiny::runApp("path_to_your_app_directory")
```
Replace "path_to_your_app_directory" with the actual path where your ui.R, server.R, and global.R files are located. Once the application is running, it will open in your web browser, allowing you to explore the 1973 US Arrests data interactively.

This will start the Shiny app, accessible via your web browser.

# File Structure
- **ui.R**: Defines the user interface, encompassing tabs for dataset viewing, visualizations, and the choropleth map.
- **global.R**: Loads necessary libraries and prepares the dataset for analysis.
- **server.R**: Contains server-side logic for rendering data tables, plots, and interactive components.
- **www/**: Houses static assets, including images used in the dashboard.

# Dashboard Tabs

## Dataset
- **About**: Provides an overview of the dataset.
- **Data**: Displays the dataset in an interactive table format.
- **Structure**: Shows the structure of the dataset.
- **Summary Stats**: Offers summary statistics of the data.

## Visualization
- **Crime Trends by State**: Bar charts illustrating crime trends by state.
- **Distribution**: Histograms and box plots representing the distribution of crime rates.
- **Correlation Matrix**: Interactive matrix displaying correlations between different crime types.
- **Relationships**: Scatter plots exploring relationships between crime types and urban population percentages.

## Choropleth Map
- **Arrests by Crime Type**: Choropleth map visualizing crime rates across U.S. states.

# Credits
- **Data**: The USArrests dataset is part of the base R distribution.
- **Image**: The crime-related image is sourced from Campbell Jensen on Unsplash.

# Contact
For further information or inquiries:

- **LinkedIn**: [Umar Musa](https://www.linkedin.com/in/your-profile)  
- **GitHub**: [USArrests Shiny Dashboard Repository](https://github.com/your-repo)
