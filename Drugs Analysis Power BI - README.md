# My third capstone project
## *Data Analysis on Drugs Offence in Singapore, using Power BI*

I have used 10 datasets from Singstats and Data.gov website. 

The purpose of the analysis is:
- to understand the trend of drugs offences in Singapore
- to understand the demographics of the drugs abusers in Singapore

Below is the Model View and a preview of the Dashboard:
![Screenshot of dashboard](https://imgur.com/7kCxszo.png)
![Screenshot of dashboard](https://imgur.com/9Qx6o5G.png)
![Screenshot of dashboard](https://imgur.com/duJ0d3H.png)

# How I used PowerBI to analyse
- Tranformed all the Datasets by using tranpose, remove rows, change column type from whole numbers to Date, use first row as Headers
- Created a Date table using DAX with Calendar formula 
- Connected the Date table to all the 10 datasets using the common column Year.
- Encountered issues when converting the data type to Date, hence I have to format the column using the raw CSV file and re-upload the file to PowerBI 
- For Abusers dataset, it was not consistent as one file has Repeat status while other 3 files do not have Repeat status. It only has Total and New status. So, I manually calculated the Repeat status and included in the 3 files; re-uploaded it so that all my charts can be connected and changed as per the Slicer for Status.
- Created a Drillthrough for Drug Offence Year trend chart to further drillthrough and find out which year has how many offenders who were executed and how many were in Drug Rehabilitation Centre
- Created bookmarks to navigate to each page
 

# Insights from the analysis
- Among all the offences in Singapore, drug offences is the highest at 67%.
- Drugs Offences are decreasing over the years especially in 2020 and 2021. 
  - This could be due to COVID-19 pandemic
  - More efforts have been put forth at the ICA immigrations clearance checkpoints 
  - More raiding activities conducted by the officers
  - More awareness are raised in schools with talks by SANA (Singapore Anti-Narcotics Association).

- However, there is an increase in the numbers of drugs addicts in Drug Rehab Centre
- In addition, the age group that has the highest number of inhalent abusers is age below 20 years old. This is quite concerning and needs to be addressed by giving more talks, counselling and raising more awareness among young adults in schools.
- There used to be alot of posters in lift lobbies or public spaces about smoking and gambling. These days, we also start to see posters about vaping. Hence, there are currently not enough information about drugs abuse in public spaces.
- More efforts could be put in place in raising awareness in the public instead of just schools so as to maximise the chances to reach to wider audience as not all young adults attend school on regular basis. It is also important to raise awareness among the older people who are in their mid 20s to 50s.



Below is a link to my Linkedin.
[Linkedin Link]( www.linkedin.com/in/karen-ang-44776170)















   
