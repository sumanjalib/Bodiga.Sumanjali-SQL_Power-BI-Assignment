Executive Summary

This project focuses on analyzing and visualizing Amazon Prime Video content through data-driven insights using Power BI. With over 9,600 titles, this dashboard provides an in-depth look into content trends, genres, release years, ratings, country-wise distributions, and more. The visualizations help in understanding the platform's evolution, audience focus, and global reach.
Through interactive charts and visuals, stakeholders can derive valuable insights regarding content types (movies vs. TV shows), genre diversity, director participation, and audience rating preferences. This project serves as an analytical tool for understanding media distribution strategies on streaming platforms.

 


Introduction

Background and Context
With the rise of OTT platforms, analyzing content data provides useful business and entertainment insights. Amazon Prime Video, being one of the largest platforms globally, offers diverse content that can be dissected for patterns and trends.
Problem Statement 
There is a need for better understanding and insights into Amazon Prime’s massive dataset. Manual analysis is time-consuming and inefficient.
4.3 Scope
The project explores visual data analytics of Amazon Prime titles, ratings, genres, release years, and geographies using Power BI. It is limited to the dataset provided and focuses on descriptive analytics.
4.4 Limitations
•	Dataset limited up to 2021.
•	Some data fields are incomplete (e.g., missing director or cast details).
•	Visualization is limited to Power BI features.
4.5 Innovation
Integration of rich, interactive dashboards showcasing comparative analysis, genre-wise trends, and rating distributions is a step toward automating streaming content analytics.

5. PROJECT OBJECTIVES
5.1 Project Objectives and Expected Outcomes
•	To develop an interactive dashboard using Power BI.
•	To extract insights on content type, genre popularity, and ratings.
•	To provide a strategic view for media managers and analysts.
platform.





Scope

This project focuses on job data extracted from LinkedIn, including fields such as job title, company name, location, required skills, domain, and experience level. The Power BI dashboard enables users to analyze data across multiple dimensions like city, company, role, and skill. While the scope is limited to static, preprocessed data, it provides a comprehensive view of hiring patterns during the selected time frame.

 


 




Limitations

The current version of the dashboard operates on a static dataset, meaning that the information represents only a snapshot in time. Real-time job updates or live API integration is not part of the current implementation. Also, the dashboard lacks predictive capabilities for forecasting future job trends. The data being sourced from publicly available listings may also introduce bias, as it does not include confidential or niche hiring practices.

Innovation

This project is unique in its ability to provide a 360-degree view of Amazon sales performance using Power BI. It integrates various data fields—such as product categories, city-wise sales, customer reviews, and delivery statuses—into a cohesive visual format. By using DAX measures and interactive visuals, the dashboard empowers users to make data-backed decisions quickly. The automation of insights and the visual storytelling element make this project a valuable tool for e-commerce analysis and future BI enhancements.
 


 
Project Objectives


Project Objectives:
1.	Data Cleaning and Preparation

To preprocess and transform raw datasets into a structured format suitable for analysis in Power BI. This includes handling missing values, renaming columns, changing data types, and creating calculated columns/measures using DAX.
2.	Data Modeling

To establish relationships between different tables such as sales data, product details, and shipping status. This step ensures that slicers and visuals work cohesively and allows for dynamic filtering across the dashboard.
3.	Visual Design and Layout

To create an intuitive and visually appealing dashboard by organizing charts, tables, slicers, and KPIs in a clean layout. Emphasis is placed on clarity, interactivity, and ease of navigation between multiple report pages.
4.	DAX Measures and Calculations

To develop meaningful calculations using DAX formulas, such as total sales, total units, returns, and customer reviews. These measures provide business-specific insights and allow users to compare performance across different dimensions.
5.	Interactive Features and Filters

To enable interactivity through slicers (e.g., date, category, status) and navigation buttons. These features empower users to explore data dynamically and focus on specific subsets of interest without modifying the underlying dataset.
 
Expected Outcomes:	


Sales Dashboard showing:
●	Overall and filtered sales values

●	Units sold and return (lost) statistics

●	Sales distribution across states and cities

●	Time-based sales patterns (monthly trends)

Product Dashboard revealing:
●	Best-selling products and categories

●	Number of customer reviews per product

●	Product-wise performance comparison

●	Insights based on shipping and order status

Operational Benefits:
●	Improved business insights for stakeholders through intuitive visuals and dynamic filters

●	Enhanced decision-making by minimizing the need for manual data analysis

●	A scalable Power BI solution that can be updated easily with new datasets or extended with features like trend forecasting or automated alerts.
 
Methodology and Results


Methods/Technology Used:
The project applies Data Analytics and Business Intelligence (BI) methodologies to transform raw Amazon sales data into meaningful insights. It includes:
●	Data preprocessing: Cleaning and transforming the sales, product, and order status data using Power Query Editor in Power BI.
●	Data modeling: Establishing relationships between tables (e.g., sales, products, reviews, and shipping), and creating DAX measures for calculations like total sales, units, and returns.
●	Interactive visualization: Utilizing bar charts, line graphs, slicers, and buttons to uncover patterns in sales trends, product performance, and regional distribution.
●	Descriptive analysis: Summarizing sales history to show what products and locations contributed most to revenue and units sold.
●	Diagnostic analysis: Analyzing returns, reviews, and delivery statuses to understand potential issues in sales or logistics performance.

Tools/Software Used:
●	Microsoft Power BI Desktop: Primary tool for dashboard creation, data modeling, and interactive visualization.
●	Power Query Editor: Used for cleaning, filtering, and shaping the data before analysis.
●	DAX (Data Analysis Expressions): For creating custom KPIs, aggregations, and calculations.
●	Excel/CSV Files: Data source format used for importing Amazon sales and product data.
●	MS Excel or Google Sheets: For initial inspection or minor data adjustments before loading into Power BI.
 

Data Collection Approach:
The data used for this project was manually collected from public LinkedIn job postings. Care was taken to include a variety of job listings across different companies, locations, and domains.
    Key steps:
•	Collected data fields include:
o	Job Title
o	Company Name
o	Location (City, State)
o	Experience Required
o	Skills Mentioned
•	The raw data was structured into tabular format and exported as a CSV file.
•	Preprocessing was done in Microsoft Excel to remove missing values, format dates, categorize job types, and standardize company names and skills.
6.4 Project Architecture
The architectural flow of the LinkedIn Job Analysis Dashboard project is as follows:
1.	Data Collection
o	Job listings were manually extracted from LinkedIn based on filters like date posted, job type, and experience level.
2.	Excel Preprocessing
o	Data was cleaned to remove duplicates, incomplete entries, and outliers.
o	Columns were standardized, and categorical fields were encoded where necessary.
3.	Import into Power BI
o	The cleaned Excel sheet was loaded into Power BI Desktop.
o	Tables and relationships were established.
4.	Data Modeling & DAX Implementation
o	Measures and calculated columns were created using DAX.
o	Example KPIs: Total Jobs, Unique Companies, Most Common Skills.
5.	Visualization Design
o	Visual elements such as pie charts, bar charts, stacked columns, and card tiles were created.
o	Filters and slicers for role, skill, location, company, and experience level were added for interactive exploration.
6.	Filtering and Drilldown
o	Users can dynamically explore trends based on their interests.
o	Multi-level drilldowns and interactive slicers enhance the dashboard’s usability and depth of insights.
Results	

The dashboard yielded several valuable insights based on the analyzed LinkedIn job data. The most frequently mentioned technical skills across job postings included Python, SQL, Power BI, Cloud computing, and Machine Learning. These skills are highly sought after in data analysis, cloud engineering, and software development roles.
Top companies hiring included:
•	Infosys
•	Tata Consultancy Services (TCS)
•	Accenture
Top job locations were:
•	Hyderabad
•	Bengaluru
•	Pune
Common job roles identified:
•	Data Analyst
•	Software Developer
Limitations

The current version of the dashboard operates on a static dataset, meaning that the information represents only a snapshot in time. Real-time job updates or live API integration is not part of the current implementation. Also, the dashboard lacks predictive capabilities for forecasting future job trends. The data being sourced from publicly available listings may also introduce bias, as it does not include confidential or niche hiring practices.

Innovation

This project is unique in its ability to provide a 360-degree view of Amazon sales performance using Power BI. It integrates various data fields—such as product categories, city-wise sales, customer reviews, and delivery statuses—into a cohesive visual format. By using DAX measures and interactive visuals, the dashboard empowers users to make data-backed decisions quickly. The automation of insights and the visual storytelling element make this project a valuable tool for e-commerce analysis and future BI enhancements.
 


 
Project Objectives


Project Objectives:
1.	Data Cleaning and Preparation

To preprocess and transform raw datasets into a structured format suitable for analysis in Power BI. This includes handling missing values, renaming columns, changing data types, and creating calculated columns/measures using DAX.
2.	Data Modeling

To establish relationships between different tables such as sales data, product details, and shipping status. This step ensures that slicers and visuals work cohesively and allows for dynamic filtering across the dashboard.
3.	Visual Design and Layout

To create an intuitive and visually appealing dashboard by organizing charts, tables, slicers, and KPIs in a clean layout. Emphasis is placed on clarity, interactivity, and ease of navigation between multiple report pages.
4.	DAX Measures and Calculations

To develop meaningful calculations using DAX formulas, such as total sales, total units, returns, and customer reviews. These measures provide business-specific insights and allow users to compare performance across different dimensions.
5.	Interactive Features and Filters

To enable interactivity through slicers (e.g., date, category, status) and navigation buttons. These features empower users to explore data dynamically and focus on specific subsets of interest without modifying the underlying dataset.
 
Expected Outcomes:	


Sales Dashboard showing:
●	Overall and filtered sales values

●	Units sold and return (lost) statistics

●	Sales distribution across states and cities

●	Time-based sales patterns (monthly trends)

Product Dashboard revealing:
●	Best-selling products and categories

●	Number of customer reviews per product

●	Product-wise performance comparison

●	Insights based on shipping and order status

Operational Benefits:
●	Improved business insights for stakeholders through intuitive visuals and dynamic filters

●	Enhanced decision-making by minimizing the need for manual data analysis

●	A scalable Power BI solution that can be updated easily with new datasets or extended with features like trend forecasting or automated alerts.
 
Methodology and Results


Methods/Technology Used:
The project applies Data Analytics and Business Intelligence (BI) methodologies to transform raw Amazon sales data into meaningful insights. It includes:
●	Data preprocessing: Cleaning and transforming the sales, product, and order status data using Power Query Editor in Power BI.
●	Data modeling: Establishing relationships between tables (e.g., sales, products, reviews, and shipping), and creating DAX measures for calculations like total sales, units, and returns.
●	Interactive visualization: Utilizing bar charts, line graphs, slicers, and buttons to uncover patterns in sales trends, product performance, and regional distribution.
●	Descriptive analysis: Summarizing sales history to show what products and locations contributed most to revenue and units sold.
●	Diagnostic analysis: Analyzing returns, reviews, and delivery statuses to understand potential issues in sales or logistics performance.

Tools/Software Used:
●	Microsoft Power BI Desktop: Primary tool for dashboard creation, data modeling, and interactive visualization.
●	Power Query Editor: Used for cleaning, filtering, and shaping the data before analysis.
●	DAX (Data Analysis Expressions): For creating custom KPIs, aggregations, and calculations.
●	Excel/CSV Files: Data source format used for importing Amazon sales and product data.
●	MS Excel or Google Sheets: For initial inspection or minor data adjustments before loading into Power BI.
 

Data Collection Approach:
The data used for this project was manually collected from public LinkedIn job postings. Care was taken to include a variety of job listings across different companies, locations, and domains.
    Key steps:
•	Collected data fields include:
o	Job Title
o	Company Name
o	Location (City, State)
o	Experience Required
o	Skills Mentioned
•	The raw data was structured into tabular format and exported as a CSV file.
•	Preprocessing was done in Microsoft Excel to remove missing values, format dates, categorize job types, and standardize company names and skills.
6.4 Project Architecture
The architectural flow of the LinkedIn Job Analysis Dashboard project is as follows:
1.	Data Collection
o	Job listings were manually extracted from LinkedIn based on filters like date posted, job type, and experience level.
2.	Excel Preprocessing
o	Data was cleaned to remove duplicates, incomplete entries, and outliers.
o	Columns were standardized, and categorical fields were encoded where necessary.
3.	Import into Power BI
o	The cleaned Excel sheet was loaded into Power BI Desktop.
o	Tables and relationships were established.
4.	Data Modeling & DAX Implementation
o	Measures and calculated columns were created using DAX.
o	Example KPIs: Total Jobs, Unique Companies, Most Common Skills.
5.	Visualization Design
o	Visual elements such as pie charts, bar charts, stacked columns, and card tiles were created.
o	Filters and slicers for role, skill, location, company, and experience level were added for interactive exploration.
6.	Filtering and Drilldown
o	Users can dynamically explore trends based on their interests.
o	Multi-level drilldowns and interactive slicers enhance the dashboard’s usability and depth of insights.
Results	

The dashboard yielded several valuable insights based on the analyzed LinkedIn job data. The most frequently mentioned technical skills across job postings included Python, SQL, Power BI, Cloud computing, and Machine Learning. These skills are highly sought after in data analysis, cloud engineering, and software development roles.
Top companies hiring included:
•	Infosys
•	Tata Consultancy Services (TCS)
•	Accenture
Top job locations were:
•	Hyderabad
•	Bengaluru
•	Pune
Common job roles identified:
•	Data Analyst
•	Software Developer
•	Data Engineer
These results indicate that demand is high in the IT and analytics sectors, especially in major tech cities. The dashboard makes it easy to visualize this data in real time and explore trends interactively.


6.6 Screenshots
This section includes visual screenshots of the Power BI dashboard. It highlights:
•	Top hiring companies
•	In-demand skills
•	City-wise job distribution
•	Job roles vs. required experience levels








 

MINI Project Working Screenshots




  

●	Dashboard

 






 









  
GitHub Link

https://github.com/sure-trust/BODIGA.-SUMANJALI-g16-sql/upload/main/Mini%20projects































 
Learning and Reflection


Learning and Reflection
This project has been a valuable learning journey, helping me grow both technically and analytically. By working with Power BI to build an Amazon Sales Dashboard, I gained hands-on experience in data visualization, dashboard creation, and business intelligence. I learned how to clean and structure raw sales data, build relationships between tables, write DAX formulas, and design visuals that present insights in a clear and impactful way.
One of the most important lessons was learning how to communicate stories through data. By using interactive elements like slicers, buttons, and filters, I discovered how to let users explore different views of the data, enabling them to make informed business decisions more efficiently.
I also came to understand the critical role of data accuracy and consistency. Every chart, card, and table needed to be precise to ensure users could trust the insights they were seeing. Whether analyzing sales by city or tracking returns, it was essential that the visuals were both accurate and user-friendly.
On a personal level, this project sharpened my problem-solving abilities, improved my attention to detail, and boosted my confidence in using Power BI. I now feel more equipped to apply these skills in real-world scenarios and contribute to data-driven strategies in business environments.
Overall, this project not only improved my technical capabilities but also deepened my understanding of how data can be transformed into actionable insights that support smarter business decisions.
 

 
Conclusion and Future Scope


Objectives
The primary goals of this project were to:
1.	Clean and Prepare Raw Data
Transform raw Amazon sales and product data into a clean and structured format using Power Query Editor.
2.	Build Interactive Dashboards
Design dynamic, multi-page dashboards that visualize sales performance, product trends, and geographic distribution.
3.	Perform Data Modeling
Create relationships between sales, products, and order status tables, and define calculated columns and DAX measures for key metrics.
4.	Visualize Key Insights
Use visuals such as bar charts, line graphs, cards, and slicers to highlight sales patterns, best-selling products, and high-return regions.
5.	Enable User Interactivity
Allow users to explore data interactively by filtering through date ranges, product categories, and delivery statuses.
6.	Enhance Decision Making
Equip	business	stakeholders	with	insightful	visuals	that support quicker, data-driven decisions in areas like sales strategy and logistics.
7.	Ensure Scalability
Develop the dashboard with flexibility to incorporate additional data sources or advanced analytics features like forecasting in the future.
8.	Improve Analytical Skills
Strengthen proficiency in data visualization, dashboard building, and applying BI tools like Power BI and DAX for real-world analysis.
 

Achievements
1.	Successfully Designed  Dashboards
Developed a multi-page Power BI dashboard to visualize Amazon sales performance, product insights, and geographic trends using interactive visuals and slicers.
2.	Advanced Data Modeling
Established clear relationships between sales, product, and order status tables; created calculated columns and DAX measures to generate meaningful KPIs such as total sales, units sold, and returns.
3.	Data Transformation and Cleaning
Used Power Query Editor to clean raw datasets by removing duplicates, correcting data types, renaming columns, and preparing the data for seamless analysis.
4.	Insightful Visualizations
Created impactful visual elements including bar charts, line graphs, cards, and slicers that highlight top-performing products, review patterns, and region-wise sales distribution.
5.	User-Friendly Interface
Built an intuitive, easy-to-navigate dashboard layout that allows users to interact with data using category filters, date slicers, and status selection for focused analysis.
6.	Demonstrated Analytical Thinking
Uncovered valuable insights such as best-selling cities, high-return products, and sales trends—demonstrating strong analytical reasoning and business understanding.
7.	Scalability and Future-Readiness
Designed the dashboard to be scalable, allowing for the future integration of live data, trend forecasting, and additional analytical features.
8.	Skill Development
Enhanced hands-on skills in Power BI, DAX, data modeling, and visual storytelling—boosting both technical expertise and real-world data analysis capability.
 

Conclusion
The LinkedIn Job Analysis Dashboard project represents a successful application of Business Intelligence tools in solving real-world problems. In a data-driven era where job seekers, students, and professionals are constantly navigating through evolving employment landscapes, this dashboard provides a structured and insightful view of hiring patterns, skill demands, and market trends. By transforming raw LinkedIn job data into interactive visualizations, the project bridges the gap between complex datasets and meaningful career insights.
Throughout the development of this project, various aspects of data processing, visualization, and analysis were explored. The use of Power BI allowed for seamless integration of cleaned datasets, application of DAX for dynamic metrics, and the creation of rich visuals like charts, slicers, and key performance indicators (KPIs). The dashboard offers real-time filtering capabilities that make it highly user-friendly and functional for diverse stakeholders including students, job seekers, and academic advisors.
The project not only helped reinforce technical skills in Excel, Power BI, and DAX, but also fostered critical thinking in terms of identifying patterns, extracting actionable information, and designing an intuitive user experience. It highlighted how visual analytics can transform decision-making, particularly in the context of career planning and skill development.
Overall, the project fulfills its objective of offering a simplified, interactive, and intelligent method to explore job market trends. It is a valuable tool that can aid individuals in aligning their skills with industry needs and planning their career growth strategically. With further enhancements like real-time API integration and predictive modeling, this dashboard holds the potential to evolve into a comprehensive, automated job market analysis platform.
Future Scope
1.	Real-Time Data Integration
Connect the dashboard to live data sources like SQL databases, web APIs, or cloud platforms to enable real-time monitoring of sales, returns, and delivery status, helping tea
