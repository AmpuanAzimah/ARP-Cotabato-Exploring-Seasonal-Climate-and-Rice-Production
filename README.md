# ARP-Cotabato-Exploring-Seasonal-Climate-and-Rice-Production
Visualization of Agro-Climate and Rice Production in Cotabato Province,  employing Power BI for effective data presentation and Phython Script for Analysis.

*First, install the Microsoft Power BI
*Download the code "Final_PowerBI.pbix" under this repository
*Open the Power BI get the data from the local repository. Power BI 
supports various file formats, databases, online services, and other platforms. Power query 
was used for data preparation. For the prototype since the data was prepared in an Excel file 
format, the file was easily retrieved and loaded into the repository.

*Once the file was retrieved, Figure it shows the navigator where specific entities/sheets 
in the Excel file should be selected. This navigator allows an overview of the selected entities 
that should be loaded into the system. At this point, similar tables were picked to facilitate the 
data selection process. There were seven (7) tables involved, rice production amounts by 
irrigated or rainfed harvest, crop area, humidity, annual temperature, precipitation, annual soil 
moisture, and radiation All these tables include year, and municipality to generate the 
associated visualization for rice production of Cotabato.

*The selected entities were now being loaded in Power BI. If the data 
needs modification the transform data allows updating and deleting attributes for any entities. If the 
data was prepared and cleaned ahead, then the load function should be selected. However, 
transformation of data was performed since the names of the column was not formally labeled and 
some of the fields were empty like in production and crop area. You can transform the selected data 
in Power BI by clicking the “Transform Data” button in the Navigation. 

*After all the data was transformed to acceptable format, the tables from the Power Query were 
loaded to the Power BI. This process enabled the further processing of the data inside the Power BI. An exploratory analysis 
was conducted to better understand the importance of the data and what were the factors affecting the 
production of Cotabato.

*There were three important views in the Power BI environment. One is, it will displays the report canvas. 
In the report’s canvas, this was where the agro-climate and rice production dashboard were created. 
The fields in the right side consist of all the entities that were loaded. Beside was the visulizations where
Power View was used to build visuals.

*Second, displays the data view where the agro-climate end rice production analytical 
dashboard was mostly shaped. Shaping the Power BI means transforming the data, such as renaming 
columns or tables, or removing or adding rows or columns, or changing data types. Like in agro-climate 
and rice production analytical dashboard where there was a need to add identifiers for each entity or 
field. This I when Power Query Editor was used to connect a certain query to the data source. The 
data should be shaped the way it was specified in the ERD.

*Third, the model view of all entities, tables, and its relationships. The model view 
helps to model complex relationships between many tables. In the analytical dashboard for agroclimate and rice production of Cotabato where excel file format was used, the model view helps to 
easily connect and manage relationships between entities while excel cannot do.

*In developing the agro-climate and rice production analytical dashboard, several methods were 
utilized to complete the dashboard. Using Power BI, allows the researcher to explore three methods: 
(1) power query, (2) power pivot, and (3) power view. Power BI supports data from Excel, CSV, JSON, 
various databases, and other platforms. The dataset of the agro-climate and rice production analytical 
dashboard was collected in an Excel file which was then selected and partially loaded into the 
application. Further, in Power Query, extracted, transformed, and loaded were performed for 
processing the data. Power pivot manages the data stored in the data model in a tabular format that 
serves as the data warehouse. The agro-climate and rice production analytical dashboard dataset initially 
retrieve the default structure of the excel file, so establishing the relationships between the 156 
attributes was important. The entity relationship diagrams have helped to support the structure of the 
agro-climate and rice production analytical dashboard. Additionally, it helped to link the tables when 
filtered by the municipality and by year. Power pivot allows creating calculations and integrating a new 
entry of data like generated year format. The power view helps present the data in reports containing 
images, maps, charts, etc. In the agro-climate and rice production analytical dashboard the 
visualizations were all available in Power BI. Although, some visuals like the maps require external 
shape files in JSON format and the benchmark tasks were essential design concepts to fully develop 
the agro-climate and rice production analytical dashboard.
