# Paris2024MedalData
This project focuses on collecting, cleaning, and analyzing the Paris 2024 Olympics medals data from a Wikipedia page. The process involves web scraping using Excel's Power Query, data transformation, and outlier handling to ensure accurate insights. The cleaned dataset is saved as a CSV for further analysis.

## Data Collection
The initial step was to implement a data extraction process from the official website. Since the official website of the Paris 2024 Olympics was unable to load quickly, I decided to import the medals table data from a Wikipedia page using the URL in MS Excel:

1. Go to the **Data** tab in the ribbon.
2. Click on **Get Data**, then select **From Other Sources**, and click on the **From Web** option.
3. After this step, a pop-up window will appear asking for a URL. Enter the URL of the medals page and click **OK**. 
4. Power Query will attempt to connect to the webpage.
5. A **Navigator** window will open, showing the tables that Excel found. Choose the table with the medals data.
6. If the table doesn't appear right away, check under "Document" or "Web View".
7. Once the right table is found, click the **Load** button.

## Data Cleaning
The second step involved cleaning the data, such as removing extra columns if necessary, fixing column headers, identifying outliers, and more. After clicking the **Transform Data** button:
- I filled the empty cells in the "Rank" column with the necessary values.
- I corrected the "NOC" column.
- I deleted the last record, as it could have interfered with the calculations.

After making the required changes, I clicked the **Load** button to load the cleaned data into my Excel sheet.

## File Saving
After the data was imported and cleaned:
1. Go to **File** -> **Save As**.
2. Choose the location where the file should be saved.
3. In the **Save as type** dropdown, select "CSV" or (*.csv).
4. Give the file a name and click the **Save** button.
