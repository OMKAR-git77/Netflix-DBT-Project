# Netflix-DBT-Project
End to End DBT  Data Engineer Project

# Description
The netflix-dbt-project is an end-to-end data transformation project built using dbt (Data Build Tool) to process and analyze Netflix datasets for actionable insights. This project demonstrates the power of dbt in orchestrating data workflows, transforming raw Netflix data into clean, analytics-ready models. It showcases core dbt concepts such as models, materializations, tests, macros, and documentation, while following modern data engineering best practices.

# Project Architecture
<img width="1920" height="842" alt="Screenshot (108)" src="https://github.com/user-attachments/assets/26886573-0705-4950-99cf-346dd1336813" />

# Technology Used
• dbt (Data Build Tool): For data transformation and pipeline orchestration.

• AWS S3: Storage for raw Netflix datasets.

• Snowflake: Cloud data warehouse for processing and analytics.

• SQL: Core language for dbt models and transformations.

• Python: For data preprocessing and custom scripting.

• Microsoft Visual Studio Code: IDE for editing SQL, Python, and shell scripts.

• Shell Scripting: For automation of data uploads and pipeline execution.

# Key Components
• Models:
     
     • Staging: Cleans and standardizes raw Netflix data from AWS S3 (e.g., titles and user activity).
     • Intermediate: Performs complex transformations, such as aggregating genre metrics or calculating user engagement.
     • Marts: Creates analytics-ready dimension tables (e.g., titles, users) and fact tables (e.g., viewership) for reporting.

• Tests:
    
    • Ensures data quality with checks for uniqueness and non-null constraints on key fields.
    • Includes custom tests for Netflix-specific data validation.

• Macros:
    
    • Reusable SQL logic for tasks like string normalization and engagement scoring.

• Seeds:
    
    • Sample datasets for Netflix titles and user activity, stored in S3 or locally for testing.

• Scripts:
    
    • Python: Preprocesses raw data before loading into S3 or Snowflake.
    • Shell Scripts: Automates data uploads to S3 and dbt pipeline execution.

• Documentation:
    
    • Model documentation for data lineage and dependencies.
    • Generated dbt docs for pipeline exploration.

# Future Advancements
To enhance the project's analytical capabilities, a future iteration will include the development of a Power BI dashboard to visualize insights from the transformed Netflix data. This dashboard will:
 
 • Connect to Snowflake to query the analytics-ready tables.
 
 • Provide interactive visualizations for key metrics, such as: 
      
      • Viewership trends by genre, region, or release year.
      • User engagement scores and watch time distributions.
      • Content popularity rankings and demographic insights.

 • Enable stakeholders to explore data through filters, drill-downs, and dynamic charts.
 
 • Leverage Power BI's data modeling features to create relationships between dimension and fact tables for seamless analysis.
 
 • Include automated refresh schedules to ensure real-time or near-real-time insights.



# Acknowledgments
 • Special thanks to Darshil Parmar for inspiration and reference through their project: https://github.com/darshilparmar/dbt-databuildtool--masterclass-netflix-project
 
 • Gratitude to dbt Labs for creating dbt and providing open-source tools and resources.
 
 • Thanks to Snowflake for powering the cloud data warehouse used in this project.



