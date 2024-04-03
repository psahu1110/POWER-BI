## Day 1



### Steps Taken:


   - Loaded sample sales data provided by Power BI.


   - Utilized a basic chart to analyze sales of products based on the discount bands given.
   


   - Explored sales data on a geographical map to visualize sales by country.


   - Employed a funnel chart to analyze sales by segment.


   - Created a horizontal bar chart to examine profit trends by year and discount band.





### Snapshot of Dashboard

![DAY 1](https://github.com/psahu1110/POWER-BI/assets/114385902/0dbf1b79-e5b9-4aa5-9b94-132c259182c8.jpg)


## DAY 2
### Analyzing World Happiness Report 2020 with Power BI


### Steps Taken:

### 1. Loading the Dataset:
- Utilized Power BI's "Get Data from Web" option to load the World Happiness Report 2020 dataset.
- Spent time understanding the dataset and its variables.

### 2. Visual 1: GDP per Capita across Countries
- Utilized drag-and-drop feature to plot GDP per capita against countries.
- Adjusted bubble sizes for better visual representation.

### 3. Visual 2: Relationship between Freedom to make life choices and Healthy Life Expectancy
- Used a scatter plot to analyze the relationship between freedom to make life choices and healthy life expectancy.
- Initially, only one point was displayed due to summarization. Resolved by adding the country column to the values field.

### 4. Visual 3: Relationship between GDP per Capita and Perceptions of Corruption
- Employed another scatter plot to investigate the relationship between GDP per capita and perception of corruption.
- Disabled summarization under x and y-axis fields.

### 5. Visual 4: Clustering GDP per Capita and Generosity
- Utilized a scatter plot with GDP per capita on the x-axis and generosity on the y-axis.
- Applied the "automatically find clusters" option to automate the clustering process.
- Performed color formatting and brushing for enhanced visualization.

### Snapshot of Dashboard 

![DAY 2](https://github.com/psahu1110/POWER-BI/assets/114385902/1e431430-794e-4ed7-ba7a-8f09a6af228f)


## DAY 3

### Explored different Bar Charts:
### Stacked Bar Chart:
- **Objective**: Understand sales distribution across different discount bands.
- **Steps**:
    1. Dragged and dropped the "Sales" column onto the X-axis.
    2. Placed the "Discount Band" column on the Y-axis.
    3. To enhance visualization, utilized the "Year" column as the legend field for color-coded representation of sales across years.
    4. Utilized small multiples to compare sales for each product, employing color formatting and data labels for clarity.

### Clustered Bar Chart:
- **Objective**: Compare profit across different segments.
- **Steps**:
    1. Duplicated the previous bar chart visualization.
    2. Modified the chart type to a clustered bar chart.
    3. Dragged and dropped the "Profit" column onto the Y-axis.
    4. Placed the "Segment" column on the X-axis.
    5. Applied necessary formatting for enhanced readability.

### Snapshot of Dashboard 

![DAY 3 (1)](https://github.com/psahu1110/POWER-BI/assets/114385902/7902be93-8c67-4fde-9e93-dbf91c47d58c)


## Day 4

### Clustered Column Chart: Profit Analysis Across Countries
- **Objective**: Understand profit distribution across different countries.
- **Steps**:
    1. Utilized a clustered column chart.
    2. Dragged and dropped the relevant columns onto the X and Y axes.
    3. Applied conditional formatting to analyze profit based on discounts from minimum to maximum among countries.
    4. Utilized features of the magnifying glass visual option for further analysis, such as average line, series, line, and data labels.

### Slicers: Controlling Visualization Based on Product and Segment
- **Objective**: Control visualizations based on specific product and segment criteria.
- **Steps**:
    1. Used slicers to interactively filter data.
    2. For the first slicer, added the "Product" column to the field section and configured it to single select mode using slicer settings.
    3. Added the "Segment" column to the field section for the second slicer, applied horizontal orientation, and enabled the "show select all" option for better visual presentation.
    4. For the third slicer, added the "Units Sold" column to the field section.

### Snapshot of Dashboard

![DAY 3 (2)](https://github.com/psahu1110/POWER-BI/assets/114385902/6082e233-927c-495c-bbf7-486034d9a1da)


## DAY 5


### Line Chart Analysis

For the first visual, the yearly sales were explored using a line chart. The date and sales columns were dragged and dropped onto the x and y axes. Due to the date format, a hierarchy was automatically created. The drill option created by the hierarchy was utilized to delve into the data, providing insights into the usage and functionality of hierarchies.

### Pie Chart Analysis

In the second visual, a pie chart was utilized to analyze yearly profit. The year, country, segment, product, and discount band were placed in the legend field, while profit was used for values. This visualization offered a clear understanding of profit distribution across different categories.

### Treemap and Cards Analysis

For the third visual, a treemap was employed to visualize sales data by year. A hierarchy named 'ba' was manually created for this purpose, enabling easy drag-and-drop functionality without the need to create hierarchies repeatedly. The 'ba' hierarchy was used for categories, while sales were represented by values. Additionally, two cards were created to display sales and profit numbers for quick access and clear understanding.

### Snapshot of Dashboard

![DAY 4](https://github.com/psahu1110/POWER-BI/assets/114385902/c46d23ee-2d3a-443b-86db-6912167d1bdc)

## DAY 6 

- For day 6 explored the concept of Power Query In Power Bi
- Loaded the dataset named sales(Excel file), Customer(csv File), Segment(excel file) using get data in Data section under home tab.
- After loading all the 3 datasets, some data cleaning was performed in the power query editor.
- For the Sales dataset removed the column named "Source. Name" as it was of no use for analysis and it was observed that a column named "model_color" had some null values so it was replaced with "Others" using "replace values" in "any column" section under transform tab in the power query editor.
- For the Customer dataset, the first row was promoted as a header using "use the first row as header" in the table section under the transform tab in the power query editor.
- For the Segment dataset promoted the first row as a header using the same method as earlier mentioned then removed blank rows using "remove rows" in "reduce rows" under the home tab and last but not least filtered null rows from the column named "segmt_category" by the unselecting null box from the dropdown.
- After cleaning the datasets use the close and apply option in the close section under the home tab.
- In the model view, the relationship was created between all 3 datasets.
- A Donut Chart was added to the canvas representing the sum of gross sales amount. While creating this visual column cust seg was added to legends to segregate according to the cust segments. A card visual was also added in the middle of the donut chart representing gross sales amount and also did some formatting under the brush section.
- The same donut chart was copy-pasted to canvas representing the sum of the order quantity and a legend was also added representing the buzz segment and a card visual was added representing the sum of the order quantity.

### Snapshot of dashboard

![DAY 5](https://github.com/psahu1110/POWER-BI/assets/114385902/5b85ea76-8d5b-40ad-a386-2c79b70b35f2)

## DAY 7

- Loaded the dataset named Revenue sharing(excel file) using the Excel workbook option in the Data section under the home tab.
- In power query performed some data cleaning actions like splitting the team analyst column into rows using advanced options in split columns under the transform tab.[Transform-split column-split by delimiter-advanced options-select rows-then click ok.]
- Then cleaned and trimmed the test using the format option in the text column section under the transform tab in power query.
- Using reference table to project details made a bridge table named project info.[The bridge table is a copy of the original table with genuine information]
- In the Bridge table named project info grouped the team analysts column using group by function in the table section under the home tab in power query.
 
![group by](https://github.com/psahu1110/POWER-BI/assets/114385902/775d3bcd-7a66-4d40-ad12-3d1e7f3b8922)
- Then make a new column name contribution by selecting the project fee column and then the no of employee column using the divide function in the statistics option under the transform tab.
- Now the dataset is cleaned choose the close and apply option under the home tab.
- Now for visualization, we used bar chart, funnel chart, and tree map. 

![DAY 6](https://github.com/psahu1110/POWER-BI/assets/114385902/68147405-4d35-4686-b257-3a40a2182638)


















