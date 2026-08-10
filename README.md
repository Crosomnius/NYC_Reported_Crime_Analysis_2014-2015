# NYC Reported Crime Analytics Dashboard (2014–2015)

Power BI dashboard analyzing NYPD reported crime complaints across New York City from 2014 to 2015 — covering monthly crime trends, incident locations, top offense types, and crime severity categories on an interactive dark-themed page.

---

### File

* **`NYC 2014 2015 Reported Crime Analysis.pbix`** — open with Power BI Desktop.

---

### Data Model

* **`NYPD_Complaint_Data_Historic1`** — main fact table containing reported crime incidents, timestamps, locations, borough names, and offense descriptions.
* **`Date Hierarchy`** — date table hierarchy used to break down incidents by year and month.

---

### What's on the Dashboard

**1. KPI Cards (Top):**
* **Total Incidents** — total count of reported crimes in the dataset (958,938).
* **% Completed Crime** — percentage of reported complaints successfully completed (98.22%).
* **Top Offense** — most frequent crime category recorded (Petit Larceny).

**2. Monthly Crime Trend by Category (Center Left):**
* Clustered Column Chart comparing month-by-month crime counts between 2014 and 2015.

**3. Top 10 Offense Types (Bottom Left):**
* Horizontal Bar Chart displaying the 10 most common offenses, led by Petit Larceny, Harassment 2, and Assault 3.

**4. Incidents by Premises Percentage (Bottom Right):**
* Donut Chart showing the distribution of crime locations (Street, Residence - Apt. House, Residence - House, etc.).
---

### Filters & Interactivity

* **Boroughs Dropdown (Top Left):** filters all charts by specific NYC boroughs (*Brooklyn, Manhattan, Queens, Bronx, Staten Island*).
* **Complaint Date Slicer:** date range slider and picker to isolate specific timeframes between `01/01/2014` and `31/12/2015`.
* **Crime Category Buttons:** quick buttons to filter data by severity (*Felony*, *Misdemeanor*, *Violation*).
* **Reset Button (Bottom Left):** custom bookmark action to clear all applied filters in one click.

---

### How to Use

1. Open `NYC 2014 2015 Reported Crime Analysis.pbix` in **Power BI Desktop**.
2. Use the **Boroughs**, **Date Range**, or **Crime Category** slicers on the left sidebar to drill down into specific data segments.
3. Hover over chart elements to view exact numbers and detailed tooltips.
4. Click the **Bookmark / Reset Button** at the bottom left to restore all filters back to the default view.
