# Inventory & Supply Chain Analytics Dashboard

## Project Overview

This project builds an **Inventory and Supply Chain Management Dashboard** using **Python, MySQL, and Streamlit**. The system provides an interactive interface that allows users to **monitor inventory levels, track orders and shipments, and manage supply chain operations** without writing SQL queries.

In many organizations, operations teams and managers need to interact with databases but may not have strong technical skills. This project demonstrates how a **user-friendly dashboard can simplify database interactions** and help stakeholders make data-driven decisions.

The application enables users to:

* View inventory and product information
* Track orders and shipments
* Update stock levels
* Generate reports and summaries
* Analyze supply chain performance

---

## Business Problem

Companies often face challenges in managing inventory and supply chain operations, such as:

* Overstocking or understocking of products
* Lack of visibility into current inventory levels
* Inefficient tracking of orders and shipments
* Difficulty in accessing operational data

This dashboard helps address these problems by providing **real-time insights into inventory and supply chain data** through an interactive analytics interface.

---

## How the Project Works

The system is built using **two main layers**.

### 1. Database Layer (MySQL)

The backend database stores and processes supply chain data.

#### Tables

* **Products** – stores product details such as name, category, and price
* **Orders** – records customer orders
* **Shipments** – tracks shipment details and delivery status
* **Inventory** – maintains stock levels of each product

#### Views

Views are used to generate analytical summaries such as:

* Inventory status reports
* Product movement history
* Order tracking summaries

#### Stored Procedures

Stored procedures automate common operations like:

* Receiving new shipments
* Updating inventory stock
* Processing order updates

#### Functions

Functions perform business calculations such as:

* Checking if a product needs restocking
* Calculating inventory value
* Verifying product availability

---

### 2. Application Layer (Streamlit Dashboard)

The frontend application is built using **Streamlit**, which provides a web-based interface connected to the MySQL database.

Users can:

* View and filter data from tables and views
* Run stored procedures using buttons
* Add or update records through forms
* Execute business calculations using database functions
* View results instantly in the dashboard

This approach allows users to **interact with database systems without writing SQL queries**.

---

## Dashboard Features

* Inventory monitoring dashboard
* Product stock management
* Order tracking system
* Shipment tracking
* Supply chain analytics
* Real-time database interaction
* Interactive user interface

---

## Technology Stack

| Technology | Purpose                      |
| ---------- | ---------------------------- |
| Python     | Application logic            |
| Streamlit  | Interactive dashboard        |
| MySQL      | Database management          |
| SQL        | Data querying and processing |
| Pandas     | Data handling and analysis   |

---

## Skills Demonstrated

This project demonstrates the following technical skills:

* Advanced SQL (Views, Stored Procedures, Functions)
* Database schema design
* Python data applications
* Dashboard development using Streamlit
* Integration of SQL databases with Python
* Building interactive analytical tools

---

## Project Structure

```
inventory-supply-chain-dashboard
│
├── data
│   └── supply_chain_dataset.csv
│
├── sql
│   ├── create_tables.sql
│   ├── views.sql
│   ├── stored_procedures.sql
│   └── functions.sql
│
├── dashboard
│   └── app.py
│
├── screenshots
│   ├── dashboard_overview.png
│   ├── inventory_analysis.png
│   └── shipment_tracking.png
│
├── requirements.txt
└── README.md
```

---

## Dashboard Preview

### Inventory Overview

Displays stock levels and inventory distribution.

![Inventory Dashboard](screenshots/dashboard_overview.png)

### Order and Shipment Tracking

Track order processing and shipment status.

![Shipment Tracking](screenshots/shipment_tracking.png)

### Inventory Analysis

Analyze demand and monitor stock availability.

![Inventory Analysis](screenshots/inventory_analysis.png)

---

## Future Improvements

Possible future enhancements include:

* Demand forecasting using machine learning
* Supplier performance analysis
* Automated restocking alerts
* Cloud deployment for real-time access
* Integration with enterprise systems

---

## Use Case

This system can be used by:

* Inventory managers
* Operations teams
* Supply chain analysts
* Business managers

The dashboard provides **real-time insights into supply chain operations**, enabling better decision-making and improved inventory management.
