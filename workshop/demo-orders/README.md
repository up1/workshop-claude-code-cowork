# Demo with Claude Cowork

## 1. E-commerce Orders Analysis

### Case 1: Spike in Electronics Cancellations
Case: The e-commerce operations lead has noticed a spike in order cancellations for electronics products in June 2026. They want to analyze the cancellation trends using a Python script on the local CSV file `projects/ecommerce_analysis/orders_june2026.csv` and draft a risk mitigation plan based on the findings.
```
Read my @context.md and check @todo.md for task_101. 
Run a Python script analyzing the cancellation trend in @projects/ecommerce_analysis/orders_june2026.csv 
and draft a brief risk mitigation plan matching my requested output tone
and generate graphs to visualize the cancellation trends
```

### Case 2: Gross Revenue vs. Net Revenue by Category
* Generate a visual chart comparing Gross Revenue vs. Net Revenue by Category using the sales data from `projects/ecommerce_analysis/orders_june2026.csv`.
```
Access my context.md and the sales data file located at projects/ecommerce_analysis/orders_june2026.csv. Write and execute a Python script using matplotlib or seaborn to generate a clean visual chart. The chart must display Gross Revenue vs. Net Revenue by Category side-by-side.Set the color palette to match a professional corporate theme (e.g., dark blue and slate gray). 

Save the chart as a high-resolution PNG image named sales_trend.png inside the projects/ecommerce_analysis/ folder. Once saved, update todo.md by checking off task_101 and output a brief note confirming the file path where the chart was created and the insights derived from the Gross Revenue vs. Net Revenue trends for each category
```

* Gernerate report in html format and visualization on the top 5 SKUs by sales volume and their contribution to overall revenue.
```
Using the same sales data, write a Python script to identify the top 5 SKUs by sales volume. 
Create a structured HTML report that lists these SKUs along with their sales volume and revenue contribution.
Create a bar chart that shows each of these SKUs and their contribution to overall revenue. Save this chart as top_skus.png in the same directory. Update todo.md to reflect the completion of this task and include a brief analysis of how these top SKUs are performing in terms of revenue contribution
```

### Case 3: Supplier Agreement Revision for Beauty SKUs
Case: The operations lead needs to draft a revised supplier agreement for high-margin Beauty SKUs. They want to ensure the new agreement includes stricter delivery timelines and penalties for late shipments to improve inventory management and sales performance.
```
Read my @context.md and check @todo.md for task_102.
Draft a revised supplier agreement for high-margin Beauty SKUs that includes stricter delivery timelines and penalties for late shipments, ensuring it aligns with my strategic goals and operating principles.
and generate graphs to visualize the current delivery performance of Beauty SKUs to support the need for stricter timelines and penalties
``` 