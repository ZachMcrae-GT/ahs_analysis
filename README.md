# ahs_analysis
This repository includes the data and necessary code for a working analysis conducted by the Center for Poverty and Inequality at Georgetown Law (GCPI) that examines housing outcomes for renter-occupied units in select metropolitan areas between 2015 and 2023. Contact Zach McRae with any questions at zwm6@georgetown.edu

## Analysis
The American Housing Survey (AHS) is being utilized to answer the following questions:
- **What can we observe from the AHS on changes among renter-occupied housing units, changes in rent for different income groups, and the characteristics of the rental housing units in metropolitan areas that have contributed more to their overall housing stock?**
    - This analysis of the American Housing Survey (AHS) looks at select metropolitan areas with higher shares of newly built housing since 2010.
        - "Supply" Cohort
            - Atlanta-Sandy Springs-Roswell, GA (12060)
            - Dallas-Fort Worth-Arlington, TX (19100)
            - Houston-The Woodlands-Sugar Land, TX (26420)
            - Phoenix-Mesa-Scottsdale, AZ (38060)
            - Seattle-Tacoma-Bellevue, WA (42660)
            - Washington-Arlington-Alexandria, DC-VA-MD (47900)
    - Other groupings of metropolitan areas **_may be_** used for comparisons
        - "Group A" Cohort
            - Boston-Cambridge-Quincy, MA-NH (14460)
            - Los Angeles-Long Beach-Anaheim, CA (31080)
            - Miami-Fort Lauderdale-West Palm Beach, FL (33100)
            - New York-Newark-Jersey City, NY-NJ-PA (35620)
            - Riverside-San Bernardino-Ontario, CA (40140)
            - San Francisco-Oakland-Hayward, CA (41860)
        - "Group B" Chort
            - Chicago-Naperville-Elgin, IL-IN-WI (16980)
            - Detroit-Warren-Dearborn, MI (19820)
            - Philadelphia-Camden-Wilmington, PA-NJ-DE-MD (37980) 
        - "Other" Cohort
            - All other metropolitan areas (99998)
            - Not in a metropolitan area (99999)

Using the longitudual data of the American Housing Survey, the analysis will identify cohorts of rental units that were occupied by lower-income households and observe any changes throughout the panel data.

**Research Questions:**
1. Which of the metropolitan areas available in the AHS dataset have built the most units since 2010? 
2. What does the new rental and ownership stock look like compared to building patterns in previous decades?
    - What were the rent levels across the housing stock in 2023?
    - How have median rents changed throughout the housing stock from 2015 - 2023?
3. Are vacancy rates higher for newer units? 
    - What are the rents for vancant units?
4. Which income groups (defined by Area Median Income) are occupying different segments of the housing stock?
5. Are pubic rental subsidies more prevalent in newer or older housing stock? How has that changed from 2015 - 2023?
6. How has the share of rental housing units occupied by AMI (LI/VLI/ELI) households changed from 2015 - 2023?
    - Visualize by count as well and by household income  
7. Changes in rent for renter-occupied households of market-rate units (i.e., unsubsidized, not income-restricted housing)
    - How have rents changed for units occupied by unassisted lower-income households (<= 80% AMI) in relation to units occupied by higher-income households (>80 AMI)? 
    - What is the percent change of rent for renter occupied units in each income group over time (2015-2023)?
    - Are rent increases higher for ELI, VLI, or LI renter-occupied units than for units occupied by higher-income renters?
    - How has rents growth occured for ELI, VLI, LI renter-occupied units in relation to one another using 2015 as a baseline (cumulative growth)?
    
## Structure
- `notebooks/`: Jupyter Notebooks with exploratory and final analysis
- `outputs/`: Tables, figures, and visualizations for the paper


## Links to the data are provided below:
- American Housing Survey (AHS): https://www.census.gov/programs-surveys/ahs/data.html
- HUD Income Limits: https://www.huduser.gov/portal/datasets/il.html

The full codebook for the American Housing Survey (AHS) can be found here: https://www.census.gov/data-tools/demo/codebook/ahs/ahsdict.html

Note: The API function to access HUD's Income Limit data requires a personalized API Key. That is not provided in the code and can be accessed here: https://www.huduser.gov/portal/dataset/fmr-api.html  

