# Airline_Crew_Scheduling Ass.
# ✈️ Airline Crew Scheduling System

The **Airline Crew Scheduling System** is a data-driven project designed to analyze airline operations and schedule crew members efficiently.  
It uses real-world airline dataset fields such as passenger information, airports, flights, pilots, and flight status to generate insights and run SQL/Spark queries.

---

## 📌 Project Overview

This project focuses on:
- Processing airline datasets using **Scala + Spark SQL** in Databricks  
- Writing **easy, moderate, and advanced SQL queries**  
- Performing data cleaning, transformation, and analytics  
- Understanding operational patterns related to crew scheduling  
- Preparing queries required for academic or industry-grade projects

---

## 📂 Dataset Details

The dataset includes the following major columns:

- Passenger ID  
- First Name, Last Name  
- Gender, Age, Nationality  
- Airport Name  
- Airport Country Code  
- Country Name  
- Airport Continent  
- Continents  
- Departure Date  
- Arrival Airport  
- Pilot Name  
- Flight Status  

> *(Dataset source: Airline Dataset Updated – v2 from Kaggle)*

---

## 🛠️ Technologies Used

- **Apache Spark (Spark SQL)**
- **Scala**
- **Databricks Notebook**
- **CSV / DataFrame Processing**

---
2. Upload Code & Dataset to Databricks

Upload the dataset to /FileStore/tables/

Open the Scala/Spark SQL notebook

3. Load the Dataset

Example:

val df = spark.read.option("header", "true").csv("/FileStore/tables/Airline_Dataset_Updated___v2.csv")
df.createOrReplaceTempView("airline")

4. Run Queries

Use:

SELECT * FROM airline;


or advanced queries depending on your use case.

📘 Project Contents

This repository includes:

✔️ Spark SQL queries (Easy, Moderate, Advanced)

✔️ Scala DataFrame API code

✔️ Crew-related analytics (Pilots, flights, statuses, airports)

✔️ Clean and documented notebook

✔️ README documentation

📊 Sample Analyses Performed

Find pilot-wise total flights

Analyze delays or cancelled flights

Analyze passenger demographics

Country-wise or continent-wise flight distribution

Scheduling insights for better crew assignment

🤝 Contribution

Feel free to submit:

Improvements

Bug fixes

Additional analytics

New features

Please open an issue before submitting major changes.

👨‍💻 Author

Ashu
Roll Number: 2301201105
