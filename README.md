# New York City Immunization Dashboard 

This repository contains data on routine vaccinations administered to New York City (NYC) children ages 0-18 years and reported to the [Citywide Immunization Registry](https://www.nyc.gov/site/doh/providers/reporting-and-services/citywide-immunization-registry-cir.page) https://www.nyc.gov/site/doh/providers/reporting-and-services/citywide-immunization-registry-cir.page (CIR). 

You can view a visualization of these data on the NYC Health Department’s Immunization Data webpage ([link](https://www.nyc.gov/site/doh/misc/sdah-boi-dashboard.page)). 

**This Readme includes the following topics:**

- How to Use This Repository 
- Key Technical Notes 
- Definitions 
- Contents 

## How to Use This Repository   

There are two main datasets that serve as the data sources for all the visualizations displayed on the NYC Immunization Dashboard – one dataset is stratified by individual demographics and the other is stratified by geography. Users can download an individual dataset for each visualization by clicking ‘Get the data’ under the visualization or downloading the full dataset under **‘Repository Content’.** The data dictionary is also available to download in Excel. 

## Key Technical Notes 

**Citywide Immunization Registry:**

Since 1996, the CIR has been used as a database of patient immunization records reported by NYC health care providers and some out-of-state immunization information systems. The CIR keeps immunization records for all city residents – children and adults – throughout their lifespan and has records for non-NYC residents vaccinated in the city. It is accessible to authorized health care providers, schools, individuals and agencies concerned with public health to ensure that NYC residents are up to date with recommended immunizations. NYC health care providers report immunizations to the CIR as mandated by New York State (NYS) Public Health Law and the NYC Health Code. Pediatric providers are required to report all immunizations administered to children 0-18 years. Reporting of adult immunizations requires patient consent. Immunization data are submitted to the CIR through electronic health record systems or the [CIR’s Online Registry.](https://immunize.nyc/prod/online-registry/)

**Childhood Immunization Recommendations**

Making sure children receive all recommended vaccines is important to protect children from acquiring vaccine-preventable diseases and to protect the health of the public. The Advisory Committee on Immunization Practices (ACIP) recommends vaccines against 15 potentially serious diseases by the age of 24 months. Most vaccine series require more than 1 dose with a spacing interval between doses to produce optimal immunity. 

The CIR evaluates vaccine doses and series completion based on the Centers for Disease Control and Prevention’s (CDC’s) recommendations, available at the links below: 

- **Advisory Committee on Immunization Practices (ACIP)** Recommendations 
[Complete list of ACIP vaccine recommendations.](https://www.cdc.gov/vaccines/hcp/acip-recs/index.html) 
- **CDC’s** [Immunization Schedules](https://www.cdc.gov/vaccines/schedules/hcp/index.html) 
Links to the childhood, adolescent, catch-up, and adult immunization schedules; plus vaccine documentation and screening forms. 

**Dashboard Update Schedule**

The NYC Immunization Dashboard displays immunization coverage data for the past five years stratified by race/ethnicity and NYC neighborhood. Additionally, trends in citywide coverage are displayed for the past eight years. Data presented on the NYC Immunization Dashboard are updated twice a year as of June 30 and December 31 of each year. Data are released one to two months after the review date to allow enough time for data to be reported to the CIR and prepared for public sharing. Data are preliminary and subject to change when new population estimates are published. 

## Definition 

Cohorts: 

- Children 
- Adolescents 

Types of vaccines: 

- [Childhood Combined 7-vaccine Series (4 DTaP, 3 Polio, 1 MMR, 3 Hib, 3 HepB, 1 Varicella, 4 PCV)](#seven)
- [Diphtheria and Tetanus Toxoids and Acellular Pertussis Vaccine (DTaP/DT/DTP)](#dtap)
- [Haemophilus Influenzae Type b Vaccine (Hib)](#hib) 
- [Hepatitis B Vaccine (HepB)](#hepb) 
- [Human Papillomavirus Vaccine (HPV)](#hpv)
- [Influenza Vaccine (Flu)](#flu) 
- [Measles, Mumps and Rubella Vaccine (MMR)](#mmr) 
- [Meningococcal Conjugate Vaccine (MenACWY)](#menacwy) - Future 
- [Pneumococcal Conjugate Vaccine (PCV)](#pcv) 
- [Poliovirus Vaccine (Polio)](#polio) 
- [Tetanus, Diphtheria, Acellular Pertussis Vaccine (Tdap)](#tdap) - Future
- [Varicella Zoster (chickenpox) Vaccine (VAR)](#var) 


Data variables: 

**Children**

The NYC Health Department tracks vaccination coverage among NYC children ages 2 years by their 2<sup>nd</sup> birthday.  

Children must meet the following eligibility criteria to be included in the cohort: 

- Between the ages of 24 months 0 days and 35 months 30 days as of the coverage assessment date  
- Received all required doses of the specified vaccine by the date of their 2nd birthday 
- Had a valid NYC ZIP code listed in CIR as of the coverage assessment date  
- Not documented in CIR as having moved or gone elsewhere: moved out of the city or deceased 

For influenza (flu) vaccination, the NYC Health Department tracks coverage and vaccine uptake for children ages 6-months to 4-years and 5-to-12-years. Since the influenza season spans many months, the age criterion for the analysis is based on the child’s age (in days) at the time of the flu vaccination. The CIR calculates a child’s age days by subtracting the child’s date of birth (DOB) from the flu vaccination date.  

Children must meet the following eligibility criteria to be included in the influenza cohort: 

- Received at least one flu vaccine dose during the influenza vaccination season
- Between the ages of 182 and 1825 days (for the 6-month to 4-year-old cohort), between the ages of 1826 and 4747 days (for the 5-to–12-year-old cohort) as of the flu vaccination date 
- Had a valid NYC ZIP code listed in CIR as of the coverage assessment date 
- Not documented in CIR as having moved or gone elsewhere: moved out of the city or deceased 

The denominators for routine and influenza vaccination coverage estimates are based on the most recently available Vintage population estimates. The NYC Health Department produces these estimates using data from the U.S. Census Bureau and incorporates additional data from the NYC Department of City Planning and the NYC Department of Buildings. When new Vintage population estimates are released, vaccination coverage rates on the NYC Immunization Dashboard are adjusted accordingly using the same numerators and the new population estimates. Vaccination data using previous estimates are archived.  
Please note that, in a few cases, the number of children vaccinated may exceed the estimated population resulting in vaccination coverage exceeding 100%. This may happen with smaller demographic categories and geographies.  

**Adolescents**

The NYC Health Department tracks vaccination coverage among NYC adolescents ages 13 to 17 years. For HPV, the NYC Health Department additionally tracks HPV series completion rates for 13-year-olds by the 13<sup>th</sup> birthday to monitor on-time vaccination at ages 11-12 years.  

Adolescents must meet the following eligibility criteria to be included in the 13-17-year-old cohort: 

- Between the ages of 13 years 0 days and 17 years 11 months 30 days as of the coverage assessment date 
- Received all required vaccine doses in the specified vaccine series 
- Had a valid NYC ZIP code listed in CIR as of the coverage assessment date 
- Not documented in CIR as having moved or gone elsewhere: moved out of the city or deceased 

To be included in the cohort of 13-year-olds by the 13<sup>th</sup> birthday, adolescents must meet the following eligibility criteria: 

- Between the ages of 13 years 0 days and 13 years 11 months 30 days as of the coverage assessment date 
- Completed the HPV vaccine series by the date of their 13th birthday. The HPV series is completed with 2 doses of HPV vaccine with an interval of at least 5 months between doses. If the interval between the 1st and 2nd dose is shorter than 5 months, then a 3rd dose is needed to complete the series 
- Had a valid NYC ZIP code listed in CIR as of the coverage assessment date 
- Not documented in CIR as having moved or gone elsewhere: moved out of the city or deceased 

For flu vaccination, the NYC Health Department tracks coverage and vaccine uptake for adolescents ages 13-17-years. Since the influenza season spans many months, age is based on the patient’s age (in days) at the time of vaccination. The CIR calculates a patient’s age days by subtracting the patient’s date of birth (DOB) from the flu vaccination date.  

To be included in the 13-17-year-old influenza cohort, adolescents must meet the following eligibility criteria: 

- Received at least one flu vaccine dose during the influenza vaccination season 
- Between the ages of 4,748 and 6,573 days (equivalent to ages 13-17 years) as of the flu vaccination date 
- Had a valid NYC ZIP code listed in CIR as of the coverage assessment date 
- Not documented in CIR as having moved or gone elsewhere: moved out of the city or deceased 

When new Vintage population estimates are released, vaccination coverage rates on the NYC Immunization Dashboard are adjusted accordingly using the same numerators and the new population estimates. Vaccination data using previous estimates are archived.   

Please note that, in a few cases, the number of adolescents vaccinated may exceed the estimated population resulting in vaccination coverage exceeding 100%. This may happen with smaller demographic categories and geographies. 

**Vaccine Groups**  

<span id="seven"></span>
Childhood Combined 7-vaccine Series (4 DTaP, 3 Polio, 1 MMR, 3 Hib, 3 HepB, 1 Varicella, 4 PCV)

- The combined 7-vaccine series (also known as the 4:3:1:3:3:1:4 series) measures the percentage of children ages 2 years who received all required doses of the CDC’s Advisory Committee on Immunization Practices (ACIP)-recommended vaccines by their 2<sup>nd</sup> birthday. 

- The series includes ≥4 doses of diphtheria and tetanus toxoids and acellular pertussis vaccine; ≥3 doses of poliovirus vaccine; ≥1 dose of measles-mumps-rubella vaccine; ≥3 or ≥4 doses of **Haemophilus Influenzae** Type b vaccine (depending on product type); ≥3 doses of hepatitisB vaccine; ≥1 dose of varicella vaccine; and ≥4 doses of pneumococcal conjugate vaccine.  

- For more information about the 7-vaccine series, visit: Birth-18 Years Immunization Schedule – Healthcare Providers | CDC 

<span id="dtap"></span>
Diphtheria and Tetanus Toxoids and Acellular Pertussis Vaccine (DTaP/DT/DTP) 

- The CDC maintains updated guidelines and recommendations on diphtheria, tetanus and pertussis vaccination (DTaP/DT/DTP). For more information, visit: 

  - https://www.cdc.gov/vaccines/vpd/diphtheria/index.html 
  - https://www.cdc.gov/vaccines/vpd/tetanus/index.html 
  - https://www.cdc.gov/vaccines/vpd/pertussis/index.html 
  
- Vaccination Tracking: By age 24 months, children are recommended to have received four doses of DTaP vaccine. Percent vaccinated is calculated by dividing the number of 24-35-month-olds who have received 4 or more doses of DTaP vaccine by their 2<sup>nd</sup> birthday according to CIR, by the total number of same-aged children in that year according to the most recent Vintage population estimates. 

<span id="hib"></span>
Haemophilus Influenzae Type b Vaccine (Hib) 

- The CDC maintains updated guidelines and vaccine recommendations on Hib vaccination. For more information, visit: https://www.cdc.gov/vaccines/vpd/hib/index.html 
- Vaccination Tracking: By age 24 months, children are recommended to have received 3 or 4 doses of Hib vaccine depending on the vaccine product they received. Percent vaccinated is calculated by dividing the number of 24-35-month-olds who received all required doses of Hib vaccine by their 2<sup>nd</sup> birthday according to CIR, by the total number of same-aged children in that year according to the most recent Vintage population estimates. 

<span id="hepb"></span>
Hepatitis B Vaccine (HepB) 

- The CDC maintains updated  guidelines and vaccine recommendations on Hepatitis B vaccination. For more information, visit: https://www.cdc.gov/vaccines/vpd/hepb/index.html 
- Vaccination Tracking: By age 24 months, children are recommended to have received 3 doses of HepB vaccine. Percent vaccinated is calculated by dividing the number of 24-35-month-olds who received 3 doses of HepB vaccine by their 2<sup>nd</sup> birthday according to CIR, by the total number of same-aged children in that year according to the most recent Vintage population estimates. 

<span id="hpv"></span>
Human Papillomavirus Vaccine (HPV) 

- The CDC maintains updated guidelines and recommendations on HPV vaccination. For more information, visit: https://www.cdc.gov/vaccines/vpd/hpv/index.html 
- Vaccination Tracking: Percent vaccinated is calculated by dividing the number of 13-17-year-olds who received all required doses of HPV vaccine according to CIR, by the total number of same-aged children in that year according to the most recent Vintage Population estimates. On-time vaccination is calculated by dividing the number of 13-year-olds who completed the HPV vaccine series (with 2 or 3 doses) by their 13th birthday according to CIR, by the total number of 13-year-olds in that year according to the most recent Vintage Population estimates.  

<span id="flu"></span>
Influenza Vaccine (Flu) 

- The CDC maintains updated guidelines and recommendations on influenza vaccination. For more information, visit: https://www.cdc.gov/vaccines/vpd/flu/index.html 
- Vaccination Tracking: Percent vaccinated is calculated by dividing the total number of children who received at least one seasonal influenza vaccine during the target flu season according to CIR, by the total number of same-aged children in that year according to the most recent Vintage population estimates. Patient DOB criteria is based on the patient’s age (in days) at the time of the flu vaccination.  

<span id="mmr"></span>
Measles-Mumps-Rubella Vaccine (MMR) 

- The CDC maintains updated guidelines and recommendations on MMR vaccination. For more information, visit:
  - https://www.cdc.gov/vaccines/vpd/measles/index.html
  - https://www.cdc.gov/vaccines/vpd/mumps/index.html
  - https://www.cdc.gov/vaccines/vpd/rubella/index.html
- Vaccination Tracking: By age 24 months, children are recommended to have received one dose of MMR containing vaccine. Percent vaccinated is calculated by dividing the number of 24-35-month-olds who received one MMR vaccine dose by their 2<sup>nd</sup> birthday according to CIR, by the total number of same-aged children in that year according to the most recent Vintage population estimates.

<span id="menacwy"></span>

Meningococcal Conjugate Vaccine (MenACWY) 

- The CDC maintains updated guidelines and recommendations on meningococcal ACWY vaccination. For more information, visit: https://www.cdc.gov/vaccines/vpd/mening/index.html 
- Vaccination Tracking: Percent vaccinated is calculated by dividing the number of 13-17-year-olds who received at least one MenACWY vaccine dose according to CIR, by the total number of same-aged children in that year according to the most recent Vintage Population estimates. 

<span id="pcv"></span>
Pneumococcal Conjugate Vaccine (PCV) 

- The CDC maintains updated guidelines and recommendations on pneumococcal vaccination. For more information, visit: https://www.cdc.gov/vaccines/vpd/pneumo/index.html 
- Vaccination Tracking: By age 24 months, children are recommended to have received 4 doses of PCV depending on the vaccine product they received. Percent vaccinated is calculated by dividing the number of 24-35-month-olds who received all required doses of PCV by their 2<sup>nd</sup> birthday according to CIR, by the total number of same-aged children in that year according to the most recent Vintage Population estimates. 

<span id="polio"></span>
Poliovirus Vaccine (Polio) 

- The CDC maintains updated guidelines and recommendations on poliovirus vaccination. For more information, visit: https://www.cdc.gov/vaccines/vpd/polio/index.html   
- Vaccination Tracking: By age 24 months, children are recommended to have received three doses of inactivated poliovirus vaccine (IPV). Percent vaccinated is calculated by dividing the number of 24-35-month-olds who received 3 or more doses of IPV by their 2<sup>nd</sup> birthday according to CIR, by the total number of same-aged children in that year according to the most recent Vintage population estimates. 

<span id="tdap"></span>
Tetanus, Diphtheria, Acellular Pertussis Vaccine (Tdap)

- The CDC maintains updated guidance and recommendations on tetanus, diphtheria and pertussis vaccination. For more information, visit:
  - https://www.cdc.gov/vaccines/vpd/tetanus/index.html
  - https://www.cdc.gov/vaccines/vpd/diphtheria/index.html
  - https://www.cdc.gov/vaccines/vpd/pertussis/index.html
- Vaccination Tracking: Percent vaccinated is calculated by dividing the number of 13-17-year-olds who received at least  Tdap dose according to CIR, by the total number of same-aged children in that year according to the most recent Vintage Population estimates.

<span id="var"></span>
Varicella (chickenpox) Vaccine (VAR) 

- The CDC maintains updated guidelines and vaccine recommendations on varicella vaccination. For more information, visit: https://www.cdc.gov/vaccines/vpd/varicella/index.html 
- Vaccination Tracking: By age 24 months, children are recommended to have received at least 1 varicella vaccine dose. Percent vaccinated is calculated by dividing the number of 24-35-month-olds who received 1 dose of varicella vaccine by their 2<sup>nd</sup> birthday according to CIR, by the total number of same-aged children in that year according to the most recent Vintage population estimates. 

## Demographic Characteristics 

A large proportion of the vaccination data reported to the CIR come from proprietary health care provider EHR systems that are not managed by the NYC Health Department. Data in the CIR are limited to what is available in EHR systems and to the fields required for submission. Information on demographics, such as race and ethnicity can be incomplete.  

**ZIP Codes and ZIP Code Tabulation Areas (ZCTAs):**

We report information by geography using modified ZIP Code Tabulation Areas (MODZCTA) based on the ZIP code of residence reported by the vaccination recipient at the time of vaccination. A ZIP code does not refer to a specific area, but rather a collection of addresses that make up a mail delivery route. To represent the area that the route is in, the US Census Bureau developed ZIP Code Tabulation Areas (ZCTAs). In ZCTAs, some ZIP Codes are bundled together into a single ZCTA. 

Modified ZCTA (modZCTA) is a geography used to analyze health data. ZCTAs with small populations are combined, which allows for more stable rate calculations by increasing the underlying population of these areas.  See [here](https://nychealth.github.io/covid-maps/modzcta-geo/about.html) to identify in which MODZCTA a ZIP code is. 

Please note that the number of people vaccinated in some neighborhoods may exceed the estimated population. The percentage of people vaccinated is calculated using intercensal population estimates from the most recent population estimates developed by the U.S. Census Bureau. When new Vintage population estimates are released each year, geographical vaccination coverage will be adjusted accordingly using the same numerators and the new population estimates. Vaccination rates using previous population estimates will be archived.  

Additional factors contributing to these inconsistencies may be that self-reported ZIP code at the time of vaccination may not correspond to the recipient’s primary home address. For example, people may use their work address for the purposes of vaccination. 

Individuals whose addresses are not valid and, therefore, cannot be mapped to a MODZCTA are not included in the map or data download.  

**Race and Ethnicity:**

The CIR has been working with health care providers to improve capture of race/ethnicity information and the completeness of race/ethnicity data has improved over time. 

The CIR collects race and Hispanic/Latino ethnicity separately. For determining vaccination coverage rates for the NYC population in this data repository, CIR combines and classifies the proportion of people vaccinated by race/ethnicity into the following mutually exclusive categories: Asian, Black/African American, Hispanic/Latino, and White. The Hispanic/Latino category includes people of any race, and all other categories exclude those who identify as Hispanic/Latino. Disaggregated information on vaccinations among people identified as American Indian/Alaska Native, Native Hawaiian or other Pacific Islander (NHPI), and two or more races are provided only as counts due to small numbers and population estimates for these groups. Race/ethnicity coverage data should be interpreted with caution when comparing to citywide coverage rates. Please see demographic/master_routine_vaccine_demographic.csv for those counts. 

**NIS:**  

- The National Immunization Survey (NIS) is a random-digit-dialed survey conducted by the CDC to assess immunization coverage rates among young children and teens, and track progress toward the Healthy People 2030 goals.  

- Data are collected by administering telephone surveys to randomly selected households with children ages 19-35 months (NIS-Child) or 13-17 years (NIS-Teen). To ensure accuracy, each child’s medical provider is then contacted by mail to provide the child’s immunization history.  

- NIS data are used to provide national, state, local area, and territorial estimates of vaccination coverage for all ACIP-recommended vaccines for children and teens in the United States. 

- For more information about the NIS, visit https://www.cdc.gov/vaccines/imz-managers/nis/index.html 

**About Health Inequities in Data:**

Differences in vaccination coverage among NYC children may be due to many factors, including but not limited to: 

- **Socioeconomic disparities:** children from lower socioeconomic backgrounds may face additional barriers to vaccination, such as limited access to healthcare services, transportation issues and work-related constraints of caregivers. 
- **Geographic disparities:** certain NYC neighborhoods may have limited access to healthcare facilities or vaccination services, making it more difficult for children living in those neighborhoods to receive vaccines. 
- **Racial/ethnic disparities:** differences in health outcomes and vaccination coverage may be due to long-term structural racism, and not biological or personal traits. Structural racism — centuries of racist policies and discriminatory practices across institutions, including government agencies, and society — prevents communities of color from accessing vital resources (such as health care, housing and food) and opportunities (such as employment and education), and negatively affects overall health and well-being.
- **Other factors:** other factors such as vaccine confidence, language and other cultural factors may affect vaccine uptake. 

## Repository Contents 

**demographic /**

**geographic /**

**demographic /**
This folder contains vaccination data stratified by demographic types. 

*main_routine_vaccine_demographic.csv*

Variables include: 

|Variable Name | Definition |
|---|---|
DATE_CREATED | Data of data retrieved from the CIR
AGE_GROUP |Age group 
DOB_RANGE |Date of birth range of cohort 
VACCINE_GROUP |Vaccine group 
DOSES |Number of doses 
YEAR_COVERAGE |Year of vaccination coverage  
QUARTER |Quarter of vaccination coverage 
RACE_ETHNICITY |Race and ethnicity 
POP_DENOMINATOR_YEAR |Year of population estimates 
POP_DENOMINATOR |Population estimates, denominator for vaccination coverage 
COUNT_PEOPLE_VAC |Number of people who received all required doses of the vaccine series, numerator for vaccination coverage 
PERC_VAC |Point estimates of vaccination coverage, percentage rounded to the nearest whole number, capped at 99% of the population who completed the series, show %  

**geographic/**
This folder contains vaccination data stratified by geographic types. 

*main_routine_vaccine_geographic.csv*

Variables include: 

|Variable Name |Definition|
|---|---|
DATE_CREATED | Date of data retrieved from the CIR 
AGE_GROUP | Age group 
DOB RANGE | Date of birth range of cohort 
VACCINE_GROUP | Vaccine group 
DOSES | Number of doses 
YEAR_COVERAGE | Year of vaccination coverage  
QUARTER | Quarter of vaccination coverage 
BOROUGH | Name of borough 
MODZCTA | Modified ZCTA (ZIP Code Tabulation Area, which solidifies Zip codes into units of area) 
LABEL | List of the ZIP Code Tabulation Areas (ZCTAs) that are bundled into the MODZCTA 
NEIGHBORHOOD_NAME | Neighborhood name of the MODZCTA 
POP_DENOMINATOR_YEAR | Year of population estimates 
POP_DENOMINATOR | Population estimates, denominator for vaccination coverage 
COUNT_PEOPLE_VAC | Number of people who received all required doses of the vaccine series, numerator for vaccination coverage 
PERC_VAC | Estimated percentage rounded to the nearest whole number, capped at 99% of the population who completed the series, show %  

