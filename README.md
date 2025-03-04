# Cinépolis Sales & Attendance Dashboard

## Description
A Power BI dashboard analyzing sales and attendance at Cinépolis theaters in Saltillo during March 2025. It includes interactive visualizations on ticket sales, concession purchases, and customer behavior. All data was generated using AI based on statistical models.

## Features
1) **Total Sales by Day**
   - A line chart displaying daily total sales in March 2025, with slicers for theater type and location.
   - Clicking on a specific day redirects to a pie chart showing the hierarchy of sales by theater and room type, including the percentage and total tickets sold.

2) **Stacked Column Chart - Ticket & Concession Sales**
   - Shows ticket and concession sales per day, with the same slicers as the line chart.
   - Clicking on a specific day redirects to the pie chart for detailed breakdowns.

3) **Concessions Analysis**
   - A KPI card showing the percentage of total cinema revenue contributed by concession sales.
   - A word cloud displaying the most purchased products.
   - A KPI chart tracking the monthly sales target for concessions.
   - A gauge chart visualizing the target vs. actual sales for March 2025.

4) **Demographics & Membership Insights**
   - A grouped column chart showing ticket purchases by gender, categorized in 5-year age bins starting from 15 years old.
   - A ring chart illustrating the distribution of ticket sales by gender.
   - Three KPI cards displaying the number of "Super Fans," "Fans," and "Movie Enthusiasts" based on the Cinépolis membership system.

5) **Sales Performance Matrix**
   - A matrix displaying:
     - Ticket sales per day.
     - Concession sales per day.
     - Cumulative ticket sales.
     - Cumulative concession sales.
     - Total sales per day.
     - Percentage contribution of each day to the total monthly sales.

## Getting Started

### Prerequisites

Ensure you have the following installed:
- Power BI Desktop
- Access to the provided datasets:
  - `customers.csv` (Customer demographics and membership details)
  - `concession_sales.csv` (Concession purchase data)
  - `ticket_sales.csv` (Daily ticket sales data)

### Installation

1. Clone this repository or download the files.
2. Open Power BI Desktop and load the datasets.
3. Import the Power BI dashboard template included in the repository.

### Usage

### Running the Dashboard
1. Open the Power BI dashboard file.
2. Navigate through different pages using interactive buttons.
3. Use filters and slicers to explore specific insights.


## Example

### Line Chart
Visualize the total ticket sales in March, this chart can be filtered by Cinema and Movie Theater Type.

### Stacked Bar Chart
Explore the total ticket and concession sales in March, this chart can be filtered by Cinema and Movie Theater Type.

### KPI
Identify the percentage of total cinema revenue contributed by concession sales.

### Word Cloud
Identify the most popular purchased products.

### KPI Gage
View the target vs. actual sales for March 2025.

### Grouped Column Chart
Explore the total ticket purchases by gender, categorized in 5-year age bins starting from 15 years old.

### Ring Chart
Examine the distribution of ticket sales by gender.

### KPI Cards
Identify the number of "Super Fans," "Fans," and "Movie Enthusiasts" based on the Cinépolis membership system.

### Matrix
Analyze daily performance and the contribution of each individual day to the overall monthly revenue, making this matrix an essential tool for performance analysis.

### Detail Page
View a detailed pie chart displaying the distribution of tickets sold by cinema and type of room based on the selected day in the general sales or concession sales page.

## Data Sources
The following CSV files were used:
- **customers.csv** (Customer demographics and membership details)
- **concession_sales.csv** (Concession purchase data)
- **ticket_sales.csv** (Daily ticket sales data)

## Contributing
Contributions are welcome! Feel free to open an issue or submit a pull request with suggestions or improvements.

## License
This project is licensed under the MIT License.

## Acknowledgments
Thank you for exploring the Cinépolis Sales & Attendance Dashboard!
