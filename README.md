# ahs_analysis
This repository includes the data and necessary code for a working analysis conducted by the Center for Poverty and Inequality at Georgetown Law (GCPI) examing housing outcomes for renter-occupied units in select metropolitan areas between 2015 and 2023. Contact Zach McRae with any questions at zwm6@georgetown.edu

## The current analysis examines:
- Cost-motivated exits and entries in the metropolitan area
- Net flows by household income and metropolitan area
- Rent changes for households at different Area Median Income (AMI) levels
- Changes in renter-occupied household composition.

## Structure
- `notebooks/`: Jupyter Notebooks with exploratory and final analysis
- `data/`: Input data files
- `outputs/`: Tables, figures, and visualizations for the paper

## Variables and Data Source
| Variable Description | Data Source                   | Years                        | Var Name       |
|----------------------|-------------------------------|------------------------------|----------------|
| Unique Household Identified | American Housing Survey (AHS)     | 2015, 2017, 2019, 2021, 2023 | CONTROL        |
| Respondent-Reported Rent | American Housing Survey (AHS)     | 2015, 2017, 2019, 2021, 2023 | RENT           |
| Recent Mover to Reduce Housing Costs | American Housing Survey (AHS)     | 2015, 2017, 2019, 2021, 2023 | RMCOSTS        |
| Housing Tenure         | American Housing Survey (AHS)     | 2015, 2017, 2019, 2021, 2023 | TENURE         |
| Rent Controlled Unit   | American Housing Survey (AHS)     | 2015, 2017, 2019, 2021, 2023 | RENTCNTRL      |
| Recipient of a Rental Subsidy | American Housing Survey (AHS)     | 2015, 2017, 2019, 2021, 2023 | RENTSUB        |
| Recipient of a HUD Subsidy | American Housing Survey (AHS)     | 2015, 2017, 2019, 2021, 2023 | HUDSUB         |
| CBSA Identifier        | American Housing Survey (AHS)     | 2015, 2017, 2019, 2021, 2023 | OMB13CBSA      |
| Final Weight           | American Housing Survey (AHS)     | 2015, 2017, 2019, 2021, 2023 | WEIGHT         |
| Number of People in Unit | American Housing Survey (AHS)     | 2015, 2017, 2019, 2021, 2023 | NUMPEOPLE      |
| Household Income       | American Housing Survey (AHS)     | 2015, 2017, 2019, 2021, 2023 | HINCP          |
| Year of Survey         | Author Generated                 | 2015, 2017, 2019, 2021, 2023 | SRVYEAR        |
| HUD Area Code          | Income Limit Data (HUD USER)     | 2015, 2017, 2019, 2021, 2023 | hud_area_code  |
| HUD Area Name          | Income Limit Data (HUD USER)     | 2015, 2017, 2019, 2021, 2023 | hud_area_name  |
| Fiscal Year of Income Limits | Author Generated             | 2015, 2017, 2019, 2021, 2023 | il_fiscal_year |
| HUD Area Median Income | Income Limit Data (HUD USER)     | 2015, 2017, 2019, 2021, 2023 | median_income  |
| 1–8 Person 50% Income Limits | Income Limit Data (HUD USER) | 2015–2023                    | l50_1 to l50_8 |
| 1–8 Person 30% Income Limits | Income Limit Data (HUD USER) | 2015–2023                    | ELI_1 to ELI_8 |
| 1–8 Person 80% Income Limits | Income Limit Data (HUD USER) | 2015–2023                    | l80_1 to l80_8 |
| 30% AMI Income Threshold | Author Generated               | 2015, 2017, 2019, 2021, 2023 | ELI_threshold  |
| 50% AMI Income Threshold | Author Generated               | 2015, 2017, 2019, 2021, 2023 | VLI_threshold  |
| 80% AMI Income Threshold | Author Generated               | 2015, 2017, 2019, 2021, 2023 | LI_threshold   |
| AMI Based on Income Limits | Author Generated             | 2015, 2017, 2019, 2021, 2023 | AMI            |

Links to the data are provided below:
- American Housing Survey (AHS): https://www.census.gov/programs-surveys/ahs/data.html
- HUD Income Limits: https://www.huduser.gov/portal/datasets/il.html

The full codebook for the American Housing Survey (AHS) can be found here: https://www.census.gov/data-tools/demo/codebook/ahs/ahsdict.html

Note: The API function to access HUD's Income Limit data requires a personalized API Key. That is not provided in the code and can be accessed here: https://www.huduser.gov/portal/dataset/fmr-api.html  

