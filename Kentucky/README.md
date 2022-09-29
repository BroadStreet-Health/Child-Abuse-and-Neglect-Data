# The BroadStreet Institute

## Structure of the Dataset

### <u>Data Dictionary:</u>

Variable | Definition
------------- | -------------
<strong>County</strong> | The county for which the data is reported. |
<strong>FIPS_Code</strong> | Federal Information Processing Standards code that uniquely identifies countries and county equivalents in the United States. |
<strong>[year]_Physical</strong> | Counts of reported physical abuse for that year. | 
<strong>[year]_Emotional</strong> | Counts of reported emotional abuse for that year. |
<strong>[year]_Neglect</strong> | Counts of reported neglect abuse for that year. |
<strong>[year]_Sexual</strong> | Counts of reported sexual abuse for that year. |

### <u>Content:</u>

#### <u>Data Source:</u>
County-level data in the United States was collected from KidsCount and various federal websites (such as Department of Children & Families) that reported any child abuse per state. KidsCount is a website that provides state and local datasets on topics regarding children's well-being.3 Sources were expanded as necessary to include government or institutional sources with county-level or other sub-state level data (i.e. zip code, health district, or regional data). In BroadStreet’s initiative, types of abuse are provided comprehensively within yearly reports where cases are to be reported into the dataset. To ensure we are providing a comprehensive report, interns are responsible for seeking out the source for each state’s county-level data. Data sources per state can vary and if KidsCount is not available for a specific state, federal websites are used, such as Department of Social Services or Department of Children & Families reports.
Data for Kentucky was available on KidsCount. Reports used for data collection are labeled as “Number of child abuse/ neglect investigations by type in Kentucky”. Within this report, a table captures the total number values per county under Physical Abuse, Child Neglect, and Sexual Abuse from 2003 to 2013.

#### <u>Data Collection & Input:</u>
Data is collected weekly for each county in the United States that is reporting any extent of child abuse.

Data is collected as a cumulative count rather than a daily count. Types of abuse are provided comprehensively within yearly reports where cases are to be reported into an entire data set. Numerical cases reported under the “substantiated” are data of interest; this indicates the case(s) has evidence of abuse.

When the county is not listed nor its numerical data, often from lack of collection (e.g. geological effects, data release phases), a “-” is used to denote this. When 0 cases are reported in a category, a 0 is used as the placeholder.

#### <u>Coding:</u>
Table 1. Types of abuse
Variable Name  | Variable Description
------------- | ------------- 
Substantiated  | Provides a breakdown of confirmed/founded maltreatment by the abuse type. For each child on each report, up to 10 maltreatment types may be indicated. This spreadsheet summarizes the number of each type of allegation which was confirmed or founded for all child protective reports during the calendar year. <sup>[1] (https://datacenter.kidscount.org/)</sup>
Units Reported  | Total number of cases<sup>[1] (https://datacenter.kidscount.org/)</sup>


## Methodology
### <u>Challenges & Limitations</u>
<u>Data Challenges</u>
Certain organized counties on published reports are organized based on region. The way in which interns organize these counties, through Google Sheets, are in alphabetical order. This discrepancy may present some difficulty when entering data. On occasions, data can become mixed up, thus fortifying the possibility of publishing incorrect data.

<u>Accessibility of Data </u>
Formatting Child Abuse data may be reported in various formats, which can complicate any efforts to automate data entry. Formats used to report child abuse data include .pdf, .csv, excel, and Microsoft Bl, to name a few.

<u>Data completeness</u>
Over the past decade, Kids Count provides data up until the year 2019. Data for the years of 2019 through 2021 are unavailable.


## References

1.  KidsCount. The Annie E. Casey Foundation. Kids Count Data Center website. Accessed September 15, 2022.
[https://datacenter.kidscount.org/](https://datacenter.kidscount.org/)


## Suggested Citation
When using data images, downloaded data, or shared document formats, please attribute BroadStreet as well as the original source, when applicable. For examples and more information, review this article which answers the question  ["How do I cite BroadStreet?"](https://help.broadstreet.io/article/citations/)

## Contributors
Gilianne Augustin; Anna Heinrich; Ernesto Lopez; Rimple Patel; Lamya Serhir; Jaclyn Siu; [Fu Zeng](https://www.linkedin.com/in/fuzeng/); [Brenna Jarvis, MPH](https://www.linkedin.com/in/brenna-jarvis-88b4351b6/); Meenal Khandaker; Sarah Murata. 

A full list of the Broadstreet Institute volunteers can be found at [https://covid19dataproject.org/team-2/](https://covid19dataproject.org/team-2/)

## Questions / Feedback
Email the primary contributors at: hello@broadstreet.io




