# zaxbys-analysis
# Zaxby's Economic and Mobile Tracking Data Analysis

## Project Overview
This repository houses two comprehensive projects analyzing Zaxby's, a prominent fast-casual restaurant chain, focusing on economic analysis and mobile tracking data insights. The projects leverage nationwide datasets spanning 2018 to 2022, utilizing Python and Jupyter Notebooks for in-depth analysis.

## Datasets
The datasets are weekly patterns CSV files for the entire US from 2018 to 2022, specifically tailored to investigate patterns related to Zaxby's. They were sourced from SafeGraph and have been processed in this project to focus on Zaxby's locations and related metrics.

## Part 1: Mobile Tracking Data Analysis

### Objective
To analyze mobile tracking data, focusing on Zaxby's presence in a specified State. This part aims to understand the scope of Zaxby's influence and activity through mobile data patterns.

### Tasks
- **Data Preparation**: Nationwide data is read and processed to create a "wide sample" focused on Zaxby's.
- **Analysis**: The project examines the total observations across datasets, subsets for Zaxby's, and analyzes the unique places observed versus expected for the chain.
- **Output**: The final "wide sample" is saved as a CSV for further analysis.

## Part 2: Economic Analysis

### Objective
Building upon the mobile tracking data analysis, this part delves into economic implications, visualizing daily visits, examining the geographic distribution of visits, and assessing the impact of COVID-19 on customer behavior.

### Tasks
- **Data Verification**: Verifies the long data created from raw datasets, focusing on daily visits and their distribution over time and geography.
- **Visualization**: Utilizes histograms, pie charts, bar charts, line charts, and box plots to depict various aspects of daily visits, with a keen eye on clarity and readability for all visualizations.
- **Geographic Analysis**: Through a detailed geographic visualization, the project explores the distribution of daily visits across the US, comparing findings against public data on Zaxby's operations.

## Instructions
To run these notebooks, ensure you have Python and Jupyter Notebook installed. Libraries required include pandas for data manipulation and matplotlib and seaborn for data visualization. Detailed steps for each analysis are contained within the Jupyter Notebooks, guiding you through the data processing and visualization phases.

## Contribution
Contributions to this project are welcome. Please submit an issue or pull request with your suggestions or improvements.

## License
This project is released under the MIT License.

## Contact
For any questions or feedback, please contact Bilal Akbar at bilalakbar10@gmail.com.
