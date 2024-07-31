# Databricks Workshop
This workshop is from [Adastra Thailand's 2024 University Workshop](https://github.com/AdastraTH/2024-univ-workshop).

### Medallion Architecture
In Databricks, Medallion architecture can be implemented using Delta Lake, which provides ACID transactions, scalable metadata handling, and data versioning. It involves organizing data into layers or stages, typically named Bronze, Silver, and Gold, to improve data quality, performance, and manageability.
- Bronze layer
- Sliver: flitered, cleaned, augmented
- Gold: business-level aggrates

### Getting Start with Databricks
Sign up for Databricks Community Edition at [community.cloud.databricks.com](https://community.cloud.databricks.com/login.html?tuuid=8a57b53c-3747-44a5-a35d-1a2c29931bfd). Once registered, you can import "notebooks".
```
https://github.com/siriyaparn/databricks-workshop/blob/main/data-engineering-workshop.dbc
```

In Databricks, when a notebook is executed, it creates a Spark object, which is a Spark session. It is this Spark session that is the heart of Spark during any execution. Loosely speaking, a notebook can be viewed as a Spark application, sharing a single Spark session and therefore sharing any data read by it.
