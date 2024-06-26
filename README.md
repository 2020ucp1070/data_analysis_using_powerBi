PROJECT_TITLE:
"Unemployment-Data_Analysis-using-PowerBI"


DESCRIPTION:
This project aims to analyze and visualize the unemployment data across various regions in India using Power BI. The project explores datasets, cleans and queries data in MySQL, and retrieves it for analysis in Power BI. Retrieved data is connected to Power BI for visualization, including bar charts, line graphs and donut charts



STEP:1 DATA COLLECTION
SOURCE:
UNEMPLOYMENT IN INDIA - Unemployment dataset of each States of Iindia - “kaggle.com”

URL:
“https://www.kaggle.com/datasets/gokulrajkmv/unemployment-in-india”



STEP-2: DATA CLEANING (JUPYTER NOTEBOOK_ VS-CODE)
In this step, we used Jupyter Notebook and VS Code to clean the data downloaded in the previous step. The cleaning process involved removing missing values, handling duplicates ect,. The cleaned data was saved to a new CSV file for further processing and analysis.



STEP-3: IMPORT NEW_CSV_FILE IN MYSQL & QUERY TO EXTRACT_DATA (MYSQL WORKBENCH)
In this step, we imported the cleaned CSV file into MySQL and performed SQL queries to extract the required data for analysis.

➔Open MySQL Dashboard:
→New connection→Create schema→ Data import wizard→ Browse the file path → Click next → Apply.



STEP-4: LOAD_DATA INTO POWERBI (PowerBI)
In this step, we loaded the data extracted in the previous step into Power BI using the MySQL connector.

➔Open Power BI:
The "Get Data" option in Power BI is used to connect to the MySQL database and select the table containing the employment data.
→Getdata → More →MySQL Database → Connect.



STEP-5 CREATE_DASHBOARD (POWERBI)
In this final step, we created a dashboard using Power BI to visualize and analyze the data. We used various visualizations such as bar charts, line graphs, and heat maps to showcase the trends and patterns in the data. We also added filters, slicers, and drill-through functionality to make the dashboard interactive and easy to use. The final dashboard provided useful insights into the current state of unemployment in India and identified areas where additional support may be needed.



REPORTS_CREATION:
A report is a visual representation of data in a structured format, such as tables, charts, and graphs, which provides insights into the data. It typically focuses on a specific aspect of the data, such as sales performance or customer behavior.



