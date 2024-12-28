
![Screenshot (188)](https://github.com/user-attachments/assets/d31703c3-1761-4dab-9e5f-24bc84c748f6)

## Problem Statement

The Midwestern United States is home to numerous industrial facilities that play a critical role in sustainability efforts, including waste management, recycling, and energy recovery. Despite significant progress in some areas, the region faces challenges such as:

- Uneven adoption of sustainability practices across states.
- Disparities in waste production and recycling efforts among facilities.
- Underutilized opportunities for energy recovery.
- Lack of actionable insights for prioritizing improvement efforts.

This report aims to analyze sustainability metrics for facilities in Midwestern states to identify leaders and laggards, uncover inefficiencies, and provide actionable recommendations to enhance sustainability performance.

## Essence of the Report
This analysis focuses on:

- Highlighting Key Metrics: Examining waste production, recycling efforts, and energy recovery across facilities.
- Driving Data-Driven Decisions: Providing insights to help stakeholders target underperforming facilities and regions.
- Promoting Sustainability: Supporting efforts to achieve waste reduction and improved recycling rates while optimizing energy recovery.
- The report combines dynamic visualizations and interactivity to enable stakeholders to filter data by state, year, and facility name, offering a comprehensive view of sustainability performance.

## Data Cleaning Process
The raw dataset contained a wealth of information but also presented challenges such as irrelevant columns, mixed data types, and missing values. The data cleaning was conducted in Python using the pandas library, which provided robust tools for handling and transforming the dataset. Below are the steps taken to prepare the data for analysis in Power BI:

## Selection of Relevant Columns:

Focused on key sustainability metrics: waste production, recycling (on-site and off-site), energy recovery (on-site and off-site), and production ratios.
Included geographical fields like state, county, and city for regional analysis.
Renaming Columns:

Simplified column names to make them easier to interpret in Power BI (e.g., renaming 113. 8.2 - ENERGY RECOVER ON to Energy Recovery On-Site).

## Data Type Conversion:

Converted numeric fields like Energy Recovery On-Site and Total Waste Production to appropriate data types to ensure accurate calculations.
Handling Missing Values:

Dropped rows with missing critical fields such as State and Total Waste Production to maintain data integrity.
Filtering for Midwest States:

Focused the dataset on Midwestern states, including Illinois, Indiana, Iowa, Kansas, Michigan, Minnesota, Missouri, Nebraska, North Dakota, Ohio, South Dakota, and Wisconsin.
Saving the Cleaned Dataset:

Exported the cleaned dataset as a CSV file for seamless import into Power BI.
Analysis and Visualization
The report’s visualizations address the following key analyses:

## Uneven Sustainability Performance Across States:

Maps and bar charts highlight variations in waste production, recycling, and energy recovery across Midwestern states.
Facilities with High Waste Production:

Tree maps and tables identify facilities contributing the most to waste, providing targets for waste reduction initiatives.
Inconsistent Recycling Efforts:

Clustered bar charts compare on-site and off-site recycling rates by facility, revealing disparities and potential areas for improvement.
Ineffective Energy Recovery:

Scatter plots visualize the relationship between waste production and energy recovery, pinpointing underperforming facilities.

## Conclusion
This report provides a comprehensive overview of sustainability performance in the Midwest. It equips stakeholders with actionable insights to drive improvements in waste management, recycling, and energy recovery. By identifying key areas of inefficiency and disparity, the report supports informed decision-making and fosters progress toward a more sustainable industrial ecosystem.
