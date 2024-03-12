# Crop Production Analysis in India


##  Problem Statement:- The Agriculture business domain, as a vital part of the overall supply chain, is expected to highly evolve in the upcoming years via the developments, which are taking place on the side of the Future Internet.This Dashboard helps to understand the prodution of crops in India in year from 1997 to 2015.it also provides the understanding of crop production in India through different states,districts and seasons also get to know the area of states and crop.

##Steps Followed
- Step 1 : Load data into Power BI Desktop, dataset is a csv file.
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 3 : Also since by default, profile will be opened only for 1000 rows so you need to select "column profiling based on entire dataset".
- Step 4 : It was observed that in none of the columns errors & empty values were present. 
- Step 5 : For the Dashborad there are 3 pages named as "overview","Production" and "Area".
- Step 6 : In the report view, under the view tab, theme was selected.
- Step 7 : Since the data contain "Area","Production","seasons","State_name","District_name","Crop_name","Crop_year" thus in order to represent all these data a visual called KPI cards was added on the canvas.
- Step 7 : Visual filters (Slicers) were added for "crop_year".
- Step 8 : A watterfall chart was also added to the report design area representing the crop Production from year 19997 to 2015 on the very first page of overview.
- Step 9 : For the page of production one KPI card for average production and the visual of stacked coloumn chart for production of top 5 crop and bar chart for the production in seasons were added to the canvas.
- Step 10 : A visual of donut and pie chart for the production of top 5 states and district were added to the canvas.
- Step 11 : For the page of Area a visual of line chart for the area of top 5 crop and a funnel for the area of top 10 states were added to the canvas.

## Snapshot of Dashboard[Power BI Desktop]
Page 1 :overview
![Screenshot (7)](https://github.com/Harhare18/Crop-Production-Analysis-in-India/assets/101700437/3311c0fb-9dcd-41af-bcea-eb22c0fb86ec)  

page 2 :Production
![Screenshot (8)](https://github.com/Harhare18/Crop-Production-Analysis-in-India/assets/101700437/c5169771-9bfa-410e-b23e-399b2e426b63)

page 3 :Area
![Screenshot (9)](https://github.com/Harhare18/Crop-Production-Analysis-in-India/assets/101700437/608df66d-bcda-47e7-8ee8-f6fdea7690b1)


## Insights
Following inference can be drawn from the Dashboard    
  1. overview
- Total production is 1,251M
- Total No of district are 411
- Total no of states are 9613
- Total no of crops were 36
- The maximum production were in year 2011.

2. Production
- Wheat crop gives a maximum production of 1332.83M.
- The maximum production is in the whole year of 1,34,425M.
- Yanam,Yamunanagar,Yavatmal,Yadgir,Zunheboto are the top 5 district with a maximum production.
- Uttar pradesh,West bengal,Telangana,Uttarakhand,Tripura are tht top 5 states with a maximum production.

3. Area
- Wheat,Urad,Varagu,Water Melon,Yam are the top 5 crops which consists maximum area.
- Uttar pradesh consist maximum area of 40,286,36k. 
