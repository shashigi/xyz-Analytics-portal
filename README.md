#  XYZ Retail Analytics Portal

## 1. Project Overview
The **XYZ Retail Analytics Portal** is an end-to-end business intelligence solution developed as part of an analytics case study.  
The objective of this project is to provide **clear, actionable insights** into **sales performance** and **quality / operational metrics** for XYZ retail outlets across Bangalore.

The solution uses **Tableau dashboards** for analytics and a **web-based portal** to make insights easily accessible through a browser without requiring Tableau Desktop.

---

## 2. Tools & Technologies
- **Tableau Desktop** – Data modeling & dashboard creation  
- **Tableau Public** – Dashboard hosting and sharing  
- **HTML5 & CSS3** – Web application development  
- **GitHub** – Source code version control  
- **GitHub Pages** (optional) – Web hosting

---

## 3. Data Sources
- **xyz_Sales.xlsx**  
  Contains monthly sales metrics such as revenue, profit, transactions, average bill value, and outlet performance.

- **xyz_Quality.xlsx**  
  Contains operational and quality metrics including defect rate, return rate, complaints, compliance score, and fulfillment accuracy.

---

## 4. Dashboards Developed

### Sales Performance Dashboard
- Total Sales & Net Profit KPIs  
- Profit Margin & Average Bill Value  
- Monthly sales trends  
- Outlet-wise sales comparison  
- Interactive filters (Outlet, Year)

### Quality & Operations Dashboard
- Defect Rate & Return Rate  
- Customer Complaints  
- Fulfillment Accuracy  
- Compliance & Cleanliness Scores  
- Outlet-wise quality comparison  

---

## 5. Design Choices
- Used **Tableau relationships** instead of physical joins to ensure correct aggregations.
- Followed a **KPI → Trend → Breakdown** layout for executive readability.
- Applied consistent **branding, colors, and typography** across dashboards.
- Minimized visual clutter to improve storytelling and usability.
- Embedded dashboards using **iframe** for simple and reliable web integration.

---

## 6. Assumptions
- Data provided is accurate and pre-validated.
- Metrics are aggregated at a monthly outlet level.
- All retail outlets operate under comparable business conditions.
- Tableau dashboards are set to **Public** visibility for embedding.

---

## 7. Web Application
The web application acts as a lightweight analytics portal and includes:
- **Home Page** – Overview of the XYZ Analytics Portal  
- **Sales Dashboard Page** – Embedded Sales Tableau dashboard  
- **Quality Dashboard Page** – Embedded Quality Tableau dashboard  
- **About Page** – Project summary and assumptions  

---

## 8. How to Run the Web Application

### Option 1: Run Locally
1. Download or clone the repository.
2. Maintain the folder structure:
xyz-analytics-portal/
├── index.html
├── sales.html
├── quality.html
├── about.html
├── styles.css
└── assets/
3. Open `index.html` in any modern browser (Chrome / Edge).

---

### Option 2: Run Using GitHub Pages
1. Upload all project files to a GitHub repository.
2. Go to **Settings → Pages**.
3. Select the main branch and save.
4. Access the application using the generated GitHub Pages URL.

---

## 9. Tableau Public Links
- **Sales Dashboard:** (https://public.tableau.com/views/SalesDashboard_Shashi/SalesDashboard?:showVizHome=no)  
- **Quality Dashboard:** (https://public.tableau.com/views/SalesDashboard_Shashi/QualityDashboard?:showVizHome=no) 

---

## 10. Conclusion
This project demonstrates:
- Strong Tableau dashboarding skills
- Data modeling and analytical thinking
- Business-focused visualization design
- Integration of BI tools with a web interface
- End-to-end analytics solution delivery

---

## Author
**Shashi Kala**  
BI / Analytics Developer
