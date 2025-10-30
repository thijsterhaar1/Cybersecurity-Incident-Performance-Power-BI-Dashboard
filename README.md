# Mini Case – Cybersecurity Incident Performance

### 🎯 Objective
Analyze the operational performance of a SOC (Security Operations Center) team to evaluate response and resolution times, and SLA compliance.

---

### 📊 Dashboard Deliverables
Built in **Power BI** with the following insights:
- **MTTA (Mean Time to Acknowledge)**
- **MTTR (Mean Time to Resolve)**
- **SLA Breach %**
- Incident count per **severity**
- Performance breakdown by **asset** and **team**

---

### 📊 Key Insights

- SOC team acknowledges incidents quickly (MTTA ~3 hours), but resolution time is significantly higher (~38 hours).
- Over **50% of incidents breach SLA**, indicating capacity or process improvement needs.
- Critical incidents occur most frequently, increasing operational workload and urgency.
- Database and Firewall assets show the highest SLA breach rates → priority areas for optimization.
- Team “Charlie” shows longer MTTR → potential training or load-balancing opportunity.

---

### ⚙️ Power BI Features Used
- Power Query transformations (Trim/Clean, calculated time columns)
- DAX measures:
  - `MTTA_hours`
  - `MTTR_hours`
  - `SLA_Breach_%`
- Conditional formatting (SLA Breach %)
- Interactive slicers (Severity, Team)

---

### 🖼️ Screenshots
Located in `/screenshots_cyber`:
1. Power Query applied steps  
2. DAX measures in Power BI  
3. Final dashboard page

---

### 🗂️ Files
| File | Description |
|------|--------------|
| `cyber_incidents.csv` | Dataset used |
| `cyber_incidents_dashboard.pbix` | Power BI dashboard |
| `/screenshots_cyber` | Screenshot folder |
| `README.md` | Project summary |

---

**Tools:** Power BI, DAX, Power Query  
**Author:** Thijs ter Haar
