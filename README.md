---

# Supply Chain Data Analytics Project

## Overview

This project aims to analyze and visualize the supply chain data of a fashion and makeup product company. By leveraging data analytics techniques, the project uncovers key insights into various aspects of the supply chain process, including product sales, stock levels, supplier information, shipping details, and customer demographics. 

The primary focus is to enable efficient data handling through an Extract, Transform, and Load (ETL) process using Python and Snowflake, followed by insightful data visualization through an interactive Power BI dashboard. The dashboard facilitates the exploration of supply chain metrics, empowering decision-makers to optimize operations and drive better business outcomes.

## Project Motive

The motive of this project is to:
- Analyze supply chain data to extract meaningful insights.
- Transform raw data into a structured format for deeper analysis.
- Utilize Snowflake for efficient data storage and querying.
- Build an interactive dashboard with Power BI to visualize key performance indicators (KPIs) and supply chain metrics.
- Help business stakeholders optimize the supply chain process by identifying trends, inefficiencies, and areas for improvement.

## Tech Stack Used

- **Python**: Used for data extraction, cleaning, transformation, and integration.
- **Pandas**: For data manipulation and processing.
- **Snowflake**: As the cloud-based data warehouse to store and manage the transformed data.
- **Power BI**: To create a comprehensive and interactive dashboard for visualizing supply chain metrics.
- **Snowflake Connector for Python**: Used to connect Python scripts with Snowflake.
- **Jupyter Notebooks** (Optional): For initial data exploration and ETL process testing.

## Dataset Overview

The dataset covers various supply chain features, including:
- **Product Information**: Type, SKU, price, availability.
- **Sales & Revenue**: Number of products sold, revenue generated.
- **Customer Demographics**: Age, gender, location.
- **Inventory**: Stock levels, order quantities.
- **Shipping**: Times, costs, carriers, and routes.
- **Supplier Information**: Name, location, lead times.
- **Manufacturing Data**: Production volumes, costs, defect rates, inspection results.
- **Transportation**: Modes of transport, associated costs.

## Project Structure

```
|-- README.md
|-- data/
|-- processed_data.csv
|-- supply_chain_data.xlsx
|-- source/
|   |-- ETL.py
|   |-- snowflake_utils.py
|-- powerbi_file/
|   |-- supply_chain_dashboard.pbix
```

## Project Workflow

### Step 1: Extract, Transform, and Load (ETL)
- **Data Extraction**: Source the dataset from files (e.g., CSV, Excel).
- **Data Cleaning & Transformation**: Use Python and Pandas to clean, transform, and integrate the dataset.
- **Data Loading**: Load the transformed data into the Snowflake data warehouse for efficient storage and analysis.

### Step 2: Data Visualization in Power BI
- **Data Connection**: Connect Power BI to the Snowflake warehouse for data retrieval.
- **Dashboard Creation**: Design an interactive dashboard with various visualizations such as charts, graphs, and maps.
- **Data Insights**: Enable business users to gain insights from the supply chain data and drive data-driven decisions.

## Getting Started

1. **Clone the repository** to your local machine:
   ```bash
   git clone https://github.com/yourusername/supply-chain-data-analytics.git
   ```

2. **Install the required dependencies**:
   Make sure Python and necessary libraries are installed:
   ```bash
   pip install pandas snowflake-connector-python
   ```

3. **Run the ETL script**:
   Execute the ETL process by running the script to extract, transform, and load data into Snowflake.
   ```bash
   python src/ETL.py
   ```

4. **Connect Power BI to Snowflake**:
   Open Power BI and connect to Snowflake using the credentials found in `snowflake_connection_credentials.json`.

5. **Explore the Power BI Dashboard**:
   Open the `.pbix` file in Power BI to explore the visualizations and insights from the supply chain data.

## Conclusion

This project highlights the importance of a structured ETL process for efficient data handling and the power of visualization tools like Power BI in deriving actionable insights. By analyzing the supply chain data, businesses can optimize operations, improve decision-making, and ultimately enhance the overall efficiency of their supply chain processes.

