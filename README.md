# 📞 OptiConnect Solutions: Call Center Analytics Dashboard
An enterprise-grade, multi-page **Power BI Analytics Solution** designed to ingest, clean, and analyze 2,000+ raw operational customer service logs. This dashboard resolves critical executive questions regarding queue bottlenecks, agent performance distribution, and the direct impact of call handle times on customer experience (CX).

---

## 📈 Executive Core KPIs

### 📥 2K TOTAL CALLS
* **Data Context:** Comprehensive call volume baseline capturing all incoming customer touchpoints across five core product departments (Fridge, Television, Air Conditioner, Toaster, and Washing Machine).

### 📞 82.1% ANSWER RATE
* **Data Context:** Strong operational responsiveness threshold indicating that out of the incoming volume, 1,772 calls were successfully accepted by frontline support teams.

### ✅ 74.0% RESOLUTION RATE
* **Data Context:** Solid operational capability baseline demonstrating that nearly three-quarters of all incoming consumer complaints were completely resolved on first contact.

### ⏱️ 67 SECONDS AVERAGE SPEED OF ANSWER (ASA)
* **Data Context:** The true operational queue metric indicating the absolute mean wait time experienced by a customer before an agent picks up the phone.

### ⭐ 3.45 / 5.0 AVERAGE CSAT
* **Data Context:** Aggregated Customer Satisfaction rating establishing a highly dependable baseline of consumer sentiment across the entire call center floor.

---

## 🔍 Core Analytical Insights

### 1. Product Sector Volatility & Volume Drivers
* **Findings:** Analysis of the **Department Donut Chart** reveals that **Television (21.56%)** and **Air Conditioners (20.43%)** account for the absolute majority of incoming support queries. 
* **Business Value:** Identifying these heavy volume pillars enables management to dynamically shift staffing patterns during peak windows to mitigate customer frustration.

### 2. Standardized Agent Uniformity (The CSAT Cluster)
* **Findings:** By mapping an advanced **Multi-variable Scatter Plot** on Page 2, a highly uniform cluster was discovered. Every single agent operates at an optimal baseline of **1.0 talk time units** while maintaining a stable customer satisfaction band strictly between **3.38 and 3.54**.
* **Business Value:** This tight cluster mathematically proves that service delivery is highly standardized across the floor, showing that onboarding and script compliance measures are highly effective.

### 3. Queue Handling Efficiency vs. First Contact Resolution
* **Findings:** Cross-referencing individual metrics within the **Performance Matrix** shows that agent **Martha** holds the highest individual quality score at **3.54 CSAT** despite carrying a lower resolution rate (69.1%). Conversely, **Dan** manages an elite **78.0% Resolution Rate** with a **3.49 CSAT**.
* **Business Value:** This proves that text-book resolution rates are not the sole driver of customer happiness; call quality, empathy, and conversational tone play significant roles in building strong scores.

---

## 🛠️ Data Architecture & Tools Used

### 📊 Business Intelligence Layer: Microsoft Power BI Desktop
* **Multi-Page Layout:** Structured a seamless 2-page report separation split between high-level **Operational Overview (Page 1)** and deep-dive **Performance & Insights (Page 2)**.
* **Custom Format String Engine:** Programmed explicit visual type formatting overrides (`0" seconds"`) inside the report layer to gracefully anchor numeric data parameters next to time dimensions.
* **Advanced Visual Reporting:** Developed an interactive matrix table and custom scatter charts to correlate distinct metrics such as handle duration, queue wait times, and satisfaction distributions across the workforce.

### 🧮 Data Modeling & Advanced Calculations: DAX (Data Analysis Expressions)
* Engineered custom data modeling metrics using **DAX** to handle missing records and calculate exact operational averages across variables like call volume, speed of answer, and resolution success rates.

### 🧹 Extract, Transform, Load (ETL): Power Query Engine
* Implemented clean column parsing logic to transform incoming date strings into relational temporal timestamps.
* Structured data schema layouts to accurately handle empty records—such as unanswered calls lacking wait times or satisfaction inputs—preventing null values from distorting operational averages.
