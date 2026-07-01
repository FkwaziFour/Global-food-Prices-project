Here is a clean, comprehensive, and professional markdown description for your new repository, **Global-food-Prices-project**, based on your uploaded GitHub screenshot.

---

# # Global Food Prices Analytics Project

This repository houses an end-to-end data analytics and business intelligence project focused on cleaning, transforming, modeling, and visualizing historical global food price data. The project bridges backend data engineering with frontend interactive dashboards to surface macroeconomic insights into inflation, commodity volatility, and regional market trends.

---

## ## Repository Structure

The files in this repository represent a complete lifecycle from raw data ingestion to executive-level visualization assets:

* **`Food_Prices_raw.csv`** – The original, untamed raw source dataset containing raw regional price logs, localized currencies, and unformatted market identifiers.
* **`Food_Prices_Dataset.xlsx`** – The structured, clean staging database. This workbook contains refined data splits categorized for optimization and data verification checks.
* **`Food_Prices.sas`** – The data engineering pipeline script. Written in SAS, this module handles parsing, type conversions (handling localized dates/currencies), outliers treatment, categorical pooling, and aggregate statistical indexing.
* **`Global Food Prices Dashboard.pbix`** – The interactive frontend business intelligence application built in Microsoft Power BI. It includes relational star-schema modeling, DAX measures for calculating year-over-year price deltas, and multi-page visual narratives.
* **`Global_Food_Prices_Case_Study.pdf`** – A comprehensive formal report detailing the methodologies, analytical frameworks, statistical findings, and economic insights derived from the data pipeline.
* **`README.md`** – The primary repository directory guide and project overview markdown file.

---

## ## Project Workflow & Architecture

The architecture relies on a traditional data-to-dashboard pipeline:


[Raw Data] -> [SAS Processing Engine] -> [Structured Output] -> [Power BI Desktop] -> [Executive PDF Insights]



### ### 1. Data Processing & Pipeline Design (`SAS`)

* **Ingestion & Integrity:** Programmatically reads the `Food_Prices_raw.csv` file, converting text-based periods into mathematically viable dates and aligning disjointed currency markers.
* **Feature Engineering:** Computes moving averages, identifies standard deviation outliers for price shocks, and builds normalized indexes to compare varying commodities uniformly.
* **Data Structuring:** Outputs relational matrix models that map cleanly into BI staging environments without requiring further formatting.

### ### 2. Relational Modeling & BI Engineering (`Power BI`)

* **Data Modeling:** Links commodity types, regional geographic locations, and timespans using an optimized Star Schema setup.
* **DAX Analytics:** Leverages Data Analysis Expressions (DAX) to build dynamic time-intelligence measures (e.g., *Moving Average Trends*, *Inflation Rates*, and *Peak Price Shock Voltilities*).
* **Interactive Design:** Showcases cross-filtering visuals, geospatial maps tracking regional price distributions, and historical trend lines with forecast bands.

### ### 3. Business Context & Strategic Reporting

The final narrative synthesizes data processing with visualization panels to explain global food vulnerability corridors, supply chain blockages, and inflationary trends. It turns technical code into a clean, intuitive presentation package perfect for economic researchers, analysts, or executive stakeholders.
