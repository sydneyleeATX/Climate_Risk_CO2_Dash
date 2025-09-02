# Climate Change Vulnerability and Emissions Dashboard 

An interactive climate data dashboard built in Python to explore national emissions and climate vulnerability. 
---

## Project Goals
- Visualize climate vulnerability and emissions data across countries.  
- Provide interactive maps and charts to explore global patterns.   
- Offer a country-level drilldown for deeper analysis.  

---

## Tech Stack
- **Python** (Jupyter Notebook)  
- **Dash & Plotly** → Interactive dashboard components  
- **Folium** → Choropleth maps & geospatial visualization  
- **Pandas** → Data cleaning and transformation  
- **Matplotlib** → Data plotting  
- **NumPy** → Numerical computation  

---

## 📂 Features
- **Choropleth Maps**:  
  Visualize emissions and climate vulnerability across countries.  

- **Country Drilldown**:  
  Click on a country to view detailed stats   

---

## 🔬 Implementation Steps
1. **Data Collection**  
   - Datasets sourced from the **Global Carbon Project**, **ND-GAIN Index**, and other open climate databases.  

2. **Data Preprocessing**  
   - Cleaned and merged datasets using **Pandas**.  
   - Normalized country names for consistency.  
   - Handled missing values and outliers.  

3. **Exploratory Data Analysis (EDA)**  
   - Generated correlation plots between CO₂ emissions, GDP, and climate vulnerability.  
   - Identified high-risk regions and socio-economic patterns.  

4. **Visualization**  
   - Created interactive maps with **Folium**.  
   - Built time-series and bar charts with **Plotly/Matplotlib**.  

5. **Dashboard Development**  
   - Integrated all visualizations into an interactive dashboard using **Dash**.  
   - Added user interactivity for selecting countries and indicators.  

## Future Steps
- The current implementation focuses only on carbon emissions and climate risk. Future development will expand the dashboard to include additional datasets and metrics, such as: GDP, life expectancy, renewable energy percentage, natural disaster frequency, and government stability indicators. 
---

## 🚀 How to Run
1. Clone this repository:  
   ```bash
   git clone https://github.com/your-username/ClimateDash.git
   cd ClimateDash

