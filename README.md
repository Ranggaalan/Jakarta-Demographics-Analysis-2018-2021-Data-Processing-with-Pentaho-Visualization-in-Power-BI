# **Jakarta Demographics Analysis (2018-2021) – Data Processing with Pentaho & Visualization in Power BI**  

## **Project Description**  
This project analyzes and visualizes **Jakarta's population data from 2018 to 2021** using **Pentaho for ETL** and **Power BI for interactive visualization**. The analysis focuses on **gender distribution, age segmentation, population trends, and regional demographics**.  

![Image](https://github.com/user-attachments/assets/3b8900ea-6c81-4d49-b51b-5df794fb2c61)

## **Dataset**  
The dataset is sourced from **Jakarta Open Data (2018-2021)** and includes: 
(Link : https://satudata.jakarta.go.id)
- **Total Population**: 2.38 million residents analyzed  
- **Gender Distribution**: Male vs. female population  
- **Age Group Segmentation**: Categorized by age range  
- **Regional Breakdown**: Population distribution across administrative regions  
- **Yearly Trends**: Population changes from 2018 to 2021  

## **Methodology**  
### **1. Data Processing with Pentaho**  
- **Data Extraction**: Collecting raw population data  
- **Transformation**: Cleaning, structuring, and filtering based on relevant variables  
- **Loading**: Storing processed data for visualization  

### **2. Data Visualization with Power BI**  
- **Demographic breakdown** (gender, age, and region)  
- **Trends analysis** from 2018 to 2021  
- **Geospatial maps** displaying population density in Jakarta  
- **Comparative analysis** of male vs. female population  

## **Database Before Processing**
![Image](https://github.com/user-attachments/assets/bf535c98-891e-4b2e-aee5-f19d61ad46bf)

## **Final Database After Processing**
![Image](https://github.com/user-attachments/assets/9bee887e-8729-4943-a9b3-61dd4ee1aeee)

## **Results**
![Image](https://github.com/user-attachments/assets/62c13963-9b36-455f-b1eb-d3b1a78fea4c)

## **Key Insights**  
- **Total Population**: **2.38 million** residents analyzed.  
- **Gender Distribution**: **71.6% male** and **28.5% female**.  
- **Age Group Trends**:  
  - The **15-24 age group** is the most dominant.  
  - The **0-4 and 70+ age groups** have the lowest population.  
- **Regional Distribution**:  
  - **Jakarta Utara** has the highest population.  
  - **Jakarta Timur and Kepulauan Seribu** have the lowest population.  
- **Population Decline**:  
  - The population **declined from 0.95 million (2018) to 0.59 million (2021)**.  
  - Possible factors: **migration, low birth rate, pandemic effects**.  

## **Technologies Used**  
- **Pentaho**: Data extraction, transformation, and loading (ETL)  
- **Power BI**: Interactive dashboards and data visualization  
- **Python (Pandas, NumPy)**: Data preprocessing and analysis  

## **How to Use**  
### **Pentaho Data Processing**  
1. Open **Pentaho Data Integration**  
2. Load the transformation file (`jakarta_population_transformation.ktr`)  
3. Run the ETL process to clean and structure data  

### **Power BI Visualization**  
1. Open **Power BI**  
2. Load the processed dataset (`jakarta_population_cleaned.csv`)  
3. Explore the **Jakarta Demographics Dashboard**  

## **Conclusion**  
This project provides a **comprehensive analysis of Jakarta's population trends** from **2018 to 2021**, offering insights into **demographic distribution, regional variations, and population changes**. The combination of **Pentaho for data processing** and **Power BI for visualization** makes it easier to identify key trends and support **urban planning and policymaking**.  
