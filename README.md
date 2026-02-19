Interactive Auto Sales Data Visualization
Project Overview
The goal of this project is to go beyond static charts and build an interactive visual experience for sales data. Using a global auto sales dataset, I developed a series of dashboards that allow users to explore revenue trends, product popularity, and geographic performance dynamically.

Visualizations & Dashboards
Interactive Revenue Tracking: Used Plotly Express to create dynamic charts that show sales performance over time, allowing for hover-over details and zooming.

Product Line Distribution: Created high-quality interactive pie and sunburst charts to visualize which categories (Classic Cars, Motorcycles, etc.) dominate the market share.

Statistical Relationship Mapping: Implemented Seaborn regression plots and heatmaps to visualize the correlation between MSRP (Manufacturer's Suggested Retail Price) and actual sales price.

Geospatial Insights: Visualized sales density across different countries to identify key regional hubs.

Tech Stack
Plotly & Plotly Express: For building the interactive "web-style" charts.

Seaborn: For professional-grade statistical visualizations and color palettes.

Matplotlib: For custom plot styling and layouts.

Pandas: For advanced data grouping and aggregation.

Key Discoveries
Seasonal Trends: The visualizations clearly highlight a significant surge in deal closures during the end-of-year months.

Price vs. Quantity: Through scatter plots, I identified that while quantity ordered remains steady, revenue is most heavily influenced by the Product Line category rather than volume alone.

Market Leaders: The USA and EMEA regions show the highest engagement with high-MSRP items.

How to View
Open data_visualization_project.ipynb in this repository.

Click the "Open in Colab" badge.

Because this project uses Plotly, the charts are interactive! You can hover over bars, click legend items to filter data, and export specific views as images.
