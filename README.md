# Online Retail Analysis & Strategy Dashboard

## 1. Project Objective
This project performs an end-to-end analysis of a transactional e-commerce dataset. The goal was to clean the raw data, perform RFM (Recency, Frequency, Monetary) analysis to segment customers, identify key sales trends, and present these findings in a live, interactive dashboard with actionable business recommendations.

---

## 2. Live Interactive Dashboard
This project was deployed as a live, single-page web application using GitHub Pages. The dashboard is fully interactive and showcases the final results of the analysis.

### [>> View the Live Interactive Dashboard <<](http://praveenchalla.me/customer-segmentation-analysis/)

---

## 3. Key Business Insights & Recommendations

* **Customer Segmentation:** The customer base was successfully segmented into distinct groups. The largest and most valuable segment is our **"Champions"** (1,313 customers).
    * **Recommendation:** Implement a loyalty program for "Champions" to maintain their high value. For the 480 customers in the "Needs Attention" segment, launch a feedback survey campaign to understand their needs before they become at-risk.

* **Sales Trends:** The data reveals a massive, predictable sales peak every November, consistently generating over $1.1M in revenue.
    * **Recommendation:** Capitalize on this seasonality by increasing inventory stock by October and launching holiday marketing campaigns early to capture peak demand.

* **Geographic Performance:** The **United Kingdom** is the primary market, generating over $7.2M in revenue. The next most significant markets are the Netherlands and EIRE.
    * **Recommendation:** While maintaining dominance in the UK, launch targeted digital marketing campaigns in the Netherlands and EIRE to drive growth in these high-potential regions.

* **Top Products:** Products like 'PAPER CRAFT, LITTLE BIRDIE' and 'REGENCY CAKESTAND 3 TIER' are significant revenue drivers.
    * **Recommendation:** Ensure these top-performing products are always in stock and feature them prominently on the website homepage and in marketing emails to boost sales.

---

## 4. Key Visualizations

Here are the key static visualizations generated during the Python analysis phase.


<img width="954" height="553" alt="customer_segments" src="https://github.com/user-attachments/assets/6dffac5d-02bd-42e5-90ed-d450faa7148d" />

### Customer Segmentation Distribution

*This bar chart displays the total number of customers within each RFM segment. It clearly identifies "Champions" as the largest group, providing a clear focus for retention-based marketing efforts.*

---

<img width="1018" height="569" alt="monthly_sales" src="https://github.com/user-attachments/assets/e6e06117-56e4-4c57-94a9-acff54fd5a69" />

### Monthly Sales Revenue Trend

*This line chart tracks total sales revenue over time, clearly illustrating the strong seasonal trend with a significant peak in November leading up to the holiday season.*

---

<img width="939" height="553" alt="top_countries" src="https://github.com/user-attachments/assets/f8877c67-c366-440d-aa92-f6b39cddf5db" />


### Top 10 Countries by Revenue
*This chart ranks the top 10 countries by total revenue. It highlights the overwhelming importance of the domestic UK market and pinpoints the Netherlands and EIRE as key international growth opportunities.*

---

<img width="1114" height="553" alt="top_products" src="https://github.com/user-attachments/assets/93cb8e10-1d8f-4a42-af88-a48db7488a18" />

### Top 10 Products by Revenue

*This bar chart identifies the most profitable products in the catalog. 'PAPER CRAFT, LITTLE BIRDIE' stands out as the top revenue generator, guiding inventory and marketing focus.*



## 5. Technology & Skills Demonstrated

* **Data Cleaning & Analysis:** Python (Pandas, NumPy)
* **Data Visualization:** Matplotlib, Seaborn
* **Dashboard Development:** HTML, CSS (Tailwind), JavaScript (Chart.js)
* **Deployment:** GitHub Pages

---

## 6. How to Run This Project Locally

1.  **Clone the Repository:**
    ```sh
    git clone [https://github.com/praveenarjun/customer-segmentation-analysis.git](https://github.com/praveenarjun/customer-segmentation-analysis.git)
    ```
2.  **Navigate to the Project Directory:**
    ```sh
    cd customer-segmentation-analysis
    ```
3.  **Install Required Python Libraries:**
    ```sh
    pip install pandas matplotlib seaborn openpyxl
    ```
4.  **View the Dashboard:**
    * Open the `index.html` file directly in your web browser.
