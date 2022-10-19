# The BroadStreet Institute

## Structure of the Dataset

### <u>Data Dictionary:</u>

Variable | Definition
------------- | -------------
<strong>County</strong> | The county for which the data is reported. |
<strong>FIPS_Code</strong> | Federal Information Processing Standards code that uniquely identifies countries and county equivalents in the United States. |
<strong>[year]_Physical</strong> | Counts of reported physical abuse for that year. | 
<strong>[year]_Emotional</strong> | Counts of reported mental injury for that year. |
<strong>[year]_Neglect</strong> | Counts of reported physical neglect for that year. |
<strong>[year]_Sexual</strong> | Counts of reported sexual abuse for that year. |

### <u>Content:</u>

#### <u>Data Source:</u>
Data for Mississippi was available on the Mississippi Department of Human Services website within its Annual Reports for each fiscal year. Tables used for data collection are labeled as “Child Abuse and Neglect Stastitics SFY [Year]”. The table captures the total number values under Physical Abuse, Physical Neglect (Neglect), Mental Injury (Emotional abuse), and Sexual Abuse from 2010 to 2016.

#### <u>Data Collection & Input:</u>
Data is collected weekly for each county in the United States that is reporting any extent of child abuse.

Data is collected as a cumulative count rather than a daily count. Types of abuse are provided comprehensively within yearly reports where cases are to be reported into an entire data set. Numerical cases reported under the “investigated” are data of interest; this indicates the case(s) has evidence of abuse.

When the county is not listed nor its numerical data, often from lack of collection (e.g. geological effects, data release phases), a “-” is used to denote this. When 0 cases are reported in a category, a 0 is used as the placeholder.

#### <u>Coding:</u>
Table 1. Types of abuse
Variable Name  | Variable Description
------------- | ------------- 
Substantiated  | Reports of abuse are evidenced - supported by evidence<sup>[1] (https://www.mdhs.ms.gov/annual-reports/)</sup>
Units Reported  | Total number of cases<sup>[1] (https://www.mdhs.ms.gov/annual-reports/)</sup>


## Methodology
### <u>Challenges & Limitations</u>
<u>Data completeness</u>
Data is only available from 2010-2016. There is no data for 2017-2021.


## References

1.  Mississippi Department of Human Services. Annual Reports. Accessed September 26, 2022. [Child Abuse Statistics | Mississippi Department of Human Services](https://www.mdhs.ms.gov/annual-reports/)

## Suggested Citation
When using data images, downloaded data, or shared document formats, please attribute BroadStreet as well as the original source, when applicable. For examples and more information, review this article which answers the question  ["How do I cite BroadStreet?"](https://help.broadstreet.io/article/citations/)

## Contributors
Project Leaders and Data Release Team Members (listed alphabetically by last name):

Gilianne Augustin; Meenal Khandaker; Riya Kumar; Ernesto Lopez; Sarah Murata; Rimple Patel; Lamya Serhir; [Fu Zeng](https://www.linkedin.com/in/fuzeng/)

A full list of the Broadstreet Institute volunteers can be found at [https://covid19dataproject.org/team-2/](https://covid19dataproject.org/team-2/)

## Questions / Feedback
Email the primary contributors at: hello@broadstreet.io



