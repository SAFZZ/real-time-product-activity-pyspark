# Real-Time Product Activity Monitoring with PySpark

This project simulates a real-time data engineering pipeline to monitor user interactions with products—such as views, clicks, and purchases—using PySpark. It demonstrates key skills in data generation, transformation, and analytics in a pseudo-streaming environment.

---

## 📌 Objective

To showcase the ability to build a scalable data processing pipeline using PySpark, with a focus on real-time-like simulation, aggregation, and insight generation for product and user analytics.

---

## 🛠️ Technologies Used

- Python
- PySpark
- Google Colab (for notebook execution)
- Pandas

---

## 📈 Key Features

- Simulates real-time product event data
- Cleans and processes data using PySpark
- Performs aggregation for:
  - Total counts of each user action
  - Most viewed/purchased products
  - Most active users
- Exports results to CSV for reporting and visualization

---

## 📂 Project Structure

real-time-product-activity/
│
├── notebooks/
│   └── realtime_analysis.ipynb
├── data/
│   ├── raw_events.csv
│   ├── action_counts.csv
│   ├── popular_products.csv
│   └── user_activity.csv
├── README.md


---

## ▶️ How to Run

1. Open the notebook: `notebooks/realtime_analysis.ipynb` in Google Colab.
2. Run all cells sequentially:
   - Data simulation
   - Data processing with PySpark
   - CSV export of results
3. Output files will be saved to the `data/` directory.

---

## 📊 Sample Insights

- **Most viewed product**: Product_42
- **Most active user**: User_1098
- **Top action type**: View

---

## 💼 Use Cases

- Real-time dashboard analytics
- E-commerce clickstream processing
- Product trend monitoring
- User behavior analysis

---

## 👤 Author

**Safzz**  
Associate Software Engineer | Data Engineering Enthusiast  
🔗 [GitHub Profile](https://github.com/SAFZZ)

---

## 📃 License

This project is open for educational and demonstration purposes.
