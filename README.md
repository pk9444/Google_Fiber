# Google Fiber 


This is the end-of-course project that was completed for the Google Business Intelligence Certificate Program. For this case study, the business scenario of an interview with Google Fiber was imagined, based on which, a completed Business Intelligence lifecycle is to be developed.

## BI Lifecycle 

The project was divided into three phases throughout the program: 

### Phase-1 : Project Planning 

In this phase, the project plan was rolled out and some essential documents were created from the meeting notes from the stakeholders.

1. Stakeholders Document

   - The core Business Problem was defined. 
   - Important stakeholders were identified.
   - How the BI tools and process will be used by end-users were planned.
      
2. Project Requirements Document

   - The stakeholder requirements and key dependencies were listed per the meeting notes. 
   - How will the success of the project be measured? For this, the S-M-A-R-T methodology was applied.
   - Some underlying assumptions were listed.
   - The User Experience, accessibility factors, and roll-out expectations were defined. 

3. Strategy Document
   
   - Based on the project requirements document, the strategy for building the BI tool or the ultimate dashboard design was imagined.
   - The Dashboard functionality was defined i.e. what features the dashboard must contain or would be nice to have.
   - All the charts that would be included in the visualization were documented, along with dimensions and measures and how they address stakeholder needs.   

### Phase-2 : Data Preparation 

For this phase, raw data was provided as three CSV files that represented three market types. There are two approaches with which the data could have been prepared: 

1. Merging the files using SQL in BigQuery
   
   - Create a Dataset in the BiQuery console.
   - Add Table -> upload the file for market-1 as data table.
   - Create two data tables for market-2 and market-3.
   - Merge the three data tables using SELECT and UNION SQL query with the necessary columns [NOTE: Avoid using "SELECT * FROM" as it adds more latency and may require additional optimization]
   - Save the merged table as a CSV file or upload it into Tableau  
   
2. Merging the files using UNION in Tableau
   - Upload the three CSV files into Tableau Public (or Tableau Desktop).
   - The three files will be uploaded as three data tables in the Data Source section of Tableau.  
   - Verify and Validate that columns are consistent with each other, check for column names, data types, and the cardinality (for a successful UNION cardinality of all three tables should be same)
   - Drag and drop one table over another and merge them.    
   

### Phase-3 : Dashboard Design 


