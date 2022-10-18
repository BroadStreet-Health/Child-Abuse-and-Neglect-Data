# The BroadStreet Institute

## Structure of the Dataset

### <u>Data Dictionary:</u>

Variable | Definition
------------- | -------------
<strong>County</strong> | The county for which the data is reported. |
<strong>FIPS_Code</strong> | Federal Information Processing Standards code that uniquely identifies countries and county equivalents in the United States. |
<strong>[year]_Physical</strong> | Counts of reported physical abuse for that year. | 
<strong>[year]_Emotional</strong> | Counts of reported emotional abuse for that year. |
<strong>[year]_Neglect</strong> | Counts of reported child neglect for that year. |
<strong>[year]_Sexual</strong> | Counts of reported sexual abuse for that year. |

### <u>Content:</u>

#### <u>Data Source:</u>
Data for Kentucky was available on KidsCount. Reports used for data collection are labeled as “Number of child abuse/neglect investigations by type in Kentucky”. Within this report, a table captures the total number values per county under Physical Abuse, Child Neglect (Neglect), and Sexual Abuse from 2003 to 2013 and a separate report for 2014 and beyond.


#### <u>Data Collection & Input:</u>
Data is collected weekly for each county in the United States that is reporting any extent of child abuse.

Data is collected as a cumulative count rather than a daily count. Types of abuse are provided comprehensively within yearly reports where cases are to be reported into an entire data set. Numerical cases reported under the “investigated” are data of interest; this indicates the case(s) has evidence of abuse.

When the county is not listed nor its numerical data, often from lack of collection (e.g. geological effects, data release phases), a “-” is used to denote this. When 0 cases are reported in a category, a 0 is used as the placeholder. A “*” denotes that a number has been suppressed for being fewer than 6.

#### <u>Coding:</u>
Table 1. Types of abuse
Variable Name  | Variable Description
------------- | ------------- 
Investigated  | Number of child abuse/neglect investigations by type. * = Number is suppressed for fewer than 6 children<sup>[1](https://datacenter.kidscount.org/data/tables/8297-percent-of-child-abuse-neglect-investigations-substantiated-by-type?loc=19&loct=5#detailed/5/2924-3043/false/36,868,867,133,38,35,18,17,14/6074,1267,1268/16863)</sup>
Units Reported  | Total number of cases<sup>[1](https://datacenter.kidscount.org/data/tables/8297-percent-of-child-abuse-neglect-investigations-substantiated-by-type?loc=19&loct=5#detailed/5/2924-3043/false/36,868,867,133,38,35,18,17,14/6074,1267,1268/16863)</sup>


## Methodology
### <u>Challenges & Limitations</u>
<u>Data Collection</u>
Counties in KidsCount are organized alphabetically, whereas interns organize these counties in Google Sheets in the order of FIPS codes. This discrepancy may present some difficulty when entering data. On occasion, namely regarding counties starting with Ma- and Mc-, data can become mixed up, thus fortifying the possibility of publishing incorrect data.

<u>Data completeness</u>
Over the past decade, Kids Count provides data up until the year 2019. Data for the years of 2019 through 2021 are unavailable.


## References

1.  KidsCount. Percent of child abuse/neglect investigations substantiated by type in Kentucky. Kids Count Data Center website. Accessed  September 15, 2022. 
[https://datacenter.kidscount.org/data/tables/8297-percent-of-child-abuse-neglect-investigations-substantiated-by-type?loc=19&loct=5#detailed/5/2924-3043/false/36,868,867,133,38,35,18,17,14/6074,1267,1268/16863](https://datacenter.kidscount.org/data/tables/8297-percent-of-child-abuse-neglect-investigations-substantiated-by-type?loc=19&loct=5#detailed/5/2924-3043/false/36,868,867,133,38,35,18,17,14/6074,1267,1268/16863)


## Suggested Citation
When using data images, downloaded data, or shared document formats, please attribute BroadStreet as well as the original source, when applicable. For examples and more information, review this article which answers the question  ["How do I cite BroadStreet?"](https://help.broadstreet.io/article/citations/)

## Contributors
Project Leaders and Data Release Team Members (listed alphabetically by last name):

Gilianne Augustin; Meenal Khandaker; Riya Kumar; Ernesto Lopez; Sarah Murata; Rimple Patel; Lamya Serhir; [Fu Zeng](https://www.linkedin.com/in/fuzeng/)


A full list of the Broadstreet Institute volunteers can be found at [https://covid19dataproject.org/team-2/](https://covid19dataproject.org/team-2/)

## Questions / Feedback
Email the primary contributors at: hello@broadstreet.io




