# Electronic Sales Dashboard (Version 2)

## 📊 Project Overview
This project showcases **Version 2 of the Electronic Sales Dashboard**, a refined and enhanced iteration of the original V1 report built using **Power BI**. This version introduces advanced features, improved interactivity, and additional data-driven insights, including **Pareto analysis**, **revenue analysis by electronics products**, and **regional drillthrough pages** for in-depth analysis.

Version 1 of the dashboard can be found here: [Electronic Sales Dashboard (Version 1)](https://github.com/DashOfRisk/PowerBI-Dashboard-Project/tree/a75237123d7cdbb41d6a0e2c88792f343bc68e28/Electronics%20Sales%20Dashboard).

---

## 🛠 Features

### 1. **Pareto and Revenue Analysis**
- Introduced **Pareto analysis** to identify top-performing products contributing to 80% of revenue.  
- Added a comparative **revenue analysis by product category**, covering Laptops, Mobile Phones, Smart Devices, and Tablets.  

### 2. **Advanced Geographic Insights**
- **Shape Map Visualization** for regional performance:
  - Highlights data for **each state** within the region along with a YoY comparative overview.
  - **Conditional formatting** with gradient visuals for quick identification of high and low-performing regions.

### 3. **Drillthrough Pages**
- In-depth regional analysis enabled by **drillthrough functionality** through which each region can be explored in detail for sales, profits, and product-specific performance.  

### 4. **Filters and Slicers**
- Regional filter buttons that, on hover, the message "Focus on region" showcase more user-friendly interface. After clicking, users are redirected to a page displaying insights for the chosen region.

---

## 🎯 Learning Objectives
Building upon Version 1, this project emphasises:
- Advanced **data enhancement techniques** using Python.
- Incorporation of **Pareto analysis** and other deep-dive techniques for business insights.
- Effective use of Power BI's **drillthrough functionality** for regional-level analysis.

---

## 📷 Dashboard Preview

### Dashboard Visual
![Dashboard Visual](https://github.com/DashOfRisk/PowerBI-Dashboard-Project/blob/ca99365b2a1dbca7d414d3dbe1ed143fa22f86f3/Electronic%20Sales%20Dashboard%20V2/Example%20ES%20Dashboard%20Showcase.gif)

### Dashboard Overview (Main Page)
![Dashboard Overview (Main Page)](https://raw.githubusercontent.com/DashOfRisk/PowerBI-Dashboard-Project/cfc65cf44115bc5c6c058836e4e3b19231902737/Electronic%20Sales%20Dashboard%20V2/Electronic%20Sales%20Dashboard1%20V2.png)

### Dashboard Overview (Drillthrough Page)
![Dashboard Overview (Drillthrough Page)](https://raw.githubusercontent.com/DashOfRisk/PowerBI-Dashboard-Project/cfc65cf44115bc5c6c058836e4e3b19231902737/Electronic%20Sales%20Dashboard%20V2/Electronic%20Sales%20Dashboard2%20V2.png)

---

## 🛠 Data Preparation with Python
To enhance the dataset, I used Python for preprocessing and adding depth. Below is the extract of the Python code used to generate random product models for electronics categories by importing the random libraries:

```python

def generate_models(product):
    product_models = {
        "Laptops": [f"Laptop_{i}" for i in range(1, 16)],
        "Mobile Phones": [f"Mobile_{i}" for i in range(1, 16)],
        "Smart Devices": [f"Device_{i}" for i in range(1, 16)],
        "Tablets": [f"Tablet_{i}" for i in range(1, 16)],
    }
    if product in product_models:
        return random.choice(product_models[product])  
    return "Unknown_Model"  


data['Model'] = data['Product'].apply(generate_models)


```

## 🛠 Features and Enhancements
- **Pareto Analysis**: Identified the top-performing products contributing to 80% of revenue.
- **Revenue Analysis**: Comparative revenue performance by product category (Laptops, Mobile Phones, Smart Devices, Tablets).
- **Shape Map Visualization**: Enabled regional sales insights with dynamic conditional formatting.
- **Clustered Column Chart**: Added YoY comparisons for regional sales to showcase performance trends.
- **Drillthrough Pages**: In-depth analysis for each region (West, South, Northeast, Midwest).

---

## 🛠 Tools and Technologies
- **Power BI**: Main tool for data visualisation and dashboard creation.
- **Python (pandas, random)**: For data preparation and enhancement.
- **Excel/CSV**: Data source preparation.
- **GitHub**: Version control and portfolio showcase.

---

## 📈 Insights and Results
1. **Regional and Product Insights**: Provided a comprehensive breakdown of sales and profit performance across regions and product categories.
2. **YoY Trends and Drillthrough**: Enabled deeper insights with drillthrough pages for each region, allowing targeted performance reviews building on V1.
3. **Pareto Analysis**: Identified the key products driving revenue, supporting strategic decision-making.

---

## 🌟 Key Takeaways
This updated version of the dashboard demonstrates:
- Expertise in advanced Power BI features, including **drillthrough analysis** and **Pareto visualisations**.
- Proficiency in using Python to preprocess and enrich datasets for reporting purposes.
- Enhanced storytelling through cohesive design and intuitive interactivity.

---

## 🚀 Continuity and Future Plans

### Next Steps in Power BI Learning Journey:
1. **Integrating AI and Machine Learning**:
   - Use **Power BI AI visuals** like Decomposition Trees and Key Influencers.
   - Incorporate external ML models into Power BI reports.
2. **Custom Visuals and Themes**:
   - Create **custom visuals** using R or Python.
   - Design **custom themes** to align with branding.
3. **Advanced Data Modelling**:
   - Implement **calculation groups** for measures.
   - Optimise data models for performance and scalability.

By continuing along this path, I aim to create **enterprise-grade dashboards** and take on complex business analytics challenges.

---

## 👨‍💻 Author
**Reeve Dmello**  
[LinkedIn](https://www.linkedin.com/in/reeve-d-0b481a238/)

---

## 📜 Disclaimer
This project builds upon Version 1, created as part of the **Power BI Park** community, under the guidance of **Injae Park**. All materials, including datasets and PBIX files, are for educational purposes only and may not be redistributed or used commercially without explicit permission.
