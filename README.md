# Marketing Spend Optimization for Showz

## Project Overview

This project is part of an exercise completed during a Data Analyst bootcamp, where the goal is to optimize the marketing spend for **Showz**, a ticket sales company. Using server logs, order data, and marketing spend statistics from January 2017 to December 2018, I analyzed user behavior and provided recommendations on how to allocate marketing investments efficiently.

### Key Objectives:
1. Analyze how users interact with the platform and determine conversion patterns.
2. Investigate when customers start purchasing and how much revenue each customer generates over time.
3. Evaluate marketing spend across different sources and calculate the return on marketing investment (ROMI).

## Data Sources

- **Visits data** (`visits_log_us.csv`): Server logs detailing user sessions, devices, and sources of traffic.
- **Order data** (`orders_log_us.csv`): Information on user purchases, including revenue and purchase timestamps.
- **Marketing spend data** (`costs_us.csv`): Marketing spend by source and day.

## Analysis

### 1. User Behavior & Sales Funnel:
- **Daily/Weekly/Monthly Active Users**: Track how many users engage with the platform over time.
- **Session Frequency & Duration**: Understand how often users return and how long they stay.
- **Time to Purchase (Conversion Time)**: Analyze how quickly users convert into customers after registering.

### 2. Sales Metrics:
- **Order Volume & Average Purchase Size**: Measure the total orders placed and the average revenue per order.
- **Lifetime Value (LTV)**: Calculate the total revenue each user generates over time.

### 3. Marketing Performance:
- **Customer Acquisition Cost (CAC)**: Calculate how much was spent to acquire each customer from different marketing sources.
- **Return on Marketing Investment (ROMI)**: Evaluate the profitability of marketing efforts across channels.

## Recommendations

Based on the analysis, I provide recommendations on which marketing sources or platforms to prioritize based on key metrics like customer acquisition cost and ROMI.

## Project Structure

- **`notebooks/`**: Contains Jupyter Notebooks with the detailed analysis and visualizations.
- **`datasets/`**: Includes the datasets used in the analysis (if sharing is allowed).
- **`README.md`**: This document.
- **`environment.yml`**: File with the dependencies to reproduce the analysis environment.

## How to Use

To run this project locally:

1. Clone the repository:
   ```bash
   git clone https://github.com/704k0-dev/web_events_showz.git
   ```

2. Set up the environment:
   ```bash
   conda env create -f environment.yml
   conda activate showz_analysis
   ```

3. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.