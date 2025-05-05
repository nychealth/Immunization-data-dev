# Childhood Vaccination Data 

This repository contains data on routine immunizations administered to New York City (NYC) children ages 0-18 years and reported to the [Citywide Immunization Registry](nyc.gov/health/cir) https://www.nyc.gov/health/cir (CIR). 

These data are available on the NYC Health Department’s Immunization Data webpage ([link](https://www.nyc.gov/site/doh/misc/sdah-boi-dashboard.page)). 

**This Readme includes the following topics:**

- How to Use This Repository 
- Key Technical Notes 
- Definitions 
- Contents 

## How to Use This Repository   

Two main datasets serve as the data sources for all the visualizations displayed on the Childhood Vaccination Data webpage – one dataset is stratified by individual demographics and the other is stratified by geography. Users can download a separate dataset for each visualization by clicking ‘Get the data’ under the visualization or by downloading the full dataset under **‘Repository Content’.** The data dictionary is also available for download. 

## Key Technical Notes 

**Citywide Immunization Registry:**

Since 1996, the Citywide Immunization Registry (CIR) has been used as a database of patient immunization records reported by NYC health care providers and some out-of-state immunization information systems. The CIR keeps immunization records for all city residents – children and adults – throughout their lifespan and has records for non-NYC residents vaccinated in the city. It is accessible to authorized health care providers, schools, individuals and agencies concerned with public health to ensure that NYC residents are up to date with recommended immunizations. NYC health care providers report immunizations to the CIR as mandated by New York State Public Health Law and the NYC Health Code. Pediatric providers are required to report all immunizations administered to children 0-18 years. Reporting of adult immunizations requires patient consent. Immunization data are submitted to the CIR through electronic health record systems or the [CIR’s Online Registry](https://immunize.nyc/prod/online-registry/) user interface.

**Dashboard Update Schedule**

The NYC Immunization Dashboard displays immunization coverage data for the past five years stratified by race/ethnicity and NYC neighborhood. Additionally, trends in citywide coverage are displayed for the past eight years. Data presented on the NYC Immunization Dashboard are updated twice a year, as of June 30 and December 31 of each year. Data are released one to two months after the review date to allow enough time for data to be reported to the CIR and prepared for public sharing. 

Data are preliminary and subject to change when new population estimates are published. 

## Definitions 

Types of vaccines: 

- [Childhood Combined 7-Vaccine Series (4 DTaP, 3 Polio, 1 MMR, 3 Hib, 3 HepB, 1 Varicella, 4 PCV)](#seven)
- [Diphtheria and Tetanus Toxoids and Acellular Pertussis Vaccine (DTaP/DT/DTP)](#dtap)
- [Poliovirus Vaccine (Polio)](#polio) 
- [Measles, Mumps and Rubella Vaccine (MMR)](#mmr) 
- [Haemophilus Influenzae Type b Vaccine (Hib)](#hib) 
- [Hepatitis B Vaccine (HepB)](#hepb) 
- [Varicella Zoster (chickenpox) Vaccine (VAR)](#var) 
- [Pneumococcal Conjugate Vaccine (PCV)](#pcv) 
- [Human Papillomavirus Vaccine (HPV)](#hpv)
- [Influenza Vaccine (Flu)](#flu) 

Data variables: 

**AGE_GROUP** (Age cohort)

The NYC Health Department tracks vaccination coverage among NYC children and adolescents in several age cohorts depending on vaccine series. 

- For the combined 7-vaccine series and each component vaccine, the Health Department tracks coverage for children ages 2 years by their second birthday which includes children between the ages of 24 months 0 day and 35 months 30 days as of the coverage assessment date. 
- For HPV, the Health Department additionally tracks HPV series completion rates for 13-year-olds by the 13th birthday to monitor on-time vaccination at ages 11-12 years, and completion rates for adolescents ages 13 to 17 years. Adolescents ages 13 to 17 years includes adolescents between the ages of 13 years 0 day and 17 years 11 months 30 days as of the coverage assessment date.
- For influenza (flu) vaccination, the Health Department tracks coverage and vaccine uptake for children ages 6-months to 4-years and 5-to-12-years. Since the influenza season spans many months, the age criterion for the analysis is based on the child’s age (in days) at the time of the flu vaccination. The CIR calculates a child’s age days by subtracting the child’s date of birth (DOB) from the flu vaccination date. This includes children between the ages of 182 and 1,825 days (for the 6-month to 4-year-old cohort), between the ages of 1,826 and 4,747 days (for the 5-to–12-year-old cohort), and between the ages of 4,748 and 6,573 days (equivalent to ages 13-17 years) as of the flu vaccination date. 

**VAC_COUNT** (Numerator)  
The numerator includes children in the CIR who meet the following criteria: 
- Received all required doses of the specified vaccine 
- Not documented in CIR as having moved or gone elsewhere: moved out of the city or deceased 
- Had a valid NYC ZIP code listed in CIR as of the coverage assessment date  

**POP_DENOM** (Denominator)
The denominators for routine and influenza vaccination coverage estimates are based on the most recent population estimates available. The NYC Health Department produces these estimates (called Vintage) using data from the U.S. Census Bureau and the NYC Department of City Planning. When new Vintage population estimates are released, vaccination coverage rates on the Childhood Vaccination Data page are adjusted accordingly using the same numerators and the new population estimates. Vaccination data using previous estimates are archived.  
In a few cases, the number of children vaccinated may exceed the estimated population resulting in vaccination coverage exceeding 100%. This may happen with small demographic categories and geographies. Coverage rates exceeding 100% are capped at 99%. Additionally, denominators of less than 10 are suppressed in the data presented on the dashboard.

**Vaccine Groups**  

<span id="seven"></span>
Childhood Combined 7-Vaccine Series (4 DTaP, 3 Polio, 1 MMR, 3 Hib, 3 HepB, 1 Varicella, 4 PCV)

- The combined 7-vaccine series (also known as the 4:3:1:3:3:1:4 series) measures the percentage of children ages 2 years who received all required doses of the series by their second birthday. 

- The series includes ≥4 doses of diphtheria and tetanus toxoids and acellular pertussis vaccine; ≥3 doses of poliovirus vaccine; ≥1 dose of measles-mumps-rubella vaccine; ≥3 or ≥4 doses of **Haemophilus Influenzae** Type b vaccine (depending on product type); ≥3 doses of hepatitisB vaccine; ≥1 dose of varicella vaccine; and ≥4 doses of pneumococcal conjugate vaccine.  

- For more information about the 7-vaccine series, visit: Birth-18 Years Immunization Schedule – Healthcare Providers | CDC 

<span id="dtap"></span>
Diphtheria and Tetanus Toxoids and Acellular Pertussis Vaccine (DTaP/DT/DTP) 

- The CDC maintains updated guidelines and recommendations on diphtheria, tetanus and pertussis vaccination (DTaP/DT/DTP). For more information, visit: 

  - https://www.cdc.gov/diphtheria/vaccines/index.html 
  - https://www.cdc.gov/tetanus/vaccines/index.html 
  - https://www.cdc.gov/pertussisvaccines/index.html 
  
- Vaccination Tracking: Percent vaccinated is calculated by dividing the number of 24-35-month-olds who have received 4 or more doses of DTaP vaccine by their second birthday according to CIR, by the total number of same-aged children in that year according to the most recent Vintage population estimates. 

<span id="polio"></span>
Poliovirus Vaccine (Polio) 

- The CDC maintains updated guidelines and recommendations on poliovirus vaccination. For more information, visit: https://www.cdc.gov/polio/vaccines/index.html   
- Vaccination Tracking: Percent vaccinated is calculated by dividing the number of 24-35-month-olds who received 3 or more doses of IPV by their second birthday according to CIR, by the total number of same-aged children in that year according to the most recent Vintage population estimates. 

<span id="mmr"></span>
Measles-Mumps-Rubella Vaccine (MMR) 

- The CDC maintains updated guidelines and recommendations on MMR vaccination. For more information, visit:
  - https://www.cdc.gov/measles/vaccines/index.html
  - https://www.cdc.gov/mumps/vaccines/index.html
  - https://www.cdc.gov/rubella/vaccines/index.html
- Percent vaccinated is calculated by dividing the number of 24-35-month-olds who received one MMR vaccine dose by their second birthday according to CIR, by the total number of same-aged children in that year according to the most recent Vintage population estimates.

<span id="hib"></span>
Haemophilus Influenzae Type b Vaccine (Hib) 

- The CDC maintains updated guidelines and vaccine recommendations on Hib vaccination. For more information, visit: https://www.cdc.gov/hib/vaccines/index.html 
- Vaccination Tracking: Percent vaccinated is calculated by dividing the number of 24-35-month-olds who received all required doses of Hib vaccine by their second birthday according to CIR, by the total number of same-aged children in that year according to the most recent Vintage population estimates. 

<span id="hepb"></span>
Hepatitis B Vaccine (HepB) 

- The CDC maintains updated  guidelines and vaccine recommendations on Hepatitis B vaccination. For more information, visit: https://www.cdc.gov/hepb/vaccine/index.html 
- Vaccination Tracking: Percent vaccinated is calculated by dividing the number of 24-35-month-olds who received 3 doses of HepB vaccine by their second birthday according to CIR, by the total number of same-aged children in that year according to the most recent Vintage population estimates. 

<span id="var"></span>
Varicella (chickenpox) Vaccine (VAR) 

- The CDC maintains updated guidelines and vaccine recommendations on varicella vaccination. For more information, visit: https://www.cdc.gov/vaccines/varicella/index.html 
- Vaccination Tracking: By age 24 months, children are recommended to have received at least 1 varicella vaccine dose. Percent vaccinated is calculated by dividing the number of 24-35-month-olds who received 1 dose of varicella vaccine by their 2<sup>nd</sup> birthday according to CIR, by the total number of same-aged children in that year according to the most recent Vintage population estimates. 

<span id="pcv"></span>
Pneumococcal Conjugate Vaccine (PCV) 

- The CDC maintains updated guidelines and recommendations on pneumococcal vaccination. For more information, visit: https://www.cdc.gov/pneumococcal/vaccines/index.html
- Vaccination Tracking: Percent vaccinated is calculated by dividing the number of 24-35-month-olds who received all required doses of PCV by their second birthday according to CIR, by the total number of same-aged children in that year according to the most recent Vintage Population estimates. 


<span id="hpv"></span>
Human Papillomavirus Vaccine (HPV) 

- The CDC maintains updated guidelines and recommendations on HPV vaccination. For more information, visit: https://www.cdc.gov/hpv/vaccines/index.html 
- Vaccination Tracking: Percent vaccinated is calculated by dividing the number of 13-17-year-olds who received all required doses of HPV vaccine according to CIR, by the total number of same-aged children in that year according to the most recent Vintage Population estimates. On-time vaccination is calculated by dividing the number of 13-year-olds who completed the HPV vaccine series (with 2 or 3 doses) by their 13th birthday according to CIR, by the total number of 13-year-olds in that year according to the most recent Vintage Population estimates.  

<span id="flu"></span>
Influenza Vaccine (Flu) 

- The CDC maintains updated guidelines and recommendations on influenza vaccination. For more information, visit: https://www.cdc.gov/flu/vaccines/index.html 
- Vaccination Tracking: Percent vaccinated is calculated by dividing the total number of children who received at least one seasonal influenza vaccine during the target flu season according to CIR, by the total number of same-aged children in that year according to the most recent Vintage population estimates. Patient DOB criteria is based on the patient’s age (in days) at the time of the flu vaccination.  



## Demographic Variables 

**Race and Ethnicity**

The CIR has been working with health care providers to improve capture of race/ethnicity information and the completeness of race/ethnicity data has improved over time. 

The CIR collects race and Hispanic/Latino ethnicity separately. For determining vaccination coverage rates for the NYC population in this data repository, CIR combines and classifies the proportion of people vaccinated by race/ethnicity into the following mutually exclusive categories: Asian, Black/African American, Hispanic/Latino, and White. The Hispanic/Latino category includes people of any race, and all other categories exclude those who identify as Hispanic/Latino. Disaggregated information on vaccinations among people identified as American Indian/Alaska Native, Native Hawaiian or other Pacific Islander (NHPI), and two or more races are provided only as counts due to small numbers and population estimates for these groups. Race/ethnicity coverage data should be interpreted with caution when comparing to citywide coverage rates. 
A large proportion of the vaccination data reported to the CIR come from proprietary health care provider electronic health records (EHR) systems that are not managed by the NYC Health Department. Data in the CIR are limited to what is available in EHR systems and to the fields required for submission. Information on demographics, such as race and ethnicity can be incomplete.  

**ZIP Codes and ZIP Code Tabulation Areas (ZCTAs):**

We report information by geography using modified ZIP Code Tabulation Areas (MODZCTA) based on the ZIP code of residence reported by the vaccine recipient at the time of vaccination. A ZIP code does not refer to a specific area, but rather a collection of addresses that make up a mail delivery route. To represent the area that the route is in, the US Census Bureau developed ZIP Code Tabulation Areas (ZCTAs). In ZCTAs, some ZIP Codes are bundled together into a single ZCTA. 

Modified ZCTA (modZCTA) is a geographic unit used to analyze health data. ZCTAs with small populations are combined into Modified ZCTAs to allow for stable rate calculations by increasing the underlying population of these areas. See [Modified ZIP Code Tabulation Areas NYC webpage](https://nychealth.github.io/covid-maps/modzcta-geo/about.html) to identify in which MODZCTA a ZIP code is. 

The number of people vaccinated in some neighborhoods may exceed the estimated population. The percentage of people vaccinated is calculated using intercensal population estimates from the most recent population estimates developed by the U.S. Census Bureau. When new yearly population estimates are released each year, geographical vaccination coverage will be adjusted accordingly using the same numerators and the new population estimates. Vaccination rates using previous population estimates will be archived.  

Additional factors contributing to these inconsistencies may be that self-reported ZIP code at the time of vaccination may not correspond to the recipient’s primary home address. For example, people may use their work address for the purposes of vaccination. 

Individuals whose addresses are not valid and, therefore, cannot be mapped to a MODZCTA are not included in the map or data download.  

**National Immunization Survey (NIS)**  

- The National Immunization Survey (NIS) is a random-digit-dialed survey conducted by the CDC to assess immunization coverage rates among young children and teens, and track progress toward the Healthy People 2030 goals.  

- Data are collected by administering telephone surveys to randomly selected households with children ages 19-35 months (NIS-Child) or 13-17 years (NIS-Teen). To ensure accuracy, each child’s medical provider is then contacted by mail to provide the child’s immunization history.  

- NIS data are used to provide national, state, local area, and territorial estimates of vaccination coverage for all ACIP-recommended vaccines for children and teens in the United States. NIS coverage rates may diff from CIR coverage rates due to differences in methodology.

- For more information about the NIS, visit [https://www.cdc.gov/nis/about/?CDC_AAref_Val=https://www.cdc.gov/vaccines/imz-managers/nis/index.html
](https://www.cdc.gov/nis/about/index.html)

## Repository Contents 

**demographic /**
This folder contains vaccination data stratified by demographic types. 

**geographic /**
This folder contains vaccination data stratified by geographic types. 

