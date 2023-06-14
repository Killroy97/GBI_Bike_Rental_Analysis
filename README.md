# Exploring a Business Scenario with GCP and Tableau.

[![License](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)

**Project Summary**

The **Cyclistic Customer Insights project** focuses on analyzing customer data from the bike-sharing service in New York City, provided by Cyclistic. The project's objective is to gain valuable insights into customer behavior, preferences, and demand patterns to inform the company's business planning and growth strategies.  
Cyclistic, in partnership with the city of New York, provides shared bikes across Manhattan and neighboring boroughs. As part of the business planning process, the Cyclistic Customer Growth Team aims to understand customer demand at different station locations. To achieve this, the team has collected comprehensive data on customer trips, including start and end times, locations, bike identification numbers, and customer types.  
The **goal of this project** is to grow Cyclistic's customer base by gaining insights into customer preferences, successful product features, and identifying potential station growth opportunities. By analyzing the large dataset of millions of rides, we will create a comprehensive dashboard that summarizes key insights for the leadership team.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [License](#license)
- [Contact](#contact)

## Features

**Objectives** 
The main objectives of this project could be listed as follows: 
1. Understand customer preferences and usage patterns.    
2. Aalyze bike usage to determine the popularity and demand at different station locations.    
3. Investigate the impact of weather conditions on customer activity levels.  
4. Identify trends and insights from the summer of 2015.    
5. Measure the year-over-year growth in the number of trips.    
6. Assess congestion at stations and analyze the net flow of bikes in and out of each station.    
7. Explore the overall number of trips across various starting and ending locations.    

**Description and Process** 
**Data Pre-processing**  
The datset was provided by Google, as a part of Google Business Intelligence Professional Certificate. The Project planning documents such as the stakeholder, project and stratgeic documents were drafted to highlight the project process, important KPIs and to create an overall understanding of a real workspace scenario.   

The initial dataset contained zip codes, the nighbourhood and borough details. These were subsequently integrated with a publcly available big query data about citibikes in newyork.   
The initial data set was imported in Google cloud platform for data integration and enrichment.   

![image](https://github.com/srikar-mulgund97/GBI_Bike_Rental_Analysis/assets/132211845/b10918d4-31ec-4594-9ac2-68f47d90d649)

![image](https://github.com/srikar-mulgund97/GBI_Bike_Rental_Analysis/assets/132211845/a6e1f5eb-32e1-4eb4-b4bb-19cd7c5a67c4)

The final dataset concluded with the attributes needed to asses the relevant business scenario and hosted the following attributes.  

![image](https://github.com/srikar-mulgund97/GBI_Bike_Rental_Analysis/assets/132211845/56fad0e7-f11a-4806-9bdf-aea2fe35ad64)

**Data Analysis & Visulaization**
Tableau Public setup was selected to design and implement a Dashboard capable of giving insights about the business problems to the stakeholders.  
- The datset was impoted into the desktop version of Tableau public.  
-  The final Dashboard showcases the following visualizations:   
a) Area Map of the Neighborhoods.  
b) Total trip minutes by the start station.  
c) Total trip minutes by the end station.  
d) Total trips by Neighboorhood, color graded from minimum to maximum, represneted by months.  
e) Total Trips, month wise from December 2018 to December 2020.  

**Note:** The filters for the Area map are turned on, and a slicer has been provided for the subscriber type for the user to filter and analyse further. 

## Installation
The relevant Tableau files can be found in this repository. The Tableau Dashboard can be directly downloaded [here](https://public.tableau.com/views/TripDataforaScooterRentalCompany/Dashboard1?:language=en-US&:display_count=n&:origin=viz_share_link) 
The files can be used in the following way:  
a) Tableau workbook:once you navigate to the link, you can find the download button on the bottom right corner. If you choose to download the workbbok, please select approporiate version to get the best compatibility.  

![image](https://github.com/srikar-mulgund97/GBI_Bike_Rental_Analysis/assets/132211845/8734ea49-56d1-42fc-97cb-1487b1e6f386)      ![image](https://github.com/srikar-mulgund97/GBI_Bike_Rental_Analysis/assets/132211845/147e646b-f939-4f63-abe3-69721c9fc0a6)


b) The cleaned and Integrated dataset can be found as Integrated Dataset.zip in the repository to analyse the attributes or can be used to import into a new project to develop other visualisations.   
c) A pdf file is present to have a quick look!

Please ensure that you adhere to the project's coding conventions, documentation guidelines, and code of conduct.

## License
This project deatils were drafted by Google Career certificates and was provided through the certification "Google Business Intelligence Professional Certificiate" 
This project is licensed under the [MIT License](LICENSE).

## Contact

If you have any questions, suggestions, or feedback, please feel free to reach out to us:

- Project Website: [Tableau](https://example.com)
- Email: srikarmulgund97@gmail.com

