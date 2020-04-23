# Monarch Migration Tagging and Reporting
*Data Analysis and Visualization*

#### Arink Bertrand

In this project, I gathered Monarch Tagging and Reporting data from MonarchWatch.org for 1994-2001. My goal is to get insight on how many Monarch butterflies are tagged compared to those reported, travel patterns and compare to news articles as to why report numbers dropped. I plan to use plotly and Power BI for visualization.

### Steps to Accomplish:

- [x] Create ReadMe file to explain plan 
- [x] Import all necessary packages
- [x] Use tabula.app to convert pdf data to csv
- [x] Database cleanup & export to csv for each year individually
- [x] Create Monarch Migration database
- [x] Use SQL and pandas to aggregate data
- [x] Visualize travel and numbers using plotly and Power BI
- [x] Update ReadMe to futher explain varifications, language etc.

### Dependencies

- SQLite3
- Pandas
- Plotly
- Microsoft Power BI

### Sources & Contacts
<a href="https://monarchwatch.org/read/seasum.htm"> Monarch Watch </a>

Jim Lovett <jlovett@ku.edu> Originator, Research Assistant - Monarch Watch, University of Kansas 

Photos are my own and property of <a href= "https://www.doctordewitt.com/">Robert H. DeWitt, D.D.S., P.C.</a>

### Instructions for:
- <a href="https://tabula.technology/">Tabula</a>

    - Follow download instructions
    - Launch app (new window/tab will open in browser)
    - Import PDF you are trying to extract table out of
    - Choose <i>Autodetect Tables</i>, or you can manual create a box around your tables (autodetected tables can be adjusted)
    - Select <i>Preview & Export Extracted Data</i>
    - Review your table format, choose export format and click <i>Export</i>.

- <a href="https://www.microsoft.com/en-us/download/details.aspx?id=58494">Power BI Desktop</a>
    - Follow download instructions
    - Launch app 
    - You do not need to log in or have an account. Account is needed if you wanted to save to 
    cloud and publish dashboards.
    - Select <i>Get data</i> to import CSV/excel etc (pkl does not work) & <i>Load</i>
    - If any adjustments need to be made to data (creating new columns, finding sums, etc.) click <i>Transform Data</i> to open Power         Query Editor
    - When all adjustments are made select <i>Close & Apply </i>
    - With the <i> Report </i> tab selected (looks like bar graph) you can choose your visualization (on right)
    - Under "Fields" are your columns from your csv, drag and drop into visualization box to view.
    - You can change the settings and colors of the visualization by clicking the paint roller
        - Visualization I used:
            - Filled map (preinstalled)
            - <a href="https://appsource.microsoft.com/en-us/product/power-bi-visuals/WA104380901?tab=Overview"> Flowmap(Downloaded)</a>

- Some Educational Sources:
   - <a href = "https://www.youtube.com/watch?v=xR8tplcUb1w"> Pragmatic Works</a> has a great video on how to use the Flow Map visual
   - I learned the basics of Power BI from Rebecca Hollenbach of Kentuckiana Works on Open Data Day 2020, click <a href="https://docs.google.com/presentation/d/1TQMmUkbfbpTw6SdoJ_QMTTGmMAsZBEkjmQDPqx3K3J0/edit?usp=sharing">here</a> to access her slides from her presentation.

