### awproject-DatawarehouseSales

#  Azure Data Engineering Project – DatawarehouseSales

This project demonstrates an end-to-end data pipeline using **Azure Data Factory (ADF)**, **Data Lake Storage Gen2**,**Databricks** and **GitHub**, implementing the **Bronze → Silver → Gold** architecture pattern.
#### Architecture Overview

GitHub (Raw Files / Code)
        ⬇
    [ADF Pipeline 1]
        ⬇
Bronze Layer (Raw Data in ADLS)
        ⬇
    [ Databricks ]
        ⬇
Silver Layer (Cleaned/Curated Data)
        ⬇
Gold Layer (Aggregated Data for Analytics)
        
