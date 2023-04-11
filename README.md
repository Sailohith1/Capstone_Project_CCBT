# Capstone_Project_CCBT
Capstoen-project-description
Research focus: 
Metrics collection and management of data related to Heavy vehicles and Automobiles using 
Azure cloud and Amazon web services platforms.
Abstract
Metrics collection and monitoring of the data received from automobiles regularly using the IoT 
devices and sensors and storing the data in Azure cloud for analysis is proposed, which is economical 
and cost-effective for automobile industries. Data collection and research play a crucial role in 
organizations' success as they make decisions dynamically and suggest changes if needed. Also, the 
safety of the drivers and workers on board could be assured when they encounter collisions and firerelated accidents on highways. The outcomes of this project would help the Automobile industry by
rolling out many new features and adding more safety measures in heavy vehicles.
The layout of the entire project starts with the installation of an IoT device in the automobiles,
which captures all the parameters such as speed, heat emission, engine temperature, outside 
temperature, and many other metrics and sends the telemetry data to Amazon Web Services cloud in 
the form of JSON and from there we need to push the data to Azure cloud for further analysis. Once the 
data is received in the Azure cloud, it is validated for duplicates and incorrect information. Then it will be 
pushed to the Azure SQL server for storage and further analysis.
Project distribution:
This project would be a combined effort of all the team members, starting with Designing the 
entire architecture, overseeing the project progress, exploring the feasibility of the services, and moving 
the data to Azure Cloud BLOB storage will be performed by Akhilesh Sivagouni and Pallavi Kammari. 
Creation of the data processing services in Azure data lake and accessing the Azure BLOB storage into 
the data lake container through data factory pipelines and integrating triggers to each channel would be 
managed by SaiLohith Velisala and Anirudh Durbhakula. Creation of test cases and ensuring the testing 
is on track, creating the data pipelines between the staging server and SQL database server, and 
confirming the test cases would be performed by Venkata Hanuma Sai Vishwak Kumar Kari and Madhav 
Abhishek Yaram.
Technologies used in this Project:
• Azure Blob
• Azure Data Lake storage
• Azure Key vault
• Azure Functions
• Azure SQL server
• Azure SQL database.
3
Statement of Need
The main aim of this project is to address the ongoing fire accidents caused by internal engine 
heating/malfunction, track the vehicle to protect the driver in the event of a collision, and follow the 
vehicle's health. This is achieved by collecting metrics related to many factors, such as temperatures of 
the engine and the outside world, speed of the vehicle, and heat emission activity. To create a safe 
environment for the drivers and workers on board the heavy vehicle, we took the project of collecting 
the telemetry data using an IoT device and analyzing the output JSON files received from the Azure SQL 
database.
After the successful completion of this project, we will be creating a new channel to collect the 
metrics of automobiles and store them in a cloud environment (Azure) for research and analysis 
purposes. This would primarily benefit the existing automobile industries and many new upcoming startups in the field of automobiles.
