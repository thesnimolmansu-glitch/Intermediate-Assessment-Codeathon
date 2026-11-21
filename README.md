# Intermediate Assessment-Codeathon
# Logistics & Transportation-Fleet performance & Delivery Efficiency
Dataset:Logistic Dataset Link

## Overview
This project analyzes trip and delivery performance using Power BI (`Trip_Data and Vehicle_Master`), covering data cleaning,Relate Trips with Vehicle Master, DAX measures, KPI cards, and interactive visualizations.

## Workflow & Steps
1. Data Cleaning & Modeling:
 *  Reviewed and cleaned the dataset (`Delivery_Date`, `Delivery_Status`, `Origin`, `Destination`, `Distance_km`, `Fuel_Efficiency`, `Cost per km`, etc.) for reporting. *(Note: Since a dedicated delivery time column is not available in the dataset and only `Delivery_Date` is present, `On-Time Delivery%` is used as the alternate KPI for delivery performance.)*
* Related table by merging Trips with Vehicle Master using XLOOKUP & VLOOKUP
2. DAX Measures:
    Created key DAX measures including **`On-Time Delivery%`**along with core metrics like **`Fuel Efficiency`** and **`Cost per km`**.
  
3. KPI Cards:
    Built KPI cards displaying **`On-Time Delivery%` (`60.00%`)** (alternate delivery KPI), **`Cost per km` (`9.54`)**, and **`Fuel Efficiency` (`11.68`)**, with formatted titles, colors, and layout alignment.
4.Visualizations:
   * **Bar Chart:** Delivery performance (`On-Time Delivery%`) breakdown.
   * **Line Chart:** Trend analysis (such as `Fuel Efficiency` trend).
   * **Map Visual:** Route/location view (`Origin` and delivery status).

>> Tools Used
* Excel(Power Query)
* Microsoft Power BI Desktop
* DAX (Data Analysis Expressions)
