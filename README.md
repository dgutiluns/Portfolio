# Portfolio

### Education

### Work Experience
Data and Product Intern - Apollo Studios  						     
Intern	         			        							             
- Developed a program that accumulated data on over forty active robots and created automated monthly reports for over 30 clients providing them with summary statistics enabling them to evaluate the effectiveness of their bots
-	Full stack developed, built, and shipped an internal analytics dashboard that provides insights on the functionality of each bot to Apollo employees using a Flask Python backend API to a react frontend hosted on AWS
-	Employed data cleaning techniques to standardize the structure of the database made up of over 4 million entries

Data Scientist - Vodacom  
Intern
-	Worked with fraud detection models using mobile device identification, clustering, and data optimizing techniques (random forests and XGboost) to reduce losses in customer service by identifying and blocking fraudulent activities 
-	Exposed to advanced customer segmentation strategies including RFM analysis, roll-rate analysis, and propensity modeling on churn models to optimize product offerings on the mobile app and customer retention efforts
-	Learned to develop RPA programs and participated in AI ethics discussions to learn about responsible AI practices 

### Projects
## Simplifying RPA Data with a Custom Analytics Dashboard
#### Design Overview and Challenges
During my internship at Apollo Studios, another intern and I were tasked with analyzing a database containing over 4 million entries to generate insights for both internal use and client purposes. Our initial challenge was to develop a script capable of analyzing the data, followed by producing analytics based on specific requirements set by the company and, in some cases, the client.

Additionally, we were responsible for setting up a scheduled, automated email system that would deliver personalized insights to clients regarding their RPAs. We were also asked to create a front-end software solution that could visually present the data and allow for customizable analysis.

To accomplish this, we began by creating a Python script to scrape the MongoDB database. We then developed a Flask-based Python backend and a React frontend, hosted on AWS, to provide clients and employees with customizable, accessible insights into the current status of their RPAs.

#### The Problem with Current Data Insights at Apollo Studios

Apollo Studios operated on a MongoDB database that was accessed through MongoDB Compass. This software was beneficial in searching for client names, bot names, and a time period, although it was very inaccessible to understand. The software also did not provide easy, comprehensive analysis that one could just glance at and understand the data. Both the client and executives at the company wanted a solution to this problem, whereupon customers could easily understand how their RPAs were performing, and the executives could isolate which areas they would like to work on. Overall, the main problem was accessible understanding of the database. It needed a clean, frontend interface.

