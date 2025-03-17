# HR Dashboard – Power BI  (Atliq Technologies)

## Overview  
This Power BI dashboard provides insights into employee attendance patterns over **April, May, and June 2022**.  
The dataset comes from **Atliq Technologies**, a **software and data solutions company in India**.  
It includes **presence %, work-from-home (WFH) %, and sick leave (SL) %** visualisations, along with detailed daily attendance tracking.  

## Data Cleaning & Transformation  
- The dataset consisted of **three sheets (April, May, June 2022)**, each containing daily attendance records.  
- The original data had **dates as column headers (e.g., 1 April 2022, 2 April 2022, etc.)**, requiring **transposition**.  
- A **template transformation** was created for April and applied to May and June using a **Power Query function and parameter**.  
- After applying transformations, the data was verified for accuracy.  

## DAX Calculations  
Several **DAX measures and calculated columns** were created, including:  
- **Total Working Days** (Excludes weekends and holidays).  
- **Work-From-Home (WFH) Count**.  
- **WFH %** = WFH count / Present days.  
- **Sick Leave (SL) %** = SL count / Total working days.  
- **Present Days** = Count of employees marked **P** or **WFH**.  
- **Presence %** = Present days / Total working days.  
- **WFH Count & SL Count** in calculated columns.  

## Dashboard Features  
The dashboard includes the following visualisations:  
1. **Presence %, WFH %, and SL %** for each employee.  
2. **Detailed attendance sheet** for daily granularity.  
3. **Presence % trend** over three months.  
4. **WFH % trend** over three months.  
5. **SL % trend** over three months.  
6. **WFH, Presence %, and SL % by weekday** (to analyse patterns).  
7. **Month selector (April, May, June) for filtering insights**.  

## Key Insights & Business Recommendations  

### 1. Overall Attendance is Strong  
- The **Presence % is 91.83%**, indicating that most employees are attending work consistently.  
- This suggests a **strong work culture** and **good employee engagement**.  

### 2. Work-From-Home (WFH) Accounts for 10% of Present Days  
- Remote work is a small but notable portion of total attendance.  
- This shows a **hybrid work model**, which can be further optimised for productivity.  

### 3. WFH Peaks on Thursdays & Fridays  
- Employees prefer WFH on **Thursdays and Fridays**.  
- **Possible Reasons:**  
  - People may prefer to start the weekend early or avoid Friday traffic.  
  - Some employees might use WFH for better focus before the weekend.  
- **Business Recommendation:**  
  - Management could **plan team-building activities in the middle of the week** (Tuesday/Wednesday), as more employees are physically present.  
  - **Capacity planning**: If the company has 100 employees but WFH trends show lower occupancy on Fridays, they might not need 100 desks daily—**hot desking policies** could be introduced to optimise space.  

### 4. Declining Presence % Towards June  
- There is a noticeable **drop in attendance in June**.  
- **Possible Reasons:**  
  - Mid-year burnout or fatigue.  
  - Start of summer in India, with some employees taking leave.  
  - Exam season for children, leading to employees taking time off.  
- **Business Recommendation:**  
  - Conduct **employee engagement surveys** to understand the cause.  
  - Offer **flexible work options** during peak leave seasons.  

### 5. Increasing WFH % Towards June  
- **WFH % is rising** in June, which correlates with declining in-office presence.  
- **Possible Reasons:**  
  - Employees opting for remote work due to summer heat.  
  - Rising preference for flexibility.  
- **Business Recommendation:**  
  - If this trend continues, companies can **formalise hybrid work policies** instead of ad-hoc approvals.  

### 6. Sick Leave (SL %) is Increasing Towards June  
- SL% shows a **gradual increase** over time.  
- **Possible Reasons:**  
  - Seasonal illnesses (heat-related issues, monsoon-related sickness).  
  - Work-related fatigue or mental health burnout.  
- **Business Recommendation:**  
  - Consider **wellness programs** or health initiatives to support employees.  
  - Allow preventive WFH options during monsoon season to reduce sick leaves.  

### 7. Sick Leave is Highest on Mondays  
- **Monday shows the highest SL %** across all three months.  
- **Possible Reasons:**  
  - Employees might be **extending their weekends** by taking leave.  
  - Genuine exhaustion from weekend activities or travel.  
- **Business Recommendation:**  
  - HR can **monitor recurring Monday absences** to ensure fairness.  
  - Consider allowing **optional WFH Mondays** to improve work-life balance.
 
  ## Additional Notes  
- The dataset is based on **Atliq Technologies, an India-based software and data solutions company**.  
- Cultural and seasonal factors (summer heat, monsoon, school schedules) have been considered in the insights.  
- Future improvements could include **adding more months of data** to observe long-term trends.  

 
## Files Included  
This repository contains the following files:  
1. **Excel File** – The raw data used for creating the HR Dashboard.  
2. **PBIX File** – The Power BI report that contains the data transformations, DAX calculations, and visualizations.  
3. **Dashboard PDF** – A static view of the HR Dashboard for quick reference.  

Ensure you have **Power BI Desktop** installed to open the PBIX file, and feel free to explore the dashboard.

---


---

