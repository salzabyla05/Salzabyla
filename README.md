# Company Dashboard

### Dashboard Link : https://app.powerbi.com/groups/me/reports/75355cc2-dfc8-4683-b3b3-563ebe4f0205?experience=power-bi

## Problem Statement

Create a dashboard containing group data clustering, time series, analyze features, key influencers, and 
decomposition trees, based on revenue and sales results from a company.

### Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is a csv file.
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 3 : Also since by default, profile will be opened only for 1000 rows so you need to select "column profiling based on entire dataset".
- Step 4 : It was observed that in none of the columns errors & empty values were present except column named "Arrival Delay".
- Step 5 : For calculating average delay time, null values were not taken into account as only less than 1% values are null in this column(i.e column named "Arrival Delay") 
- Step 6 : In the report view, under the view tab, theme was selected.
- Step 7 : Since the data contains various ratings, thus in order to represent ratings, a new visual was added using the three ellipses in the visualizations pane in report view. 
- Step 8 : A bar chart was also added to the report design area representing the number of satisfied & neutral/unsatisfied customers. While creating this visual, field named "Gender" was also added to the Legends bucket, thus number of customers are also seggregated according the gender. 
- Step 9 : New measure was created to find total average of sales by year.
        
A card visual was used to represent count of customers.

![Screenshot (493)](https://github.com/user-attachments/assets/a6822e00-7a23-430d-9bc3-e768231ee6f0)

 - Step 18 : The report was then published to Power BI Service.
 
 
![Publish_Message](https://user-images.githubusercontent.com/102996550/174094520-3a845196-97e6-4d44-8760-34a64abc3e77.jpg)

# Snapshot of Dashboard (Power BI Service)

![Screenshot (494)](https://github.com/user-attachments/assets/2cf49771-fef9-482f-a891-dec353470058)

 
 # Report Snapshot (Power BI DESKTOP)

 
![Screenshot (494)](https://github.com/user-attachments/assets/2522cee1-a7fc-49eb-b510-c6cee016a912)



![Screenshot (495)](https://github.com/user-attachments/assets/7ca7fd82-6d54-4037-9be9-caf2525b7843)


![Screenshot (496)](https://github.com/user-attachments/assets/8ff6299b-8edb-4538-939c-ce5254add76e)

![Screenshot (497)](https://github.com/user-attachments/assets/f167b9e6-c121-41f7-ad59-748282877601)


![Screenshot (498)](https://github.com/user-attachments/assets/6c9d0727-3d63-494d-919b-852c4fc6c5fa)


# Insights

A single page report was created on Power BI Desktop & it was then published to Power BI Service.

Following inferences can be drawn from the dashboard;
### Debt and Equity
    Debt: Represents 18.06% of the total capital, amounting to 8,252.
    Equity: Represents 81.94% of the total capital, amounting to 37,435.
### Cash and Other Current Assets
    Cash: Accounts for 13.51% of current assets, totaling 7,343.
    Other Current Assets: Accounts for 86.49% of current assets, totaling 47,021.
### Total Assets, Total Liabilities, and Equity
    Total Assets: Amount to 8,252, representing 4.47% of the total.
    Total Liabilities: Amount to 90,430, representing 48.99% of the total.
    Equity: Amount to 85,890, representing 46.53% of the total.
### Net Profit and Sum of Pendapatan Per Share by Company
    InfusionLabs: Highest average net profit.
    QuantumWorks: Fluctuating net profit, with a peak and a significant drop.
    TechNexus, SynapseSoft, SkyLift, NexaLabs, HyperionTech, and NeuralBridge: Lower net profit averages.
### Total Assets, Total Liabilities, Equity, and Sales by Company
    QuantumWorks: High total assets and liabilities, moderate equity and sales.
    HyperionTech: High total assets, moderate liabilities, and sales.
    VantageTech: Balanced total assets and liabilities, moderate equity.
    NeuralBridge: High liabilities, moderate assets, and equity.
    SparkMind: Moderate assets, liabilities, and equity.
    TechNexus: Balanced assets and liabilities.
    SynapseSoft: Lower assets and liabilities.
    SkyLift: Lower assets and liabilities.
    InfusionLabs: Lower assets, moderate liabilities.
    NexaLabs: Moderate assets, low liabilities, and equity.
### Average Sales by Year
    The average sales across the companies are 99.368.
