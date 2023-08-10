# AtliQ-Hardware-Sales-Insights

A Power BI dashboard to understand AtliQ hardware goods sales trend!

## Dataset:

The `db_dump.sql` file above is the SQL database dump for our project. 

![image](https://github.com/Aestivial/AtliQ-Hardware-Sales-Insights/assets/69592060/9cd52c1a-fb0e-4750-a05c-ee5f0814089f)

After importing it to our server `DEV_sales_insights`, we go through the data to understand its structure and anamolies. Further analysis and visualizations are performed on Microsoft Power BI.

For example:- Using the Power Query Editor to process the data and remove records such as NULL (blanks), or unrequired attributes from tables.
![image](https://github.com/Aestivial/AtliQ-Hardware-Sales-Insights/assets/69592060/f6f1eb96-df85-4315-bf19-3322315834f2)

We also use Power Query Editor to convert attributes into more meaningful forms such as converting the Currency Column as follows using DAX:
![image](https://github.com/Aestivial/AtliQ-Hardware-Sales-Insights/assets/69592060/f0885706-2a7a-4eac-84a2-d2a8783071f2)

Post the processing, we head back to our dashboard section and select the `Enter Data` option, where we create a  "BaseMeasure" table and add new measures for every attribute in our final Dashboard. For instance, to create our "Revenue" measure we did the following:
![image](https://github.com/Aestivial/AtliQ-Hardware-Sales-Insights/assets/69592060/a9f74ac8-d55b-47bb-b98a-8793575541b1)

Similarly we populate the dashboard with many more measures (and their visualizations based on corresponding axis data) until our Final Dashboard looks like this:

## Final Dashboard:
![image](https://github.com/Aestivial/AtliQ-Hardware-Sales-Insights/assets/69592060/0b0fa7f4-04d8-456a-841e-b9612a9b3aa3)

Dynamic and responsive dashboard:
![image](https://github.com/Aestivial/AtliQ-Hardware-Sales-Insights/assets/69592060/b1f69d67-5f1f-44f7-9322-64f6a5b7dd1b)

## Link to the Power BI Dashboard:
[app.powerbi.com/groups/me/reports/Nayan's_AltiQ_Report](https://app.powerbi.com/groups/me/reports/f0beaed8-4488-407a-8529-bcc3085230f9/ReportSection?experience=power-bi)
