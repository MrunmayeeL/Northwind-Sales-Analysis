# Northwind Sales Analysis

A data analysis project using the Northwind Traders database to extract business insights related to customer behavior, employee performance, and product sales. This project leverages PostgreSQL for querying and Python (pandas, matplotlib) for visualization, with a focus on applying real-world data exploration techniques.

---

## Tools Used

- PostgreSQL and pgAdmin for database setup and SQL queries  
- Python (pandas, matplotlib, seaborn) for analysis and visualization  
- Jupyter Notebook for interactive exploration  
- SQL: joins, groupings, aggregates, and foreign key constraints

---

## Project Structure

northwind-sales-analysis/

── data/ # CSV files used for populating database

── sql/

   ─ create_tables.sql # Table creation script 
    
   ─ alter_constraints.sql # Constraints (foreign keys etc.) 
    
   ─ analysis_queries.sql # All business analysis SQL queries
    
── notebooks/

   ── northwind_analysis.ipynb # Python + SQL analysis notebook
    
── visuals/ # Exported charts and figures

── README.md

── requirements.txt # Python dependencies

---

## Customer Analysis

- **Top Customers by Revenue**  
  Identifies customers who contributed the highest total sales.
  <img width="1912" height="942" alt="image" src="https://github.com/user-attachments/assets/a5d4a50c-00a7-479a-8806-a2786f403e43" />


- **Revenue by Country**  
  Aggregates total revenue per country to highlight key regions.
  <img width="1246" height="885" alt="image" src="https://github.com/user-attachments/assets/b64fd24f-8c55-4316-894a-d119f35c7dc5" />


- **Number of Orders per Customer**  
  Evaluates order frequency by customer to identify purchase behavior.
  <img width="1748" height="747" alt="image" src="https://github.com/user-attachments/assets/ea0514d1-21a8-40f7-b983-0a9f1be54742" />


- **Average Order Value per Customer**  
  Computes average order value per customer for sales efficiency.
  <img width="1743" height="757" alt="image" src="https://github.com/user-attachments/assets/667d5877-e188-4546-95f6-f66b4e562690" />


---

## Employee Analysis

- **Orders Handled per Employee**  
  Ranks employees based on the number of orders managed.

- **Revenue Generated per Employee**  
  Sums total sales associated with each employee.

- **Customers per Employee**  
  Tracks unique customers handled by each employee.

- **Employee Location Distribution**  
  Summarizes employees by region or city.

---

## Product Analysis

- **Top 10 Products by Revenue**  
  Highlights best-selling products by total revenue.

- **Revenue by Product Category**  
  Analyzes category-level sales performance.

- **Average Unit Price per Category**  
  Compares average pricing trends within each product category.

- **Product Stock vs. Sales**  
  Visual comparison of inventory levels and units sold.

---

## How to Run

1. **Install PostgreSQL and pgAdmin**  
   Set up a new database and connect via pgAdmin.

2. **Create Tables and Load Data**  
   Run `create_tables.sql`, then import CSVs via pgAdmin or use `\copy`.

3. **Apply Constraints**  
   Execute `alter_constraints.sql` to add foreign key and relational integrity rules.

4. **Run Analysis Queries**  
   Use `analysis_queries.sql` directly in pgAdmin or integrate into a Python notebook.

5. **Visualize in Python**  
   Use `pandas`, `matplotlib`, and `seaborn` in `northwind_analysis.ipynb` for data exploration and plotting.

---

## Skills Demonstrated

- SQL query design and optimization using multiple joins and groupings  
- Enforcing database constraints for data integrity  
- Data analysis and cleaning using Python  
- Visualization techniques for business analytics  
- Communication of insights through interactive notebooks

---

## Author

**Mrunmayee Limaye**  
GitHub: [MrunmayeeL](https://github.com/MrunmayeeL)
