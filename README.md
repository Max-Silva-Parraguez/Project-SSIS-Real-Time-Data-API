# 🚀 PROJECT: Real-Time Data Integration from an API to SQL Server using SSIS

## 📌 Description
This project aims to extract real-time weather data from the OpenWeatherMap API and load it into an SQL Server database using SQL Server Integration Services (SSIS). An automated ETL process is implemented with a scheduled task in SQL Server Agent for periodic execution.

---

## ⚡ **Project Steps**

### **1. Obtaining an API Key from OpenWeatherMap**
- Create an account on OpenWeatherMap and generate an API Key to retrieve the data. Desde: [https://openweathermap.org/api](https://openweathermap.org/api) 

### **2. Creating a Project in SSIS**
- Create the project **"REAL-TIME DATA INTEGRATION"** and the SSIS package **"Integrating Real-Time Data with SSIS"**.

### **3. Configuring Variables in SSIS**
- Define variables in SSIS to store data such as APIKey, city, temperature, humidity, pressure, wind speed, and weather description.

### **4. Configuring the Script Task in SSIS**
- Use a "Script Task" in SSIS and program in **C#** to retrieve data from the API.

### **5. Editing the Script in C#**
- Install the **Newtonsoft.Json** library and write the **C#** code to extract data from the API response JSON and store it in SSIS variables.

### **6. Creating a Table in SQL Server**
- Create a database and a table in SQL Server to store the extracted information.

### **7. Creating an Execute SQL Task**
- Use "Execute SQL Task" in SSIS to insert data into the SQL Server table.

### **8. Handling Errors**
- Fixed an execution error by registering the **Newtonsoft.Json** library in the **GAC (Global Assembly Cache)**.

### **9. Running the Project**
- Execute the SSIS workflow and verify that the data is inserted into the database.

### **10. Deploying the Project in SQL Server Integration Services (SSIS)**
- Deploy the project in SQL Server for automatic execution.

### **11. Automating Execution with SQL Server Agent**
- Create a scheduled task in **SQL Server Agent** to execute the process every **30 seconds**.

---

## 📊 **Technologies Used**  
✅ **CSV como fuente de datos**  
✅ **SQL Server**  
✅ **SQL Server Agent**  
✅ **Newtonsoft.Json)** library  
✅ **SSIS (SQL Server Integration Services)** 

---

## 📥 **Project Requirements**

- **SQL Server** with **SQL Server Integration Services (SSIS)** installed.
- **Visual Studio** with the SSIS tools package.
- **Newtonsoft.Json** (library to handle JSON from the API in C#).
- **OpenWeatherMap account** to obtain an API Key.

---

## ⚙ **How to Run the Project**

1. Obtain an API Key from OpenWeatherMap.
2. Configure SSIS variables with the API Key and desired cities.
3. Edit and execute the **C# Script** inside the SSIS Script Task.
4. Create the database and table in SQL Server.
5. Manually run the SSIS package to verify data insertion.
6. Deploy the package in **Integration Services Catalogs** in SQL Server.
7. Configure and execute the scheduled task in **SQL Server Agent**.

---

## 📊 **Conclusion**

This project demonstrates how to extract real-time data from an API and store it in an SQL Server database using SSIS, with an automated execution every 30 seconds via SQL Server Agent.

---

### 📌 Notes:
The complete and detailed project process can be found in the PDF: Real-Time Data from API to SQL SERVER using SSIS.pdf

---

**Author:** Eng. Máximo Silva Parraguez


