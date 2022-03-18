# Analysis_JiraTicket_TechSupportTeam

Technical support team work on Jira ticket for resolving issue raised by user. This project is about analysis and visualization of insight of jira ticket's various aspects like resolution time, ticket count handled by team and type wise, NPS(Net Promoting Score) score, Count of created and resolved ticket each day and each month wise ,SLA(Service Level Agreement) breached or met etc.

Data analyzed , visualized by using data science technique and based on that various insight/conclusion retrieved, necessary steps suggested.

This project is very important for any support team to make service better to customer. 


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

https://datastudio.google.com/reporting/b6b2f339-dba7-4b3e-b24a-77aa2aea406f

![image](https://user-images.githubusercontent.com/77465776/159096016-bedcd9d4-837e-4082-978f-584e40f76cea.png)

