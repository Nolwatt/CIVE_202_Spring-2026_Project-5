# CIVE_202_Spring-2026_Project-5

## This includes files for Project no. 5:
- [Scope of Work](CIVE_202_Project_5_SOW.pdf)
- [Gantt Chart](CIVE__202_Project_5_Gantt_Chart.xps)
- [Project Timesheet](CIVE_202_Project_5_Timesheet.xps)
- [Annotated Code Document](CIVE_202_Spring-2026_Project-5_ACD)
- [Written Report](CIVE_202_Project_5_Group_#_ProjectReport.docx.pdf.pdf)
- [Python Code](CIVE_202_Spring-2026_Project-5_Group-7_Code_Group.ipynb)

---
## Overview
Our group has previously completed a risk analysis for Risk Averse, LLC, and they liked our work, so they hired us again to examine a specific natural hazard across 6 different states in one region this time. Natural disasters pose significant risks to communities across the United States, impacting infrastructure, economies, and vulnerable populations. To assess these risks, the Federal Emergency Management Agency (FEMA) developed the National Risk Index (NRI), which evaluates risk using Expected Annual Loss, Social Vulnerability, and Community Resilience. We will use the NRI risk definitions and the NRI census tract data for analysis. Risk Averse, LLC also wants us to tract data and information about impacted populations by natural hazards. The project also looked at how population and community vulnerability may affect the impact of natural disasters. Maps and graphs were used to clearly show patterns and make the information easier to understand.

## Project Tasks:

### 1. Clean data
*	Our team will download the National Risk Index (NRI) Census Tract dataset from the FEMA data resources website, along with the NRI Data Dictionary and Hazard Information files. The CDC Social Vulnerability Index (SVI) dataset will also be obtained. All datasets will be reviewed in Python to confirm they are properly structured for analysis.

### 2. Filter data by 6 states and one Natural Disaster type
*	Maine, New Hampshire, Vermont, Massachusetts, Rhode Island, and Connecticut
*	Risk or winter weather

### 3. Summarize data for natural disaster of our choice
*	Using Python with the matplotlib and GeoPandas libraries, our team will create visualizations of tables and plots for each state and the region.

### 4. Analysis of the risk to population and regional trends
*	Using Python with the pandas and numpy libraries, our team will analyze the NRI dataset for each state. Summary statistics including mean, median, minimum, and maximum values will be calculated for key variables such as Expected Annual Loss, Social Vulnerability, Community Resilience, and NRI Risk Scores for winter weather. This analysis will help identify trends and differences in risk distribution across the region.

### 5. Compare high risks to population density
*	Using the data collected from our code using the risk score calculations, we will compare the high risk of winter weather to population density.

## Methods
* The analysis was completed in Python using several data science and visualization 
libraries, including Pandas, NumPy, Matplotlib, Seaborn, and GeoPandas.FEMA Census Tract datasets and map shapefiles were imported and cleaned before analysis. Invalid values, such as -9999, were removed or replaced to improve the accuracy of the data. 
* The dataset was filtered to include only the six selected New England states. The winter 
weather risk variable (WNTW_RISKV) was used to compare hazard levels across census 
tracts. Geographic map data was also adjusted into a consistent format so accurate maps 
could be created. 
* Several maps and graphs were generated to compare winter weather risk between states 
and identify regional trends. Functions were created in the code to organize repeated tasks 
such as filtering data and generating visualizations. The project also included discussions 
about possible bias in the datasets and how coding decisions may affect the final results.

## Discussions
* The results showed clear differences in winter weather risk across the New England region. 
Northern states such as Maine, Vermont, and New Hampshire generally had higher winter 
weather risk values than southern states such as Rhode Island and Connecticut. 
Massachusetts showed mixed results depending on the area being analyzed.

* The maps and graphs showed that geography and climate play a major role in winter 
weather risk. Areas with harsher winters and more rural communities often showed higher 
risk levels. Population density and social vulnerability may also affect how strongly 
communities are impacted during severe winter weather events.

Overall, the project successfully used programming, data cleaning, and mapping tools to 
analyze natural hazard risk across the region. The visualizations helped explain regional 
differences in winter weather risk and showed how environmental data can be used to 
better understand and prepare for natural disasters. 
