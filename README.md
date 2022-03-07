# Analysis_JiraTicket_TechSupportTeam

Technical support team work on Jira ticket for resolving issue raised by user. This project is about analysis and visualization of insight of jira ticket's various aspects like resolution time, ticket count handled by team and type wise, NPS(Net Promoting Score) score, Count of created and resolved ticket each day and each month wise ,SLA(Service Level Agreement) breached or met etc.

Data analyzed , visualized by using data science technique and based on that various insight/conclusion retrieved, necessary steps suggested.

This project is very important for any support team to make service better to customer. 


* Collected data of resolved tickets from atlassian Jira tool’s service desk used for project work.
* Pre-processed data -
   * Imputed missing data with other valid value.
   * Instead of individual ID of Assignee, having here AssigneeTeam name,the assignee person belongs to.This is required because, for a particular type of ticket,responsible        individual assignee may change over time but responsible assinee team doesn't change. This Assignee Team is target data.
* Did visualization 
   * Total ticket handled Assignee team wise 
   * Count of Total ticket raised ticket_type wise 
* Had new fetaure 'Resolution time' from two feature 'Created' and 'Resolved', calculated resolution time by day time difference of ticket created and resolved data.
*      
[Currently working to create a dashboard for all visualizatoins created in notebook] 

