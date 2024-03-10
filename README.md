# NCDC Covid-19 Data Analysis
![](images/Covid-19_image.jpg)


## Project Overview

### Introduction:
The NCDC Covid-19 Data Analysis project aims to provide insightful analysis and visualizations based on the data collected by the Nigerias' National Center for Disease Control (NCDC) related to the Covid-19 pandemic. The project focuses on extracting meaningful insights to aid decision-making processes, public health strategies, and research initiatives.


### Objectives:
- To compile and analyze the data on the number of Covid-19 tests conducted by individual states across Nigeria.
- To systematically gather and assess information regarding the number of confirmed Covid-19 cases reported by each state in Nigeria.
- To accurately track and monitor the number of active Covid-19 cases present in each state of Nigeria.
- To document and analyze data pertaining to the number of Covid-19 recoveries reported by individual states across Nigeria.
- To meticulously record and analyze the number of Covid-19 related deaths reported by each state within Nigeria.
- To develop an interactive geospatial map illustrating the distribution of confirmed Covid-19 cases and Covid-19 related deaths across the various states of Nigeria.


### Expected Outcomes:
- __Enhanced understanding of the testing terrain:__ By compiling and analyzing the data on Covid-19 tests conducted by individual states across Nigeria, the project will provide insights into the testing capacity, trends, and disparities among states.
- __Comprehensive assessment of the Covid-19 situation:__ The systematic gathering and assessment of information regarding confirmed Covid-19 cases reported by each state will enable a comprehensive understanding of the spread and severity of the pandemic across Nigeria.
- __Real-time monitoring of active cases:__ Accurate tracking and monitoring of active Covid-19 cases in each state will facilitate timely interventions and resource allocation to manage and contain the spread of the virus effectively.
- __Evaluation of recovery rates:__ Documenting and analyzing data on Covid-19 recoveries reported by individual states will enable the assessment of healthcare system effectiveness, treatment protocols, and recovery trends across Nigeria.
- __Insights into mortality patterns:__ Meticulous recording and analysis of Covid-19 related deaths reported by each state will provide insights into mortality rates, vulnerable populations, and the effectiveness of public health measures in mitigating fatalities.
- __Visual representation of spread:__ The development of an interactive geospatial map illustrating the distribution of confirmed Covid-19 cases and related deaths across states will facilitate visualization of the pandemic's geographic spread, aiding in risk assessment, decision-making, and public awareness efforts.


### Dataset Overview
The Nigeria Centre for Disease Control and Prevention (NCDC) is the national public health institute with the mandate to lead the preparedness, detection and response to infectious disease outbreaks and public health emergencies. This organization played an active role during the peak period of the pandemic and are still actively playing that role till date. There mission is to protect the health of Nigerians through evidence-based prevention, integrated disease surveillance and response activities, using a one health approach, guided by research and led by a skilled workforce. This dataset was sourced from the NCDC general fact sheet- data as at 26th february, 2023 when it was last updated, and includes detailed information such as number of covid-19 tests carried out by states, confirmed cases by state, active cases by state, births, recoveries by state, and the pandemic death toll by state.

This dataset is made up of a single table with 9 columns and 36 rows of data representing the 36 states of Nigeria. Below is the information abount the columns in this dataset:
- __State:__ The name of the state within Nigeria where Covid-19 cases are reported.
- __Confirmed:__ The total number of confirmed Covid-19 cases reported in the respective state since the beginning of the pandemic.
- __Confirmed (Last 2 Weeks):__ The number of confirmed Covid-19 cases reported in the respective state within the last two weeks, providing a more recent snapshot of the spread.
- __Recoveries:__ The total number of individuals who have recovered from Covid-19 in the respective state since the beginning of the pandemic.
- __Recoveries (Last 2 Weeks):__ The number of individuals who have recovered from Covid-19 in the respective state within the last two weeks, indicating recent recovery trends.
- __Deaths:__ The total number of deaths attributed to Covid-19 in the respective state since the beginning of the pandemic.
- __Deaths (Last 2 Weeks):__ The number of deaths attributed to Covid-19 in the respective state within the last two weeks, reflecting recent mortality patterns.
- __Active Cases:__ The current number of active Covid-19 cases in the respective state, calculated as (Confirmed - Recoveries - Deaths).
- __Testing:__ The total number of Covid-19 tests conducted in the respective state since the beginning of the pandemic, indicating testing efforts and capacity.
- __Testing (Last 2 Weeks):__ The number of Covid-19 tests conducted in the respective state within the last two weeks, reflecting recent testing activities and trends.


### Skills Utilized
1. Data Transformation
2. Data Visualiziation
3. Descriptive Analytics
4. Critical Thinking and Problem Solving
5. Communication and Reporting


### Tools Used
1. Microsoft Excel
    - Was used to:
        1. Was used to save extracted data from NCDC website,
        2. Transform,
        3. Load the dataset for this analysis.
     
2. Tableau (Was used to create dashboards for this analysis)
    - The following Tableau were incorporated:
        1. Calculated Fields
        2. Geospatial Analysis
        3. Page Navigation
        4. Filters
        5. Tooltips
        6. Buttons


### Data Transformation and Loading in Microsoft Excel and Tableau:
- Did the first data cleaning in Microsoft excel before loading the dataset to Tableau.
- Changed the data types to the appropriate data types in Tableau.
- Divided the grouped __"CONFIRMED"__ column into __"Confirmed"__ and __"Confirmed (Last 2 Weeks)"__ in Tableau.
- Divided the grouped __"RECOVERIES"__ column into __"Eecoveries"__ and __"Recoveries (Last 2 Weeks)"__ in Tableau.
- Divided the grouped __"DEATHS"__ column into __"Deaths"__ and __"Deaths (Last 2 Weeks)"__ in Tableau.
- Divided the grouped __"TESTING"__ column into __"Testing"__ and __"Testing (Last 2 Weeks)"__ in Tableau.


**Tableau Data View**

Tableau Data Screenshot                                                             |                                
:---------------------------------------------------------------------------------:|
![](images/Tableau_Data_Screenshot.png)


## Join/ Blend Data
There was no need to join or blend data as we have just a single table for this analysis.


## Tableau Visualization:
#### Dashboard View 1
![](images/NCDC_COVID-19_DATA_ANALYSIS1.png)

#### Dashboard View 2
![](images/NCDC_COVID-19_DATA_ANALYSIS2.png)
