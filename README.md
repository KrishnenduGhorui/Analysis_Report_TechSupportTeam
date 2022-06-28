# Analysis & report of Tech Support Team

Technical support team work on Jira ticket for resolving issue raised by user. This project is about **analysis**, making **report/dashboard** and **visualization of insight** of jira ticket's various aspects like resolution time, ticket count handled by team and type wise, NPS(Net Promoting Score) score, Count of created and resolved ticket each day and each month wise ,SLA(Service Level Agreement) breached or met etc.

Data analyzed , visualized by using data science technique and based on that various insight/conclusion retrieved, necessary steps suggested. 

This project is very important for any support team to make service better to customer. 

Dashboard/report link - 
https://datastudio.google.com/reporting/b6b2f339-dba7-4b3e-b24a-77aa2aea406f
https://app.powerbi.com/groups/me/reports/3cfd0ce3-0749-49c9-9563-98da0c191c05/ReportSection


* Collected data of resolved tickets from atlassian Jira tool’s service desk used for project work.
* Pre-processed data -
  * Imputed missing data with other valid value.
  * Instead of individual ID of Assignee, having here AssigneeTeam name,the assignee person belongs to.This is required because, for a particular type of ticket,responsible      individual assignee may change over time but responsible assinee team doesn't change. This Assignee Team is target data.
* Visualization 
  * Total ticket handled Assignee team wise 
  * Count of Total ticket raised ticket_type wise 
* Had new fetaure 'Resolution time' from two features 'Created' and 'Resolved', calculated resolution time by day time difference of ticket created and resolved data.
* Visualization on Resolution time- 
  * Distribution of ticket resolution time   
  * Mean, Median, Standard deviation of resolution time of each assignee team    
  * Mean reolution time each ticket component wise
  * Separate Scatterplot of resolution time for each assignee team
  * Total count of ticket in specified resolution time range
* Visualization on NPS/feedback rating  
  * Pie plot showing percentage of NPS feedback rating provided and not provided 
  * Barplot with count of NPS rate(1-10) provided
  * Countplot of NPS rating label(Promoter, Passive, Detractor) each assignee team wise 
  * Regression plot of feedback rating and Resolution time 
  * Barplot with count and Percentage of Count of NPS rate category, Resolution time range wise
* Heatmap showing correlation between fetaures 
* Lineplot of Created and Resolved ticket count in each day in a month 
* Lineplot of Created and Resolved ticket count in each month 
* Countplot of ticket SLA met and breached in a year 
* Lineplot with count of ticket SLA met and breached in each month

Some plots are shown below - 

![image](https://user-images.githubusercontent.com/77465776/159096016-bedcd9d4-837e-4082-978f-584e40f76cea.png)
![image](https://user-images.githubusercontent.com/77465776/176272138-2ec9be38-cd6d-42fc-a218-b95a5315daa4.png)![image](https://user-images.githubusercontent.com/77465776/176272400-ba96afd4-fbeb-4765-93af-a4a26f5b7ad2.png)
![image](https://user-images.githubusercontent.com/77465776/159981769-2d6e5c69-a4ef-48a4-87ec-66ca5140b5c5.png)
![image](https://user-images.githubusercontent.com/77465776/159981974-80e9029d-4e3f-4774-b916-f22a2e63733f.png)
![image](https://user-images.githubusercontent.com/77465776/159982122-98f9e9ec-5358-4cfa-869d-91a7c546b28b.png)
![image](https://user-images.githubusercontent.com/77465776/176270034-9ec26c24-c9eb-42bb-a1b0-5027a145d297.png)![image](https://user-images.githubusercontent.com/77465776/176269900-87194f42-434d-4747-8c70-f2ba417df32d.png)





