# 🚚 Fleet Performance & Delivery Efficiency Dashboard

An interactive **Power BI dashboard** developed using **Power Query** and **Power BI** to analyze fleet operations, delivery performance, fuel efficiency, maintenance costs, and transportation expenses. The project demonstrates end-to-end Business Intelligence techniques, including data transformation, data modelling, DAX calculations, AI-powered analytics, and interactive reporting.

---

## 📌 Project Overview

This project focuses on monitoring and optimizing fleet operations through an interactive dashboard. It provides valuable insights into delivery efficiency, fuel consumption, vehicle maintenance, and transportation costs, enabling data-driven operational decision-making.

### Expected Output

An interactive transport operations dashboard that helps optimize fleet utilization, improve delivery performance, monitor fuel efficiency, evaluate maintenance costs, and support informed business decisions.

---

## 🎯 Objectives

- Analyze fleet delivery performance across destinations.
- Monitor on-time delivery performance.
- Evaluate fuel efficiency trends.
- Compare maintenance costs by vehicle type.
- Measure transportation cost per kilometre.
- Demonstrate AI-powered analytics using Power BI.

---

## 🛠 Tools & Technologies

- Microsoft Power Query
- Microsoft Power BI Desktop
- DAX (Data Analysis Expressions)

---

## 🗂 Data Model

A **Star Schema** data model was implemented.

### Fact Table
- Trip Data

### Dimension Table
- Vehicle Master

### Relationship
- Trip Data[Vehicle_ID] → Vehicle Master[Vehicle_ID]
- Cardinality: **Many-to-One (*:1)**

---

## 📊 Dashboard Features

### KPI Cards
- Total Trips
- Total Fuel Consumed
- On-Time Trips
- On-Time Delivery %
- Average Fuel Efficiency
- Cost per km

### Visualizations
- Fuel Efficiency Trend (Line Chart)
- On-Time Delivery % by Destination (Bar Chart)
- Average Maintenance Cost by Vehicle Type (Pie Chart)

### Interactive Features
- Delivery Date Slicer
- Delivery Status Slicer
- Destination Slicer
- Clear All Slicers Button

---

## 🤖 AI-Powered Analytics

### ✔ Teach Q&A
Natural Language Query:

> **Average Cost per km by vehicle type**

### ✔ Key Influencers

**Analyze**
- Delivery Status

**Explain By**
- Distance
- Vehicle Type
- Driver_ID

### ✔ Decomposition Tree

**Analyze**
- Cost per km

**Explain By**
- Vehicle Type
- Maintenance Cost
- Distance

---

## 📈 Key Insights

- Analyzed **50 delivery trips**.
- Achieved an **On-Time Delivery Rate of 60%**.
- Total fuel consumption reached **4.58K litres**.
- Average fuel efficiency was **11.57 km/L**.
- Average transportation cost was **₹10.08 per km**.
- Delhi and Pune recorded the highest on-time delivery performance.
- Truck vehicles incurred the highest maintenance costs.
- AI analysis identified **Driver D03** as the strongest factor influencing on-time deliveries.

---

## 📂 Repository Structure

```text
Fleet-Performance-Delivery-Efficiency-PowerBI
│
├── Dataset/
├── Power BI Dashboard/
│   └── Fleet_Performance_Dashboard.pbix
├── Documentation/
│   ├── Project_Report.pdf
│   └── Technical_Documentation.pdf
├── Images/
│   ├── Dashboard.png
│   ├── Data_Model.png
│   ├── QA_Teach.png
│   ├── Key_Influencers.png
│   └── Decomposition_Tree.png
└── README.md
```

---

## 🖼 Dashboard Preview

```markdown
<img width="1217" height="674" alt="image" src="https://github.com/user-attachments/assets/73672817-160e-46ea-a5df-67427823335f" />

```

---

## 🗄 Data Model

```markdown
<img width="1201" height="561" alt="image" src="https://github.com/user-attachments/assets/3fad0366-7b7c-4357-b56b-2883185c6364" />

```

---

## 🤖 AI Visuals

### Teach Q&A

```markdown
<img width="588" height="330" alt="image" src="https://github.com/user-attachments/assets/2fa4eab9-aec9-49ed-9f0f-d004f61547ba" />

```

### Key Influencers

```markdown
<img width="1045" height="546" alt="image" src="https://github.com/user-attachments/assets/071f65ea-6476-4a57-9d7f-17dc77dd0602" />

```

### Decomposition Tree

```markdown
<img width="727" height="439" alt="image" src="https://github.com/user-attachments/assets/65fbca4c-c6e7-4546-b714-5382d26033fe" />

```

---

## 🚀 Skills Demonstrated

- Data Import & Transformation
- Data Cleaning
- Power Query
- Star Schema Data Modelling
- DAX Measures
- Relationship Management
- Interactive Dashboard Design
- AI-Powered Analytics
- Business Intelligence Reporting

---## 📌 Conclusion

This project demonstrates an end-to-end Business Intelligence solution using **Power Query** and **Power BI**. By combining data transformation, star schema modelling, DAX calculations, AI-powered analytics, and interactive visualizations, the dashboard provides actionable insights into fleet operations, delivery performance, fuel efficiency, and transportation costs.

---

## 👩‍💻 Author

**Maathangi**

- **GitHub:** https://github.com/Maathangi1412
- **LinkedIn:** www.linkedin.com/in/maathangi-p-560266333


A **Star Schema** data model was implemented.
