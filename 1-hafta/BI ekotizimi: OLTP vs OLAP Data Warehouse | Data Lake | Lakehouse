 **BI ekotizimi** elementlari — *OLTP vs OLAP*, *Data Warehouse*, *Data Lake*, *Lakehouse* 
---

# 🔷 **1. OLTP vs OLAP — Farqi**

## **OLTP — Online Transaction Processing**

📌 **Nima uchun ishlatiladi?**
Kundalik operatsiyalarni bajarish: insert, update, delete.

📌 **Xususiyatlari:**

* Tezkor yozuv/yangilash
* Kichik, aniq tranzaksiyalar
* Ma’lumot real vaqtda
* Normalizatsiya qilingan (ko‘p bo‘lingan jadvallar)
* Masalan: bank operatsiyalari, e-commerce buyurtmalari

📌 **Misol:**
📱 Mobil bankingda pul o‘tkazish

---

## **OLAP — Online Analytical Processing**

📌 **Nima uchun ishlatiladi?**
Tahlil, BI dashboardlar, tarixiy ma’lumotlar.

📌 **Xususiyatlari:**

* Katta hajmdagi o‘qish (read-heavy)
* Murakkab analitik querylar
* Denormalizatsiya qilingan jadvallar
* Tarixiy ma’lumot saqlanadi
* Masalan: Power BI, Tableau, Looker hisobotlari

📌 **Misol:**
📊 Oylik sotuvlar trendi, KPI dashboard

---

# 🔷 **2. Data Warehouse (DW)**

📌 **Ta’rifi:**
Analitika uchun maxsus tuzilgan markazlashtirilgan ma’lumot ombori.

📌 **Xususiyatlari:**

* Strukturali ma’lumot
* ETL yoki ELT orqali tozalanadi
* Yillik, oylik tarixiy ma’lumot
* Denormalizatsiya (Star Schema / Snowflake)
* BI vositalar ulanishi uchun eng qulay

📌 **Qayerda ishlatiladi?**
Power BI, Reporting, Dashboard, KPI, Data Science.

📌 **Misol:**
`Fact_Sales`, `Dim_Product`, `Dim_Customer`, `Dim_Date` jadvallari.

---

# 🔷 **3. Data Lake**

📌 **Ta’rifi:**
Har qanday turdagi ma’lumotni (raw) saqlash uchun katta ombor:

* Structured
* Semi-structured
* Unstructured (video, audio, log)

📌 **Xususiyatlari:**

* Juda arzon saqlash
* Transformatsiya yo‘q (Raw Zone)
* Data scientistlar uchun mos
* Hadoop / Cloud Storage

📌 **Misol:**
Log fayllar, JSON, IoT sensor ma’lumotlari, CSV, video

---

# 🔷 **4. Lakehouse (Eng zamonaviy)**

📌 **Ta’rifi:**
**Data Warehouse + Data Lake** imkoniyatlarini birlashtirgan arxitektura.
(Microsoft Fabric, Databricks, Snowflake)

📌 **Xususiyatlari:**

* BI uchun strukturali ma’lumot
* Raw ma’lumotlar uchun Data Lake
* Delta format (ACID transaction)
* Real-time processing
* Bitta joyda tahlil + storage

📌 **Asosiy Afzallik:**
🔹 ETL + Storage + Analytics → **hammasi bitta platformada**
🔹 Data Warehouse kabi tezkor
🔹 Data Lake kabi elastik va arzon

📌 **Misol:**
Fabric Lakehouse → Bronze (raw), Silver (clean), Gold (analytics)

---

# 📌 Yakuniy qisqa ta’rif (super qisqa)

| Texnologiya        | Nima qiladi?               | Qaysi ma'lumot?              |
| ------------------ | -------------------------- | ---------------------------- |
| **OLTP**           | Tranzaksiyalar             | Real-time, operatsion        |
| **OLAP**           | Analitika                  | Tarixiy, katta hajm          |
| **Data Warehouse** | Strukturali analitik ombor | Tozalangan, model qilingan   |
| **Data Lake**      | Har qanday ma’lumot        | Raw (tozalanmagan)           |
| **Lakehouse**      | Warehouse + Lake           | Bitta joyda tahlil va xotira |

---
