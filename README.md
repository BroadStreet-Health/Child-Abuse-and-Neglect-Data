# The BroadStreet Institute

## Introduction
[BroadStreet](http://www.broadstreet.io) is a data and software company for social good. We believe that all people deserve access to the best information possible. BroadStreet builds our software for those working towards community change. We strive to ensure that data is accessible, affordable, and delightful to explore. BroadStreet has thousands of members all over the country. Members include students, non-profit leaders, and executives of multi-state and national organizations. We are proud of the range of our members.

BroadStreet’s COVID-19 Data Project began as an in-house project by BroadStreet to collect county-level coronavirus case (#) and death (#) totals. The COVID-19 Data Project grew to become a non-profit, The BroadStreet Institute which began tThe Community Data Project. The Community Data Project  started as small action teams looking beyond COVID data and has expanded to become multiple tracks and teams focused on collecting data on important public health topics outside of the pandemic.

Following the COVID-19 Data Project’s steady expansion, Broadstreet made an inquiry on child abuse data acquired in the United States. This was done in response to rising demand for BroadStreet to partake in the up-and-coming sector of child abuse after discovering that the national dataset on Child Abuse only details data at the state level. In addition, child abuse data generally does not have an overall database where casa data and types of abuse are easily accessible to the public. Similar to other major population health issues, ongoing surveillance of child maltreatment can inform the development of policies that respond to the needs of children and families. Studies relying on alternative data sources from public health have reported different trends in some forms of child maltreatment. The variation in reported prevalence from different sources highlights the importance of using multiple sources of information to better track child maltreatment at the population level<sup>[1](https://policylab.chop.edu/sites/default/files/pdf/publications/PolicyLab_EtoA_Tracking_Child_Abuse_and_Neglect_2012.pdf).

As of July 2021, the Broadstreet U.S. Child Abuse Dataset was initiated as a pilot program working towards creating a national, county-level data set on Child Abuse including types of abuse. This is led by a team of Broadstreet Institute volunteer interns. Interns began to collect data from KidsCount and various federal websites (such as Department of Children & Families) at the county level in the United States that are reported any extent of child abuse level per state. KidsCount is a website that provides state and local datasets on topics regarding children's well-being.2 Sources were expanded as necessitated to include government or institutional sources having county-level data or other sub-state level data (i.e. zip code, health district, or regional data). Currently, the states where data entry has occurred had data available at the county-level which can be found on the state’s individual dashboards.

  

For the state of Missouri, data on confirmed or substantiated Child Abuse cases was collected from 2010 to 2020. In BroadStreet’s initiative, types of abuse are provided comprehensively within yearly reports where cases are to be reported into an entire data set. To ensure we are providing a comprehensive report, Data Entry and QA teams are responsible for seeking out the source for each state’s county-level data.

  

The Child Abuse Data Tracking Project is unique in that it is one of the only datasets collecting child abuse data at the county-level across the United States. This data gives the public knowledge regarding the rate of child abuse cases occuring across the United States. The Child Abuse Data Track is continuously evolving because of how recent this up-and-coming sector is within the greater data curriculum of the Broadstreet Institute.

  

## Structure of the Dataset

### <u>Definitions:</u>


According to the Child Abuse Prevention and Treatment (CAPTA), child and neglect at a federal level is defined as “any recent act or failure to act on the part of a parent or caregiver that results in death, serious physical or emotional harm, sexual abuse, or exploitation, or an act or failure to act that presents an imminent risk of serious harm.”

 Term | Definition<sup><u>*3*</u></sup> | Notes<sup><u>*3*</u></sup>
------------- | ------------- | -------------
Physical Abuse  | The intentional use of physical force that can result in physical injury  | Examples include…<br> hitting, kicking, shaking, burning, or other shows of force against a child
Sexual Abuse <br>(may also be referred as Sexual Maltreatment)  | The involvement of pressuring or forcing a child to engage in sexual acts  | Child Sexual Abuse refers to the involvement of a child (person less than 18 years old) in sexual activity that violates the laws or social taboos of society and that he/she…<br>a.  Does not fully comprehend<br> b.  Does not consent to or is unable to give informed consent to<br>c. Not developmentally prepared for and cannot give consent to<br>
Emotional Abuse (may also be referred as Emotional Maltreatment or Mental Abuse)  | Behaviors that harm a child’s self worth or emotional well-being  | Examples include…<br>Name-calling, shaming, rejection, withholding love, threatening
Neglect | A failure to meet a child’s basic physical and emotional needs  | These needs include…<br>a. Housing<br> b. Food<br> c. Clothing<br> d. Education<br> e. Access to medical care

### <u>Content:</u>
#### <u>Data Entry:</u>
Data entry team members enter data once assigned by Team Lead. This entry is done per state, per county, per an assigned year, and type of abuse. This information is entered into Google sheets available on a shared Google Doc. This data entry occurs in mini/full sprints and on a bi-weekly basis. To limit errors, each state has its own tab with counties and columns for types of abuse reported. After entering data for a given state, the BroadStreet Interns check to make sure the counties match up per the state website or KidsCount website, as some counties do not report on certain types of abuse. Once the intern has completed their assigned state, year, and type of abuse they then mark it as completed on an additional Google Sheet. After entry is completed, the team reviews the state sheet for Quality Assurance to ensure data was filled in completely and matches what the states reported. Quality Assurance interns identify any data entry mistakes and make the appropriate corrections. If the value entered is incorrect, the Quality Assurance team members make corrections.

#### <u>Data Source:</u>
BroadStreet Interns collect data from KidsCount and various government websites at the county level per state. Currently, the states where data entry has occurred has data available at the county-level which can be found on the state’s individual dashboards. Data sources per state can vary and if KidsCount is not available for a specific state, federal websites are used, such as Department of Social Services or Department of Children & Families reports.

#### <u>Data Collection & Input:</u>
Data is collected weekly for each county in the United States that is reporting any extent of child abuse.

Data is collected as a cumulative count rather than a daily count. Types of abuse are provided comprehensively within yearly reports where cases are to be reported into an entire data set. Numerical cases reported under the “substantiated” are data of interest; this indicates the case(s) has evidence of abuse.

When the county is not listed nor its numerical data, often from lack of collection (e.g. geological effects, data release phases), a “-” is used to denote this. Missouri has county-level data for every year, but does not report investigated cases. When 0 cases are reported in a category, a 0 is used as the placeholder.

Reports used for data collection are labeled as “Child Abuse and Neglect Annual Report Fiscal Year YYYY.” Within this report and using its Appendix, a table will be labeled as “FY [Fiscal Year] YYYY Substantiated Children by Category of Abuse/Neglect.” The total number values under Physical Abuse, Neglect, Emotional Abuse, and Sexual Abuse are captured.

#### <u>Coding:</u>
Table 1. Total cases
Variable Name  | Variable Description
------------- | ------------- 
Substantiated  | Number of substantiated child abuse/neglect investigations for children under 18. This indicator represents the number of substantiated cases, not an unduplicated count of children who experienced child abuse/neglect.<sup>4</sup>
Units Reported  | Total number of cases<sup>4</sup>

Table 2. Types of abuse
Variable Name  | Variable Description
------------- | ------------- 
Substantiated  | A finding that a preponderance of evidence exists to conclude abuse/neglect has occurred or is occurring as a result of the observation of visible signs, physical and/or credible verbal evidence provided to the Children’s Service Worker by the child, perpetrator or witnesses in accordance with the definitions of abuse/neglect. This includes cases which are adjudicated by the courts.<sup>5</sup>
Units Reported  | Total number of cases<sup>5</sup>

#### <u>Data Manipulation</u>
Missouri data in units of total number were organized into spreadsheets imported into R programming software. With R, the total numbers were converted into rates per 1,000 cases. The DPLYR R-package was used to clean and manipulate the data.
[https://drive.google.com/drive/folders/1p5BholWwRB2cguLb_wSegJldkB70gKHk](https://drive.google.com/drive/folders/1p5BholWwRB2cguLb_wSegJldkB70gKHk)


## Methodology
### <u>Challenges & Limitations</u>
<u>Data Challenges</u>
Certain organized counties on published reports are organized based on region. The way in which interns organize these counties, through Google Sheets, are in alphabetical order. This discrepancy may present some difficulty when entering data. On occasions, data can become mixed up thus fortifying the possibility of publishing incorrect data.

In addition and specifically toward the Missouri data release, there was a table published side-by-side to our necessary “FY [Fiscal Year] YYYY Substantiated Children by Category of Abuse/Neglect” report. This other nearly identical table in the Appendix was called “Substantiated Incidents by Category of Abuse/Neglect” could have been a source for confusion when inputting data. Since this report can be confused with our necessary one, it becomes worth mentioning here.

<u>Accessibility of Data: Formatting</u>
Missouri state websites report Child Abuse data in various formats which can complicate any efforts to automate data entry. Formats used to report child abuse data include .pdf, .csv, excel, and Microsoft Bl, to name a few.

<u>Missing Data</u>
Volunteers sometimes miss recording data from state that may regularly overwrite data on their state dashboard. Since there is no comparison set for use in almost all cases, historical data may also be present but not useful to solve this occurrence. Systems and protocols are still in development on mitigating these every so often occurrences from time-to-time.

Missouri does not report data on investigated cases, which are cases subject to investigation but may not be confirmed as abuse.

## References

1.  Medina SP, Sell K, Kavanagh J, Curtis C, Wood JN. *Tracking Child Abuse and Neglect: The Role of Multiple Data Sources in Improving Child Safety*. PolicyLab, 2012. Accessed April 24, 2022.
[https://policylab.chop.edu/sites/default/files/pdf/publications/PolicyLab_EtoA_Tracking_Child_Abuse_and_Neglect_2012.pdf](https://policylab.chop.edu/sites/default/files/pdf/publications/PolicyLab_EtoA_Tracking_Child_Abuse_and_Neglect_2012.pdf)

2.  KidsCount. The Annie E. Casey Foundation. Kids Count Data Center website. Accessed April 24, 2022.
[https://datacenter.kidscount.org/](https://datacenter.kidscount.org/)

3.  Centers for Disease Control and Prevention. *Fast Facts: Preventing Child Abuse & Neglect*. Centers for Disease Control and Prevention website.
[https://www.cdc.gov/violenceprevention/childabuseandneglect/fastfact.html](https://www.cdc.gov/violenceprevention/childabuseandneglect/fastfact.html)

4.  KidsCount. *Substantiated child abuse/neglect in Missouri*. Kids Count Data Center website. Accessed April 18, 2022.
[https://datacenter.kidscount.org/data/tables/9567-substantiated-child-abuse-neglect?loc=27&loct=2#detailed/2/any/false/1729,37,870,573,869,36,868,867,133,38/any/21983,21984](https://datacenter.kidscount.org/data/tables/9567-substantiated-child-abuse-neglect?loc=27&loct=2#detailed/2/any/false/1729,37,870,573,869,36,868,867,133,38/any/21983,21984)

5.  Missouri Department of Social Services. *Missouri Child Abuse and Neglect Annual Report*. Accessed April 18, 2022.
[https://dss.mo.gov/re/canar.htm](https://dss.mo.gov/re/canar.htm)

  

## Suggested Citation
When using data images, downloaded data, or shared document formats, please attribute BroadStreet as well as the original source, when applicable. For examples and more information, review this article which answers the question  ["How do I cite BroadStreet?"](https://help.broadstreet.io/article/citations/)

## Contributors
Brenna Jarvis, MPH; Sarah Murata; Tracy Flood, MD, PhD. A full list of the Broadstreet Institute volunteers can be found at [https://covid19dataproject.org/team-2/](https://covid19dataproject.org/team-2/)

## Questions / Feedback
Email the primary contributors at: hello@broadstreet.io
