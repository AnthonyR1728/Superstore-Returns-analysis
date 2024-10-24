# Storytelling with Data: Superstore Returns Analysis

## Project Overview
This project focuses on analyzing the root causes of high return rates at Superstore. The goal is to prepare a data-driven analysis and visual presentation for the CEO to help identify factors contributing to returned orders and provide insights on how to reduce the volume of returns. The analysis is conducted using Tableau, and the story is presented through interactive visualizations and dashboards.

## Dataset

  - The project uses the Superstore.xls dataset, which includes information on orders, returns, and customers. This dataset is crucial for exploring sales patterns, customer behavior, and return rates.

## Key Data Tables:

  - Orders: Contains order details including product information, sales, and profits.
  - Returns: Information on whether an order has been returned (joined with the Orders table).

    - By LEFT JOINING the Returns table to the Orders table, we create a calculated field that categorizes returned orders (Yes = 1, No = 0) and calculate return rates.

## Project Breakdown

 ##  1. Identifying the Causes of Returns
  - In this section, we explore different views and analyze the root causes of returns.

 Visualizations Created:

  1. Scatter Plot:

  - Total Sales vs. Total Returns: This scatter plot helps us investigate if high sales correlate with high return rates. We aggregate by product subcategory to see if increased sales consistently lead to more returns.

  2. Bar Chart:

  - Return Rate by Product Category: This chart visualizes which product categories have the highest return rates.

  3. Return Rate by Customer:

  - This chart identifies customers who frequently return items. A filter is applied to remove customers with only one order to focus on repeat returners.

  4. Map Visualization:

  - Return Rate by Geography: This map helps analyze geographic concentrations of returns by state or city.

  5. Return Rate by Time:

  - This visualization looks at the return rate by month or week to determine if there is a seasonal effect.

  6. Composite Charts:

  - Two composite charts were created, showing return rates across multiple factors such as date, geography, and product category, providing a deeper insight into patterns and trends.

## 2. Dashboard Creation: Monitoring Returns

  - In this phase, we designed a dashboard to showcase the return analysis findings. The dashboard is a tool for the CEO to monitor returns and drill down into root causes.

## Steps:

Low-Fidelity Mockups:

  - Created three pen-and-paper sketches of potential dashboard layouts. These mockups help conceptualize the design of the final Tableau dashboard.

Dashboard Template:

  - A template was created using empty containers to match the mockup’s layout. A screenshot of this template is included.

Finalized Dashboard:

- The final dashboard includes all relevant worksheets, along with markers, images, and titles to ensure clarity. It highlights return rates by product, customer, and geography, allowing for an intuitive exploration of the data.


## 3. Presenting the Analysis and Dashboard

- In this final section, we create a Tableau Story to present the analysis and dashboard findings effectively.

Steps:

1. Draft Story:
 
  - A caption-only draft of the story is created, summarizing the analysis and key insights. It covers:
    - How returns are measured (return rate vs. total cost vs. total number of returns).
    - The key root causes of returns.
    - A summary of each component in the dashboard and how to interpret the charts.
    - A demonstration of how to use the dashboard to filter data and identify root causes.
    - Proposed actions based on the insights.

2. Story Points:

  - Worksheets from the analysis are used to create story points in Tableau. New worksheets may be created to support the story arc. These are then compiled into a presentation format using Tableau’s dashboard story feature.

3. Presentation:

  - A 3 to 5-minute presentation is prepared, either as a screen recording or a PDF of the Tableau Story. This presentation explains the analysis, demonstrates the dashboard, and suggests next steps for the CEO to reduce return rates.


Superstore Returns Dashboard (Tableau Public link) : 


## Project Files

- Superstore Returns Tableau Workbook (.twbx)
- Mockups and Templates: Images of the initial sketches and the dashboard template.
- Final Dashboard: A Tableau dashboard that compiles all relevant analyses.
- Story Points: A Tableau Story that summarizes the return analysis and provides actionable insights.
- Presentation: Either a screen recording or PDF version of the Tableau Story presentation.