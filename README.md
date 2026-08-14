# Mini-project
This Project Contain information about bike buyers details.
MINI PROJECT  SUMMARY

RAW DATA=https://www.kaggle.com/datasets/heeraldedhia/bike-buyers?select=bike_buyers.csv#:~:text=calendar_view_week-,bike_buyers.csv,-calendar_view_week
1	DATA Cleaning and Transformation to excel 

Step 1: Import data
      The Restaurant Sales dataset (CSV file) was imported into MS Excel. 

Step 2: Checked for Duplicate Records
The dataset was checked for duplicate value. but No
duplicate records were found; therefore, no rows were removed.

Step 3: Check null value and Handle that value
•	Blank value in the “GENDER” Column Were replaced with “unknown”.
•	Blank value in the “marital status” Column were replaced with “unknown”.
•	Blank value in the “Income, age” Column were replaced the calculating the impute value.
Create new columncalculate impute value (=IF(ISBLANK(E2),AVERAGE([Income]),E2)

Step 4: Sorting and filtering
                                     Sorted   A to Z   for “ID”


Step 5: Checked Data Consistency 
      The categorical columns were checked for spelling errors, extra Spaces ,  incorrect  capitalization,  and inconsistent values. No significant inconsistencies were found after preprocessing                                    
 Step  6: Create a Table
Homestyleformat as table create Format table
Step 7: Created a calculated column
•	Created New column “Income category”.
=IF([@[Impute Income]]<=70000,"High class",IF([@[Impute Income]]>=70000,"Low class"))
Step 8 : Create Pivot Table
Created 3 Pivot Table
•	Total customer region wise
•	Car and Bike Based Gender
•	Total Income commute distance

Step 9 :Create Dashboard
Visualized that three pivot Tables  
                                                                                                                                                                                                            
 



2	Data Visualization using Power BI

Step 1:  Import Data
    The Cleaned Bike buyers Data set was imported into Microsoft Power BI Desktop for visualization and analysis.

Step 2 : Normalization
Splitting that cleaned data set into small Table

•	Customer Table 
•	Income Table
•	Location Table

          Step 3: Created Calculated Column
          Created new column named “Age category” 
          Categorized :  Age category = if('customer table'[Age]<=39,"young adults", if('customer table'[Age]<=59,"Middle-age adults", "seniors"))
    
           Step 4: Created measures for analysis
         This measures are used aggregate data 
•	Total Costumers
•	Average Income
•	Maximum Age
•	Minimum Age
•	Total Customers Every Categorized Categorize

             
         Step 5 :Create slicers
         Create Slicer to Occupation , Gender

       Step 4: Created the Executive Analysis Dashboard
           The first dashboard, Executive Analysis, was created to provide an overall view of the          Buyers Details
           KPI cards were created for:
•	Total Customers
•	Average Income
•	Maximum Age
•	No of House Owners
           The following visualizations were created
•	Total Income By Occupation : Column  Chart
•	Income Trend By Commute Distance :Line chart
•	Count Id By Occupation and Income Category : Tree Map
•	Count Bike  and 	Sum Of Income By Region :Map
 Logos and visual icons were inserted into the dashboard to make the Executive Analysis page more attractive and visually appealing.

  Step 5: Created The Customer analysis
 The second Dash board , Customer analysis, This Dashboard Has customer personal Details
  No KPI Cards
     The following visualization were created
•	Income by Gender Category : pie chart
•	Count of customer  By Marital Status :Donut chart
•	Maximum age with income range : Scatter chart
                       Logos and visual icons were inserted into the dashboard to make the Executive Analysis page more attractive and visually appealing.

Step  6: Create Perform Analysis
 Third Dash board is perform analysis
The following visualization were created
o	Total Income By gender with Education :Clustered Bar Chart
o	No of Cars By region    :Line and clustered column chart
o	Marital Status by Home Owner :Funnel chart

Step 7 : Create Table and Matrix
  Create 4th  visualization Table and matrix

Step 8 :Create insights
Create 5th visualization buyers insights
Create Decomposition Tree chart (HIGH VALUE) and added narrative. They are Al Visuals.
Step 9 :Page Navigation
 Add page Navigation in all visuals
INSERTBUTTONSNAVIGATION PAGE NAVIGATION

 Step 10: New page
Create new page named “Home”
To include Introduction in this visualization charts.
Step 11: save
Saved this power bi sheets

 Prepared By 
     ASNA SHEFI VP









