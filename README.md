# Telecom Traffic Dashboard: Optimizing Revenue Assurance Controls

This project implements a **Big Data architecture** designed to manage and analyze **telecom network traffic** to optimize **revenue assurance controls**. The system processes large volumes of network traffic data using **ETL pipelines** and provides real-time insights through a **Power BI dashboard**. 

### Key Technologies and Tools:
1. **ETL Pipeline & Data Processing**:
   - **Apache NiFi**: Used for orchestrating the ELT (Extract, Load, Transform ) process. NiFi helps automate data ingestion, transformation, and routing from various sources to a central data repository.
   - **PySpark**: Used for processing large-scale telecom data, including data transformation, aggregation, and analytics on distributed systems.
   
2. **Dashboard**:
   - **Power BI**: An interactive data visualization tool used to create dashboards displaying key telecom network metrics, such as traffic volumes, anomaly detection, and revenue assurance insights.

## Project Overview

The project optimizes revenue assurance by:
- Collecting network traffic data using **Apache NiFi** for ingestion.
- Transforming and processing large volumes of data using **PySpark** for real-time analysis.
- Visualizing the data through a **Power BI** dashboard that helps telecom operators monitor and manage network traffic.

## Project Structure

- **Data/**: Contains sample telecom network traffic data used in the analysis.
- **Code/**: 
  - **ETL/**: Scripts for processing and transforming data using **PySpark**.
  - **Orchestration/**: NiFi configurations for data ingestion and flow control.
- **Architecture/**: Diagrams explaining the architecture of the Big Data pipeline.
- **Insights/**: Key insights derived from the processed data, including findings related to traffic patterns and revenue assurance opportunities.
- **Dashboard/**: Power BI dashboard files with reports and visualizations.

## Technologies Used

- **ETL & Data Processing**: 
  - **Apache NiFi**: For data ingestion, transformation, and orchestration.
  - **PySpark**: For data processing and transformations on distributed systems (Hadoop/Spark).
  
- **Data Storage & Processing**: 
  - **Hadoop** or **Spark**: For distributed data processing and storage.

- **Visualization**:
  - **Power BI**: For creating interactive reports and dashboards.

## Key Features

- **ETL Pipeline**: 
  - Data ingestion from multiple sources using **Apache NiFi**.
  - Data processing and transformation using **PySpark** for scalable and distributed data processing.

- **Revenue Assurance Monitoring**:
  - Analyze telecom network traffic and identify potential revenue leakage or fraud patterns.

- **Power BI Dashboard**:
  - Visual representation of network performance, traffic volume trends, and anomaly detection.
  - Real-time insights into telecom traffic that help optimize revenue assurance controls.

## Data Source

The dataset used in this project comes from telecom network traffic logs. This data is used to analyze network performance, identify anomalies, and optimize revenue assurance controls.

## Screenshots

### Power BI Dashboard
![image](https://github.com/user-attachments/assets/f5875f18-df2b-4944-9daf-c61b4b6105c4)
![image](https://github.com/user-attachments/assets/b3bbdac9-7e77-4368-9d97-2fc3eaef9e79)
![image](https://github.com/user-attachments/assets/4416d045-f7ee-4d7b-85d5-cd7eafad74f7)


## Insights

1. **Traffic Anomalies**: Detect traffic anomalies that may indicate potential fraud or inefficiency.
2. **Revenue Leakage**: Identify patterns in network traffic that correlate with revenue loss.
3. **Optimization Opportunities**: Insights into network performance that lead to improved operational efficiency.

## How to Run the Project

1. **ETL Pipeline**:
   - **Apache NiFi**: 
     - Clone the **Code/Orchestration/** folder, which contains NiFi flow configurations for data ingestion and orchestration.
     - Install NiFi locally or set up a NiFi cluster to manage your flows.
     - Import the NiFi templates and configure data sources.
  
   - **PySpark**: 
     - Install **PySpark** on your local machine or use a Spark cluster for processing data.
     - Modify the **Code/ETL/** folder’s PySpark scripts to match your data sources and processing logic.

2. **Power BI Dashboard**:
   - Download the Power BI files from the **Dashboard/** folder.
   - Open the Power BI files and connect them to the processed data source.
   - Explore the interactive reports to visualize traffic patterns, anomalies, and key insights.

## Contact

For more details or inquiries, feel free to reach out:

- **Email**: Maissabenamor8@gmail.com
- **LinkedIn**: [https://www.linkedin.com/in/maissa-ben-amor-201601205/](#)
