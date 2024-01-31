# Mexician Toy Sales 

### Dashboard Link https://app.powerbi.com/groups/me/reports/0598ecad-27dd-49ca-aa06-764584bdea58?ctid=c161f32a-a16f-41cd-8e7b-2054e98f9838&pbi_source=linkShare

## Problem Statement

This dashboard helps the stakesholder Knowing how many toy stores there are in Mexico and knowing how many toy stores have the most sales. It helps the stakesholder know if their customers find out what toy products customers buy that sell the most. Through different location, they get to know their improvement area, & thus they can improve their can improve by identifying these area. It also lets them know Sales By Area, thus since by using this dashboard they have identified this problem.

This dashboard also shows a few financial conditions such as Total Unit Sales, Total Gross Profit Margin and Total Profit so that stakeholders can make policies.


### Preview  


![Report Snapshot in Power BI desktop png](https://github.com/V3n0mm0us/Mexician-Toys-Sales-/assets/81215981/dd24c45c-cd0f-497d-bcf9-a6ebb2fa0701)


        
- That Preview on Dashboard

![Gros Profit Mrgin](https://github.com/V3n0mm0us/Mexician-Toys-Sales-/assets/81215981/2dc7dd88-27ad-44a9-b472-190ca7a80c3a)


        
 - On Gross Profit 
 
 Following DAX expression was written to Gross Profit Margin,
 
        GPM = DIVIDE(SUMX(Sales, Sales[Revenue]), SUMX(Sales, RELATED(products[Profit]))) * 100
 
 A card visual was used to represent.
 
 ![Toral Unit Sales](https://github.com/V3n0mm0us/Mexician-Toys-Sales-/assets/81215981/0b8b5066-de5f-4971-9aeb-f9e75918cd5f)

 Following DAX expression was written to find total distance,
 
        TotalQuantity = SUM(Sales[Unit])
    
 - The report was then published to Power BI Service.
 
 
![Publish To Power BI PNG](https://github.com/V3n0mm0us/Mexician-Toys-Sales-/assets/81215981/0d1ffea1-0129-4a83-bdb7-dbe5172424a8)

# Snapshot of Dashboard (Power BI Service)

![Snapshoot Power BI app](https://github.com/V3n0mm0us/Mexician-Toys-Sales-/assets/81215981/d7d1f6b5-de23-4466-957d-61858146dc95)
