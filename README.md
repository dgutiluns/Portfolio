# Portfolio

## Education
University of California, Berkeley

Bachelor of Economics and Data Science

Graduation Date: May 2027

GPA: 3.94

The Data Science Toolbox										
John Hopkins University (Coursera)
- Certification in R programming language 


## Work Experience
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

## Projects
### Simplifying RPA Data with a Custom Analytics Dashboard
#### Design Overview and Challenges
During my internship at Apollo Studios, another intern and I were tasked with analyzing a database containing over 4 million entries to generate insights for both internal use and client purposes. Our initial challenge was to develop a script capable of analyzing the data, followed by producing analytics based on specific requirements set by the company and, in some cases, the client.

Additionally, we were responsible for setting up a scheduled, automated email system that would deliver personalized insights to clients regarding their RPAs. We were also asked to create a front-end software solution that could visually present the data and allow for customizable analysis.

To accomplish this, we began by creating a Python script to scrape the MongoDB database. We then developed a Flask-based Python backend and a React frontend, hosted on AWS, to provide clients and employees with customizable, accessible insights into the current status of their RPAs.

#### The Problem with Current Data Insights at Apollo Studios

Apollo Studios operated on a MongoDB database that was accessed through MongoDB Compass. This software was beneficial in searching for client names, bot names, and a time period, although it was very inaccessible to understand. The software also did not provide easy, comprehensive analysis that one could just glance at and understand the data. Both the client and executives at the company wanted a solution to this problem, whereupon customers could easily understand how their RPAs were performing, and the executives could isolate which areas they would like to work on. Overall, the main problem was accessible understanding of the database. It needed a clean, frontend interface.

#### Who is this made for?

Executive at Apollo Studios

Specifications: Understanding their company’s data, both on a high and low level
Challenges: Could not easily understand the MongoDB database without downloading software and going through an onboarding experience. 
Could not gain insight into a lot of data very quickly, as it required them to do long searches that didn’t provide comprehensive analysis. 
Was unable to easily see which bots were performing well or underperforming to figure out where work was needed.

Client

Specifications: Understanding how their RPA service is performing
Challenges: The client was forced to just accept data presented in inaccessible email formats, often in manually created spreadsheets. 
There was a lack of customization in the date ranges and individual bot insights. They also faced difficulty in quickly understanding the statuses and performance of their bots. 
They also were dependent on Apollo Studios to provide insights, rather than easily accessing them whenever.

#### Developing a Solution

The Backend:
We needed to first develop the python script that could analyze the MongoDB database. This involved some iterations in generating insights although this is irrelevant to the current design process.
Myself and one other intern developed a python script that could iterate through all of the data points in the MongoDB. It collected unique statuses and grouped them alongside generating aggregate data insights.

The Frontend:
We decided the front end should be accessed through a web browser, so clients need not download software. This led us to using React, as it was a great library for accessible and beautiful interfaces.
I decided to use React since I knew it best and it would be able to create beautiful frontend UI. I learned a lot about how difficult it can be to turn these design dreams into realities.

#### Development

https://github.com/user-attachments/assets/209521c8-6114-46fd-95a9-e34c5731b3f4

https://github.com/user-attachments/assets/d7b35af8-3f67-44d7-9ba8-52b2a0283a9b

#### Main Takeaways
Design Takeaways

This was my first industry design experience. I learned what it meant to design in a team, and receive feedback from supervisors and peers.

I also learned how to design with a clear business objective. It was very enjoyable to have a clear problem and goal, and work my way to a solution.

Technical Takeaways

Empathy for your fellow developer. As I had to build anything I dreamt up, I learned what it takes to actually program something - and make sure it works in many edge cases. 

One of the most important design / technical mechanics I learned more about are micro interactions. They should be used sparingly, and only in places where they unexpectedly delight a user. And of course, don't make them impossible to code.

### Automated Email Report
#### Overview
During my internship at Apollo Studios I was given a task with another intern to develop an automated email report that would be sent out monthly to each one of Apollo's customers giving them a full summary on the performance of their bots. The report would include an introduction followed by a table displaying various stats summarising the performance of the bots in a simple comprehenive overview. 

The process consisted of cleaning the data from the database to make it understandable for the customers and allow them to engage with the activity of their bots. We started with over 4 million entries as a base to develop the program. The program would filter out multiple layers to find all the bots that are active in a given company then calculate the relevant statistics to add to the table.

The design of the email was also important. The email was a representation of the company and we wanted to seem confident in the preformance in our bots and by being transparent in a professional looking manner it in invokes trust in the client for our service. The full service at the end was hosted on AWS and successfully ran and emailed out reports to all clients individually.

### The Problem with Past Reporting Methods
Apollo began getting inqueries from their clients asking how they can evaluate whether or not contniuing with their service was cost efficient or not. It became essential that the clients were able to see the performance of their bots including: how active they were, how many times they failed, and how many times they were successful. Another imporant aspect was that the clients should have been able to understand the information that allows them weigh whether or not the bot it worth it. In other words, the infromation that we give to them should be concise and clear and presented in a way that they would comprehend. Before the commencement of the development of this email service, clients could not evaluate the real succes of their bots. Apollo as a company wanted to be transparent and show that they are confident in the perforamnce of their service and wanted to start this monthly email report to continue to build long lasting relationships with their clients that depended on trust. 

## Room Radar App
### Overview:
This porject was part of a Data Science club at UC Berkeley called Open Project. We aimed to develop an app that alerts students about room availability across campus at all times. I worked with a team of four and we divided into frontend, backend, and Data Science focused groups. I was mainly in the Data Science and frontend team. The main issue we aimed to address was overloaded libraries by providing students with insights on other available study spots. The beginning of the project depended a lot on the data team to collect, clean, and present all the data on room schedules and resrvations to create a dynamic schedule for students to use. 

Once the data team was done I worked on the frontend development and interface design of the app which was equally as important. For the frontend development I worked a lot with HTML and Javascript to develop the interactive features, structure content on pages, and make the interface appealing to the audience. Before this stage a lot of the UI was designed using Figma to visualize the interactive features and develop a variety of prototypes. We experimented with different effects and animations and were able to create a responsive design with unique features. Finally, we worked on integrating these designs with the backend APIs to deploy the app on a hosting service that would ensure optimal performance.

### Purpose of the App:
During midterm and exams seasons the libraries receive a lot more traffic and students struggle to find a spot to study. There are time when I spend more time trying to find a spot than actually studying. At Berkeley there are hundereds of rooms usually used as classrooms for lectures or discussions that are vacant the majority of the time. All these rooms could be used as study rooms but most students don't know that studying in these rooms is an option. Room Radar aimed to compile data on the availibility of all rooms on campus and organize them into a comprehensive format where students can know about the availibilty of rooms, sign up for rooms, and report empty ones. 

### Main Takeaways:
This project was my first time working and meeting my team so it took a lot of organization and collaboartion to ensure that all parts of the project were being covered. The projects could not all be done at the same time, so the start of someone work depended a lot on another person finishing their part of the project. Moreover, not everyone was specialized on a specific part of the project and instead we all worked to help each other on areas in which we felt stuck. 

Technical Takeaways:
The frontend experince from this projects was a great opporuntity for me to advance my familiarity with JavaScript and sharpen my design skills on Figma. T

