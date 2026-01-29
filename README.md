 📊 E-Commerce Sales Data Analysis (EDA)
📌 Project Overview This project focuses on performing **data cleaning and exploratory data analysis (EDA)** on an e-commerce sales dataset to uncover meaningful business insights. The analysis explores customer demographics, purchasing behavior, product performance, discount strategies, and city-wise sales trends. The goal of this project is to demonstrate **data analysis skills using Python**, including data preprocessing, feature engineering, visualization, and insight generation — making it suitable for a **GitHub portfolio, internships, and entry-level data analyst roles**. 
🗂 Dataset Description The dataset contains order-level data from an Indian e-commerce platform.
🔑 Key Columns * order_id – Unique order identifier * order_date – Date of purchase * customer_id – Unique customer ID * gender – Customer gender * age – Customer age * city – Customer city * product_category – Product category * product_name – Product name * quantity – Units purchased * unit_price – Price per unit * discount_percent – Discount applied * payment_mode – Payment method * rating – Product rating (1–5)
🆕 Engineered Feature * total_sales – Final revenue after applying discount 
🛠 Tools & Libraries Used * **Python** * **Pandas** – Data manipulation * **Matplotlib** – Data visualization 
🧹 Data Cleaning Steps * Checked and confirmed **no missing values** * Removed duplicate records * Converted order_date to datetime format * Created a new total_sales column for revenue analysis
🔍 Exploratory Data Analysis (EDA)
📦 Product Category Insights * **Electronics** generated the highest revenue * **Home Appliances** and **Clothing** followed closely * **Books** contributed the least to total sales ### 🏙 City-wise Sales Trends * **Delhi** and **Bangalore** were the top-performing cities * Metro cities significantly outperformed tier-2 cities
👤 Customer Demographics * Majority of customers fall within the **25–45 age group** * Older customers made fewer purchases but higher-value transactions💸 Discount Analysis * Higher discounts were applied to **high-priced products** * Discounts did not negatively impact product ratings
⭐ Ratings Analysis * Average rating: **4.38** * No extreme low ratings, indicating good product quality
📈 Visualizations Included * Total sales by product category * Total sales by city * Customer age distribution
💡 Key Business Insights * Focus marketing efforts on **electronics and home appliances** * Target **metro cities** for higher revenue generation * Use discounts strategically on high-ticket items * Prioritize customers aged **25–45** for campaigns.
▶️ How to Run the Project 1. Clone the repository
bash
git clone https://github.com/your-username/E-Commerce-EDA.git
2. Install dependencies
bash
pip install -r requirements.txt
3. Run the Jupyter Notebook
bash
jupyter notebook
🚀 Future Improvements * Expand dataset for deeper analysis * Add Seaborn & advanced visualizations * Build a sales prediction model * Deploy insights using Streamlit dashboard
👤 Author **Dishant Kudtarkar** Aspiring Data Analyst | Python | Pandas | Data Visualization

👤 Author **Dishant Kudtarkar** Aspiring Data Analyst | Python | Pandas | Data Visualization
