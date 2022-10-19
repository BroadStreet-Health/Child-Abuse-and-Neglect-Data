# The BroadStreet Institute

## Structure of the Dataset

### <u>Data Dictionary:</u>

Variable | Definition
------------- | -------------
<strong>County</strong> | The county for which the data is reported. |
<strong>FIPS_Code</strong> | Federal Information Processing Standards code that uniquely identifies countries and county equivalents in the United States. |
<strong>[year]_Physical</strong> | Counts of reported “physical abuse/bodily injury” for that year. | 
<strong>[year]_Emotional</strong> | Counts of reported “serious mental injury” for that year. |
<strong>[year]_Neglect</strong> | Counts of reported “serious physical neglect” for that year. |
<strong>[year]_Sexual</strong> | Counts of reported sexual abuse for that year. |

### <u>Content:</u>

#### <u>Data Source:</u>
Data for Pennsylvania was available on the Pennsylvania Department of Human Services website. The data was found within “Annual Child Protective Services Reports” for the years 2017-2020. Within this report contains a section for “County-by-County analysis” where each county provides the relevant data under the section “Types of Allegations”. The data captures total number values per county for Physical Abuse/Bodily Injury (Physical Abuse), Serious Physical Neglect (Neglect), Sexual Abuse, and Serious Mental Injury (Emotional Abuse).

#### <u>Data Collection & Input:</u>
Data is collected weekly for each county in the United States that is reporting any extent of child abuse.

Data is collected as a cumulative count rather than a daily count. Types of abuse are provided comprehensively within yearly reports where cases are to be reported into an entire data set. Numerical cases reported under the “investigated” are data of interest; this indicates the case(s) has evidence of abuse.

When the county is not listed nor its numerical data, often from lack of collection (e.g. geological effects, data release phases), a “-” is used to denote this. When 0 cases are reported in a category, a 0 is used as the placeholder.

#### <u>Coding:</u>
Table 1. Types of abuse
Variable Name  | Variable Description
------------- | ------------- 
Investigated  | Data is listed under “Allegations” - Reports are those that allege a child might have been a victim of child abuse<sup>[1] (https://www.dhs.pa.gov/docs/Publications/Pages/Child-Abuse-Reports.aspx)</sup>
Units Reported  | Total number of cases<sup>[1] (https://www.dhs.pa.gov/docs/Publications/Pages/Child-Abuse-Reports.aspx)</sup>


## Methodology
### <u>Challenges & Limitations</u>
<u>Definition discrepancy</u>
“Serious physical neglect” is a category reported separately from “physical abuse/bodily injury.” “Serious physical neglect” was recorded as neglect in our dataset.
“Serious mental injury: was recorded as emotional abuse in our dataset.


<u>Data completeness</u>
Data is only available from 2017-2020. 


## References

1.  Pennsylvania Department of Human Services. Child Abuse Reports. Accessed September 30, 2022.  [Pennsylvania Department of Human Services | Child Abuse Reports](https://www.dhs.pa.gov/docs/Publications/Pages/Child-Abuse-Reports.aspx)

## Suggested Citation
When using data images, downloaded data, or shared document formats, please attribute BroadStreet as well as the original source, when applicable. For examples and more information, review this article which answers the question  ["How do I cite BroadStreet?"](https://help.broadstreet.io/article/citations/)

## Contributors
Project Leaders and Data Release Team Members (listed alphabetically by last name):

Gilianne Augustin; Meenal Khandaker; Riya Kumar; Ernesto Lopez; Sarah Murata; Rimple Patel; Lamya Serhir; [Fu Zeng](https://www.linkedin.com/in/fuzeng/)

A full list of the Broadstreet Institute volunteers can be found at [https://covid19dataproject.org/team-2/](https://covid19dataproject.org/team-2/)

## Questions / Feedback
Email the primary contributors at: hello@broadstreet.io


