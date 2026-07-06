# Coffee Shop Sales
## used tools
- power bi
- sql

# Power BI
- Heat Map for per day in month using heat map
    - used tooltip for per day distribution 
- Graphs like spark line chart for trends over sale
    - used mathematical functions like selectedvalue format for year month and days to classify the weekend and weekdays and for chart according to it, averagex for days in month
    - like totalmtd, used symbols according to trend if its increasing or decreasing if yes by how much
- month average bar chart
- donut chart for weekdays and weekend sales
- sales by store location
- sales by product cateogry
- sales by product type top 10
- sales by days and hours 
    - used tooltip for per day and hour 
- Slicer for Month and for days in month

### the dashboard contains 
- KPI required
    - total sales analysis
    - total order analysis
    - total quantity sold analysis
- Charts Requirement
- calendar heat map that dynamically adjusts based on the selected month from a slicer
    - color represent the sales darker the shade higher the sales
- Sales analysis by weekdays and weekend
- sales analysis by store location
    - included month over mont(mom) difference metrics based on selected month
- daily sales analysis with average line
    - displayed daily sales for selected month using line chart
    - incorporated an average line on chart to represent the avg daily sales
    - highlighted bars that exceed the avg sales
- sales analysis by product category
    - provided insight about the product categories contribution
- top 10 products 
    - displayed 10 top products based on sales volume
- sales analysis by days and hour
    - used heat map and tooltip to display the metrics of sales, orders and quanity while hovering over them.

## SQL
- used to prove that the insights used in power bi are valid
- optimized query for all graphs
- used to clean the data(into date type, removal of null values) and transform it
