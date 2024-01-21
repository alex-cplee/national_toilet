<head>Public Toilet Australia - Power BI Dashboard</head>

A Power BI Dashboard showing currently open public toilet facilities in Australia. Quickly made this under a few hours.

Data is now pulled directly from data.gov.au API. 

If you have access to Power BI Service (like I do at work), you can create a Query for this API, and then save the Query as a Dataflow. In the Power BI file load the "Toilet Map Data" query using Dataflow instead. Publish the Dashboard. 

The advantage of this approach is that you can set the refresh time for both Dataflow and Dashboard, meaning that all data will be refreshed automatically!
