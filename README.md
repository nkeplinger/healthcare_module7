# healthcare_module7

## WELCOME
Welcome to our team project reapo for module 7. We have decided to analyze an open source dataset that has captured staff shortages among hospitals across the country from Jan 2020 through Desember 2022 along with additional metadata. Our goal was to rearch possible commonalities and trends among staff shortages and other hospital data. 

## REPO ARCHITECTURE
# Source Data
Source data was pulled from https://healthdata.gov/Hospital/COVID-19-Reported-Patient-Impact-and-Hospital-Capa/g62h-syeh
There is an available API, but we grabbed the data as a CSV for ease of importaing and version control. 
This file is located in `Resources/COVID_staff_shortages.csv`

### Individual project code
Individually we all decided to tackle a research questions and work through a personalized Jupiter Notebook. These individual pieces are located in `group_working_code/`. There are 4 files, one for each team member to work with.

### Final Code
Our final code has been merged together into a final file `final_data_analysis_and_vizualization.ipnb`. This file consists of all merge code from individual group members to generate all the data analysis and supporting visuals 

### Supporting Images 
All supporting images were output and saved in the `output/` directory. These ouptputs were used to generate our final report summary and presentation. Figure numbers correspond to the reasearch topic they are supporting. 

### Presentaiton
A powerpoint presenation presented was submitted on the bootcamp spot submission portal. 

### Final Summary
A summary of all findings can be found in the `Summary_doc/` directory. This data references figures found in the `output/` directory.

# RESEARCH SUMMARY
We Broke our data into four research topics to better uncover trends associated with staff shortages in hospitals from 2020 to 2022. After initial data exploration we each developed hypotheses to test:

## Topic 1: (Dylan) 

__Null 1.1:__ There was no relationship between seasons and staffing shortage. 
__Alternative 1.1:__ There was a relationship between the seasons and staffing shortages.
__Result Summary:__ the pearson coefficient and p-value indicate we can reject the null hypothesis.

__Null 1.1:__ There was no relationship between day of the year and staffing shortage. 
__Alternative 1.1:__ There was a relationship between the day of the year and staffing shortages.
__Result Summary:__ the linear regression r-squared value indicates we can reject the null hypothesis.

__Null 1.1:__ There was no relationship between day of the week and staffing shortage. 
__Alternative 1.1:__ There was a relationship between the day of the week and staffing shortages.
__Result Summary:__ the pearson coefficient and p-value indicate we can reject the null hypothesis.

## Topic 2: (Raelle) Staff Shortages Vs. Covid Deaths from 2020 to 2022?

__Null 2.1:__ There is no relationship between staff shortages and covid deaths from 2020 to 2022
__Alternative 2.1:__ Covid deaths having a significant impact on hospital staff or shortage or vice versa.

__Result Summary:__ Data figures  Figure 2.3 shows a negative correlation between Covid Deaths vs Covid Deaths. Figure 2.1. There is an outlier in the NY data for Q2 of 2022.Figure 2.6. The TX data is spread more evenly.
 
## Topic 3: (Nicolette) Staff shortages Vs. Adult and Pediatric Patient Numbers

__Null 3.1:__ There is no relationship between staff shortages and inpatient occupancy (Adult and/or Pediatric) from 2020 to 2022 in the US
__Alternative 3.1:__ There is a relationship between critical staff shortages and adult and/or pediatric inpatient occupancy from 2020 to 2022

__Result Summary:__ These data (Figures 3-1, 3-1a-f) supports the alternative hypothesis that there is a relationship between critical staff shortages and adults and pediatric inpatient occupancy from 2020 to 2022, with the exception of pediatric patients in 2020. 

__Null 3.2:__ There is no relationship between staff shortages and confirmed covid cases (Adult and/or Pediatric) from 2020 to 2022 in the US
__Alternative 3.2:__ There is a relationship between critical staff shortages and confirmed covid cases in adult and/or pediatrics from 2020 to 2022

__Result Summary:__ These data (Figures 3-2a-e) supports the alternative hypothesis that there is a relationship between critical staff shortages and BOTH pediatric and adult confirmed covid cases in US hospitals from 2020 to 2022. 



## Topic 4: (Iqra)

__Null 4.1:__ 4 There is no relationship between the number of states in a hospital and average critical staffing shortage per state.
__Alternative 4.1:__ There is a relationship seen the number of in a hospital, and the average critical staffing per state.

__Result Summary:__ These data (Figure 4-1 and 4-2) support that there is a positive correlation, where the more hospitals there are, the more average critical staffing shortages there are per state

 Null 4.2: There is no relationship between the number of hospitals in a state and the % occupancy of inpatient beds
 Alternative 4.2: There is a relationship between the number of hospitals in a state and the % occupancy of inpatient beds

# Thanks from the team :)
