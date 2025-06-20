
🧾 Restaurant Order Analysis in SQL (with solutions)

📌 Overview

This SQL project explores restaurant data by analyzing the Menu Items and Order Details tables. The analysis covers data cleaning, price insights, category patterns, and identifying top-spending customers. It provides a solid demonstration of data manipulation and business intelligence using SQL.




🗂 Project Structure

📁 Folder / 📄 File

🧾 Description


├── create_database.sql     | Creates the database and fixes column name issues

├── explore_menu_items.sql  | Basic menu insights: pricing, dish count, categories

├── clean_order_details.sql | Cleans order_details: date formatting and time conversion

├── analysis_queries.sql    |  Standalone analysis: order frequency, item counts

└── join_analysis.sql       | Combines tables to extract deep customer and sales insights



📊 Key Questions Answered

- What are the least and most expensive menu items?

- How many dishes are in each category?

- How many orders were placed each day?

- What were the top 5 highest-spending orders?

- What dish was ordered the most?
 


## ✅ Key Insights

- The highest-spending order consisted mainly of Italian dishes.
 
- A few orders had more than 12 items, which may indicate bulk or group purchases.
  
- Some items appear disproportionately in high-value orders.

🧼 Cleaning Tasks Performed

- Standardized inconsistent order_time entries (e.g., changed / to :)

- Reformatted order_date into YYYY-MM-DD

- Converted order_time from string to SQL TIME format

🔗 Dataset Source

This project uses sample restaurant data originally published on Kaggle.
If you’d like to explore the raw data, search for restaurant order datasets on Kaggle or replicate with your own.

🛠 Tools Used

- SQL (MySQL syntax)

- GitHub for version control
  
- VS Code / DBMS tools for running queries

👤 Author

Akinwande Wasiu Olanrewaju

🎓 BSc in Transport Planning and Management

📊 Junior Data Analyst

🔗 [LinkedIn](https://www.linkedin.com/in/akinwande-wasiu-b49b62327)| [GitHub](https://github.com/wandewise)

## 🛠 Tech Stack
- SQL (MySQL dialect)
- GitHub for version control







