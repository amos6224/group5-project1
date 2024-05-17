# NYC Crimes Exploratory Data Analysis (EDA)

<div style="text-align:center">
    <img src="nypd image.jpeg" style="width:500px;" />
</div>
<br />

# Introduction

Our team embarked on a comprehensive exploratory data analysis (EDA) and visualization project aimed at understanding the dynamics of crime in New York City (NYC) from the inception of 2024 until the present date. The primary objective was to scrutinize borough-related crime patterns, identify peak crime times, examine date-related felonies, and explore gender-based disparities in criminal occurrences, with a specific focus on pinpointing the most high-risk borough within NYC. Our initial dataset encompassed over 50,000 observations spanning from the commencement of the year until now. To ensure the clarity and manageability of our analysis, we opted to narrow our focus to the data from the preceding month, thus avoiding unnecessary complexity while maintaining relevance.

# Data Source and Methodology

New York City stands as a beacon of transparency and accessibility in terms of data availability, which greatly facilitated our research endeavors. Leveraging the vast repository of datasets provided by NYC OPEN DATA, a commendable initiative that collates government-produced datasets for public access, we sourced our data from diverse NYC agencies and city organizations. This initiative, aimed at enhancing governmental transparency, accountability, and accessibility, provides a treasure trove of searchable datasets, empowering citizens with valuable insights into various facets of city governance.

Our EDA was meticulously conducted, drawing insights from data spanning 2023 and 2024. We adopted a systematic approach, grouping crimes by borough and meticulously sorting offenses by count, race, and gender. This rigorous analysis not only serves as a valuable resource for law enforcement agencies but also offers actionable insights for governmental bodies tasked with crime management and public safety initiatives. Through the integration of advanced AI technologies, our overarching goal is to empower communities by identifying key factors, patterns, and variables influencing crime rates in NYC, thereby facilitating evidence-based decision-making processes.

# Key Variables

The dataset comprised several key variables instrumental in our analysis:

    - Arrest_date: Date of arrest
    - Ofns_desc: Offense description
    - Arrest_boro: Borough of arrest
    - Age_group: Age group
    - Perp_sex: Gender
    - Perp_race: Race
    - Latitude: Geographic latitude
    - Longitude: Geographic longitude

To facilitate meaningful comparisons over time, we normalized the data by multiplying it by 365 to obtain an annualized rate.

 # Group by borough and crime type and count occurrences
![image](https://github.com/amos6224/group5-project1/assets/163084245/1588d0d2-b74d-4475-9d62-47fd71668a66)


# Felony assault in the Bronx/Queens
# Offenses by counts in descending order
    1.ROBBERY,OPEN AREA UNCLASSIFIED
    2.RAPE 
    3.ASSAULT
    4.CONTROLLED SUBSTANCE, POSSESS
    5.ASSAULT 2,1,UNCLASSIFIED
   

# Insights and Recommendations

Our analysis unearthed several noteworthy insights into crime trends in NYC, with gender-related and age-related crime patterns standing out prominently. Notably, statistical analyses consistently revealed a higher incidence of criminal activity among men compared to women, shedding light on prevailing gender disparities in criminal behavior.

In terms of age-related crime patterns, our findings underscored significant variations in the average duration of incidents across different felony types and years. While NYC's overall crime rate may not have surpassed historical highs, there has been a discernible uptick in crime rates since the onset of the COVID-19 pandemic, attributable to a myriad of socio-economic and public health factors.

# Conclusion

In conclusion, our extensive EDA offers valuable insights into the evolving landscape of crime in NYC, elucidating distinct crime patterns by borough, felony type, and demographic characteristics. The Bronx emerges as a focal point for criminal activity, with Staten Island exhibiting marginally elevated crime rates compared to other boroughs. These insights serve as a cornerstone for informed decision-making processes among law enforcement agencies and policymakers, ultimately contributing to the safety, security, and well-being of NYC residents. Moving forward, continued vigilance, proactive measures, and data-driven interventions are imperative to address emerging challenges and foster a safer, more resilient cityscape for all inhabitants.

We used: Chat GPT, Co PILOT
