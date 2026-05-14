# Convenience Store Inventory & Demand Analysis

## Project Overview
This project analyzes inventory data for a convenience store, focusing on sales velocity, profitability, and stock management recommendations. The analysis covers 157 products over 12 days of operation, identifying opportunities to optimize inventory and reduce dormant capital.

## Technologies Used
- **Python**: Core programming language
- **Pandas**: Data manipulation and analysis
- **NumPy**: Numerical computations
- **Jupyter Notebook**: Interactive development environment
- **VS Code**: Development environment
- **Real operational data**: Manually collected and structured inventory snapshots

## Key Achievements
- **Inventory Structuring**: Manually collected and structured inventory data for 157 products across 12 days, including stock snapshots, purchases, and outflows.
- **Sales Velocity Calculation**: Computed daily sales velocity per product and identified 67 items with zero movement during the period, quantifying opportunity cost.
- **Stock Recommendation System**: Built a minimum stock recommendation system with reorder alerts based on the store's 3-day purchasing cycle.
- **Product Ranking**: Generated a top-15 product ranking by category and recommended discontinuing low-turnover lines (chocolates and decorative items) to free up capital for faster-moving products.
- **Field Validation**: Purchase predictions presented to the owner were validated in practice — all flagged critical items (candles, Sol snacks) were restocked as recommended before the next supply run.

## Files Description
- `convenience_store.ipynb`: Main analysis notebook
- `inventory.csv`: Processed inventory data
- `categories.txt`: Product categories
- `final_data_frames/`: Output dataframes (snapshots, rankings, etc.)
- `data_*.md`: Raw data files

## Usage
1. Open `convenience_store.ipynb` in Jupyter Notebook or VS Code.
2. Run the cells sequentially to reproduce the analysis.
3. Review the visualizations and recommendations in the final section.

## Insights
- Total profit over 12 days: Calculated dynamically in the notebook
- Dormant capital identified: Value of unsold inventory
- Recommendations for inventory optimization and product discontinuation

This analysis provides actionable insights for small business inventory management, demonstrating data-driven decision-making in retail operations.