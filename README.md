# Call-Center-Home-Analysis-Dashboard
![Uploading Screenshot 2025-11-12 104931.png…]()

 ## Project Overview
The Call Dashboard Project focuses on analyzing customer service call data to monitor performance, identify patterns, and improve service efficiency using Power BI. The dashboard provides insights into call volume, response times, agent performance, and resolution rates. By leveraging Power BI, the project enables data-driven decisions to enhance customer experience and optimize operational processes.
 ## Dataset Description
The dataset used for the Call Dashboard contains detailed information on customer calls, agents, call duration, response time, resolution status, and customer feedback. It helps analyze service performance and identify areas for improvement across various call centers.
Call ID – Unique identifier for each call.
Agent Name – Name of the customer support representative handling the call.
Call Duration – Total time spent on each call.
Response Time – Time taken by an agent to respond to a customer call.
Call Type – Category of call (e.g., Inquiry, Complaint, Feedback).
Customer Rating – Feedback score given by the customer.
Resolution Status – Indicates whether the issue was resolved or pending.
Date – Date and time of the call.
 ## Business Objectives
Analyze call trends to identify peak hours and agent workload.
Measure and improve customer satisfaction through rating analysis.
Evaluate agent performance based on average call duration and resolution rates.
Reduce average response and resolution time for faster issue handling.
Create an interactive Power BI dashboard for performance monitoring.
 ## Tools & Techniques Used
Tool: Microsoft Power BI — Used for data transformation, modeling, and visualization.
Data Cleaning: Removed missing values, standardized timestamps, and ensured consistent data formats.
Data Transformation: Used Power Query to filter and reshape data, and DAX for custom calculations like total calls and average response time.
DAX Measures:
•	Total duration=[total call duration(min)]/60
•	Total call Duration (min) =sum(‘call center _call center[call duration in minutes])
•	Total-calls=count(‘call center_ call center’[id])

 ## Key Insights
Agents with faster response times have higher customer satisfaction ratings.
Complaint calls take longer to resolve compared to inquiries and feedback.
High-performing agents handle more calls per day with shorter durations and higher ratings.
Average customer satisfaction is improving month-over-month due to training and process optimization.
 ## Future Enhancements
Integrate predictive analytics to forecast call volume trends.
Add automated alerts for agents or managers based on KPIs.
Include live call data for real-time performance monitoring.
Enhance visuals with sentiment analysis from customer feedback.
