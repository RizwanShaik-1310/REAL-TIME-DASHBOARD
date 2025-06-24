# REAL-TIME-DASHBOARD

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: SHAIK RIZWAN AHAMED

*INTERN ID*: CT08DG1887

*DOMAIN*: POWER BI

*DURATION*: 8 WEEKS

*MENTOR*: NEELA SANTOSH KUMAR

# ⏱️ Power BI Internship – Task 3: Real-Time Dashboard Using Streaming Data

## 📌 Internship Task Description

**Objective:**  
Create a real-time dashboard in Power BI using streaming data from Microsoft Azure or a simulated API.

**Task Statement:**  
> Set up a real-time dashboard using streaming data (e.g., from Azure or a simulated API feed). Deliverable: A live Power BI dashboard that updates in real-time.

This task demonstrates Power BI's capability to ingest and visualize **live streaming data**, offering insights that update instantly as new data flows in.

---

## 🌐 Tools & Platforms Used

| Tool/Platform           | Purpose                                          |
|-------------------------|--------------------------------------------------|
| **Power BI Service**    | Real-time dashboard setup and hosting            |
| **Microsoft Azure**     | Streaming dataset setup via REST API simulator   |
| **Power Automate**      | Optional – Triggered dataset updates             |
| **Power BI Desktop**    | For designing visuals before live deployment     |

---

## 🧪 Data Simulation Approach

Since no live IoT device or production API was available, I used a **manual streaming method** to simulate real-time data updates. Data values like `Units Sold`, `Profit`, and `Sales Time` were generated and pushed to Power BI using the **Streaming Dataset** feature in Power BI Service.

---

## 🧾 Streaming Dataset Setup

1. **Logged into Power BI Service**
   - URL: https://app.powerbi.com

2. **Created a New Streaming Dataset**
   - Type: API (Push)
   - Fields:
     - `Product` (Text)
     - `UnitsSold` (Number)
     - `SalesTime` (DateTime)
     - `Region` (Text)
     - `Profit` (Number)

3. **Enabled Historic Data Analysis**
   - Allowed visuals like line charts and tables to be populated from the dataset

---

## ⚙️ Real-Time Dashboard Configuration

1. **Created Tiles on Dashboard:**
   - **Bar Chart:** Units Sold by Product

2. **Data Push Simulation:**
   - Data was manually or automatically pushed using:
     - Power Automate (low-code flows)
     - Postman (manual POST requests)
     - Python script (optional – for JSON payload simulation)

---

## 📈 Key Visualizations

- 📊 **Live Line Chart:** Real-time units sold over time
- 🧭 **Product Performance Bar:** Top products by sales
- 💰 **Profit Monitoring Card:** Max profit in last few records
- 🌍 **Region Tracker Table:** Live feed of sales by region

---

---

## 🧠 Key Learnings & Skills

- Working with **Power BI Service**
- Understanding how **Streaming Datasets** work
- Designing **live dashboards** that auto-update
- Basics of **Power Automate** and REST APIs
- Real-time **line/bar charts** and **data cards**

---

## 💡 Observations

- Power BI supports **Push datasets** through APIs, enabling integration with real-world sensors, finance systems, or CRMs.
- While historic analysis allows for plotting and slicing, pure streaming visuals like real-time line graphs are **only available on dashboards**, not reports.
- This method opens the door to integrating Power BI with **IoT devices**, **POS systems**, and **live databases**.

---

## 📌 Conclusion

This task gave me practical experience in building dashboards that reflect **up-to-the-second changes**. Real-time dashboards are increasingly important in today's data-driven world, especially for monitoring live transactions, website metrics, supply chain operations, and sensor-based systems. Learning how to simulate and visualize live data in Power BI has significantly deepened my understanding of **BI integration with live systems** and **data refresh mechanics**.

---

## 📝 License

This repository is maintained for academic and internship purposes only.

## OUTPUT of this task:

- The below image is the last updated visual of the report
![Image](https://github.com/user-attachments/assets/36123b3d-5065-4aef-acd8-8465fc6b55bb)

- The below image is the real-time syncing of the report
![Image](https://github.com/user-attachments/assets/71a075cb-a18d-409b-ad81-2ff804b8b081)

- The below image is the latest updated visual of the report
![Image](https://github.com/user-attachments/assets/6472cb66-f89a-419c-8a6b-f96d63b32a7c)
