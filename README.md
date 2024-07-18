Park Inspection using Power Platform, SQL and AI Hub

Objectives:
•	Build an easy-to-use App for Tabs which The Park inspectors carry to Parks
•	Simple and High performant Application where Park inspectors can pull the information of a park quickly and view or update previous comments and ratings.
•	Data is centrally stored and always available for other Park inspectors or Admins.
•	Leverage Artificial Intelligence capabilities and find the overall sentiment of the feedback
•	Send an immediate email to the admin if the sentiment is negative

Functional Overview:
ParkInspection is a Tablet App that can be used by Park Inspectors to review the comments and ratings of various Parks. Inspectors can select a park and view the ratings, and feedback add further comments, or edit or remove any of the previous feedback or ratings. 
•	The user can select a park from the list of parks to view the feedback and ratings information
•	The user can add a new comment and rating for the selected park 
•	The user can edit an existing comment or rating 
•	The user can delete an existing review 
•	An email of the user’s sentiment is sent to the parks manager



 

Technical Overview: 
This application has been built using Power Apps (Canvas app) which connects to the SQL Server database to manage the parks data. 
I used various formulas to format the data and customize look and feel in Power App
Power Automate reads the user comments and sends it to the AI Hub for Sentiment Analysis. An email will be sent to the Parks Manager to notify the sentiment (positive or negative) of users.
