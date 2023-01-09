Broadstreet United States Child Abuse Dataset 

Structure of the Dataset
Data Dictionary:

Variable
Definition
County
The county for which the data is reported.
FIPS_Code
Federal Information Processing Standards code that uniquely identifies countries and county equivalents in the United States.
[year]_Physical
Counts of reported “physical abuse/bodily injury” for that year.
[year]_Emotional
Counts of reported “serious mental injury” for that year.
[year]_Neglect
Counts of reported “serious physical neglect” for that year.
[year]_Sexual
Counts of reported sexual abuse for that year.


Content:

Data Source:
Data for Virginia was available on the Virginia Department of Social Services website. The data was found within “Abuse & Neglect - Types of Referrals (by locality)” for the years 2010-2016 and “Abuse & Neglect by Locality” for 2017-2021. Within this report each county provides the relevant data under the section “Accepted”. The data captures total number values per county for Physical Abuse, Physical Neglect (Neglect), Sexual Abuse, and Mental Abuse/Injury (Emotional Abuse). 

Data Collection & Input:
Data is collected weekly for each county in the United States that is reporting any extent of child abuse.
Data is collected as a cumulative count rather than a daily count. Types of abuse are provided comprehensively within yearly reports where cases are to be reported into an entire data set. Numerical cases reported under the “types of allegations” are data of interest; this indicates the case(s) are investigated, not confirmed cases of abuse.
When the county is not listed nor its numerical data, often from lack of collection (e.g. geological effects, data release phases), a “-” is used to denote this. When 0 cases are reported in a category, a 0 is used as the placeholder.


Coding:

Table 1. Types of abuse 
Variable Name
Variable Description
Investigated
Data is listed under “Allegations” - Reports are those that allege a child might have been a victim of child abuse1
Units Reported
Total number of cases1




Methodology
Challenges & Limitations
Data completeness: Some counties do not report certain kinds of abuse for some years. For example, Bath County did not report Sexual Abuse in 2012. Locations of significant missing data include but are not limited to the following: Nottoway County, Fairfax City, Buena Vista City, Emporia City, Poquoson City, and Salem City. 

Definition discrepancy: “Physical neglect” is a category reported separately from “physical abuse” and is considered “Neglect” in our dataset. “Mental Abuse/Neglect” is considered “emotional abuse” in our dataset.

References
Virginia Department of Social Services. Child Protective Services Reports & Studies. Accessed November 13th, 2022.  Child Protective Services Reports & Studies - Virginia Department of Social Services. 

Suggested Citation 
When using data images, downloaded data, or shared document formats, please attribute BroadStreet as well as the original source, when applicable. For examples and more information, review this article which answers the question "How do I cite BroadStreet?"
Contributors
Project Leaders and Data Release Team Members (listed alphabetically by last name):

Gilianne Augustin; Meenal Khandaker; Riya Kumar; Ernesto Lopez; Rimple Patel; Lamya Serhir; Fu Zeng
A full list of the Broadstreet Institute volunteers can be found at https://covid19dataproject.org/team-2/

Questions/Feedback
Email the primary contributors at: hello@broadstreet.io



