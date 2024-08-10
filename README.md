# Analysis on Real Estate Dataset

Navigating Riyadh's real estate market can be challenging due to limited data. We provide an analysis of information on villas, apartments, and lands to offer valuable insights for anyone exploring real estate opportunities in Riyadh.

## Objective Questions

Our objective questions for the datasets are:

1. In what neighborhood are the most expensive and least expensive villas located?
2. Does the frontier location of a villa can affect its price?
3. What factors influence the price of villas?
4. What factors influence the price of apartments?
5. What are the average prices of lands intended for investment purposes?

## Dataset Overview

The dataset is divided into three parts:

- **Apartments:**
  - Columns: Property_Type, City, Neighborhood, Facade, Bedrooms,Living_Rooms, Baths,Area, Kitchen, Car_Entrance, Elevator, Floor, Age, furnished,Total_Price.

- **Villas:**
  - Columns: Property_Type, City, Neighborhood, Facade, Bedrooms, Living_Rooms, Baths, street width, Area, Living_Room_Stairs, Kitchen,Maid_Room, Drivers_Room, Annex, Yard, Swimming_Pool, Basement, Car_Entrance, Elevator, Total_Price.

- **Lands:**
  - Columns: Property_Type, Purpose, City, Neighborhood, Facade, Area, Price_per_Meter, Total_Price.
    
## Source of the Dataset

[details about the source of the dataset here]

## Exploratory Data Analysis (EDA)

The EDA steps taken in this project include:

1. **Reliability:** 
 The data is from Kaggle, and there is no specific source. However, since our objective is for learning, we can use it.

3. **Timeliness:** 
The data was last updated 10 months ago.

4. **Consistency:**
   There are inconsistent values, especially in the City and Neighborhood columns.

6. **Relevance:**
   The available data is consistent with the objectives of the analysis.
   There are irrelevant columns in all the datasets that we dropped, such as Property_Type.

8. **Completeness:**
   All three datasets (Lands, Villas, Apartments) had missing values.
   In the Lands dataset, missing values in the "Purpose" column were filled using imputation with the mode.
   In the Villas dataset, because there were many missing values in different columns, we chose to create two DataFrames: one with the missing values and one without, 
   depending on the purpose.
   In the Apartments dataset, for missing values
   
10. **Uniqueness:**
    All three datasets (Lands, Villas, Apartments) had duplicate rows, but we decided to keep them since they may represent different values, and there are no unique 
    identifiers to confirm they are true duplicates.
    
12. **Accuracy Check:** [Brief description of what was done]

## Key Insights

From our analysis, we gained significant insights related to the data:

1. [Insight 1 with the chart]
2. [Insight 2 with the chart]
3. [Insight 3 with the chart]
4. [Insight 4 with the chart]
5. [Insight 5 with the chart]
6. [Insight 6 with the chart]
7. [Insight 7 with the chart]
8. [Insight 8 with the chart]
9. [Insight 9 with the chart]
10. [Insight 10 with the chart]



## Storytelling Link

[ink of the story]



## Team Members

- Dania Alshehri
- Faisal Alzhrani
- Fahad Alsaadi
- Ashwaq Almalki
- Hatoon Aloqaily
