
## Power BI Assignment 5

#### 1. Explain DAX.

Data Analysis Expressions (DAX) is a formula expression language used in Analysis Services, Power BI, and Power Pivot in Excel. DAX formulas include functions, operators, and values to perform advanced calculations and queries on data in related tables and columns in tabular data models.

This article provides only a basic introduction to the most important concepts in DAX. It describes DAX as it applies to all the products that use it. Some functionality may not apply to certain products or use cases. Refer to your product's documentation describing its particular implementation of DAX.

#### 2. Explain datasets, reports, and dashboards and how they relate to each other?

A data set is a collection of related, discrete items of related data that may be accessed individually or in combination or managed as a whole entity.
A data set is organized into some type of data structure. In a database, for example, a data set might contain a collection of business data (names, salaries, contact information, sales figures, and so forth).

A report is a specific form of writing that is organised around concisely identifying and examining issues, events, or findings that have happened in a physical sense, such as events that have occurred within an organisation, or findings from a research investigation.

A dashboard is a visual display of all of your data. While it can be used in all kinds of different ways, its primary intention is to provide information at-a-glance, such as KPIs. A dashboard usually sits on its own page and receives information from a linked database.


The Related content pane shows you how your Power BI service content -- dashboards, reports, and datasets -- are interconnected. Reports are built on datasets, report visuals are pinned to dashboards, and dashboard visuals link back to reports.

#### 3. How reports can be created in power BI, explain two ways with Navigation of each.
Four quick steps to get you started.  
Step 1: Install Power BI Desktop for Power BI Report Server.  
Step 2: Select a data source.   
Step 3: Design your report.   
Step 4: Save your report to the report server.  

#### 4. How to connect to data in Power BI? How to use the content pack to connect to google analytics? Mention the steps.
With Power BI Desktop, you can easily connect to the ever expanding world of data.




![App Screenshot](https://learn.microsoft.com/en-us/power-bi/connect-data/media/desktop-connect-to-data/get-data-from-web.png)


Connecting Power BI with Google Analytics    

1. In the left navigation pane, click Get Data.
![App Screenshot](https://powerbicdn.azureedge.net/mediahandler/blog/legacymedia/6758.Left-Nav_5F00_Get-Data.png_2D00_200x0.png)


2. In the Services box, click Get.
![App Screenshot](https://powerbicdn.azureedge.net/mediahandler/blog/legacymedia/0624.Services-_2D00_-Get.png_2D00_125x0.png)

3. From the menu of online services, select Google Analytics, and then click Connect.
![App Screenshot](https://powerbicdn.azureedge.net/mediahandler/blog/legacymedia/8156.Google-Analytics-_2D00_-Connect.png_2D00_550x0.png)


4. Enter the Google Analytics account, property, and view that you want to connect to. Then sign in with your Google Analytics credentials.

![App Screenshot](https://powerbicdn.azureedge.net/mediahandler/blog/legacymedia/6253.Connect-to-Google-Analytics.png_2D00_550x0.png)

5. To permit Power BI to connect to Google Analytics, click Accept.
![App Screenshot](https://powerbicdn.azureedge.net/mediahandler/blog/legacymedia/5700.Permit-Power-BI-to-Connect-to-GA.PNG_2D00_550x0.png)

6. When the import process completes, you will see a new dashboard, report, and model in the Navigation Pane. Select the dashboard to view your imported data.
![App Screenshot](https://powerbicdn.azureedge.net/mediahandler/blog/legacymedia/0624.Services-_2D00_-Get.png_2D00_125x0.png)

![App Screenshot](https://powerbicdn.azureedge.net/mediahandler/blog/legacymedia/2630.GA-Dashboard-Post_2D00_Import-View.png_2D00_550x0.png)
### 5. How to import Local files in Power BI? Mention the Steps.
Simply select Local File from the previous menu, then navigate to where you have your Excel workbooks saved.

![App Screenshot](https://learn.microsoft.com/en-us/power-bi/connect-data/media/service-excel-workbook-files/excel_import_6.png)
### 6. In Power BI visualization, what are Reading View and Editing view?
There are two modes for interacting with reports in the Power BI service:   
Editing view  
Reading view.

Reading View : Reading view to consume reports created by others. Editing view is used by report designers, who create the reports and share them with you. Reading view is your way to explore and interact with reports created by colleagues.

Editing View : Editing mode is generally used by Report designers or Analysts who collect data and create reports. Only they can add or delete tiles or visualizations from the reports. A much of modification priviledge is granted in this view.