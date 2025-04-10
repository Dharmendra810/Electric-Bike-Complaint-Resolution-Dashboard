
# 🔧 Electric Bike Complaint Resolution Dashboard

This repository showcases an interactive **Google Looker Studio Dashboard** created for monitoring and evaluating the end-to-end resolution process of complaints raised by riders/customers of electric bikes.

The dashboard is designed using data sourced from Google Sheets, capturing key metrics for **Advisors**, **Technicians**, **Hubs**, and **Vehicle Models** (specifically *Sun Mobility*).

---

## 📊 Dashboard Overview

The dashboard is organized into multiple pages to focus on specific areas of complaint resolution:

1. **Advisor's Productivity Dashboard**
   - Tickets handled, average TAT, user rating, workdays, SLA performance.

2. **Technician's Productivity Dashboard**
   - Work orders completed, types of repairs, locations served, maintenance cost.

3. **Hub Summary Dashboard**
   - Complaints grouped by cluster and hub, performance of each zone.

4. **Sun Mobility Vehicle Dashboard**
   - Work done specifically for the *Sun Mobility* model of electric bikes.

5. **Escalation Dashboard**
   - Overview of escalated complaints, resolution time, and responsible parties.

6. **Overall Summary**
   - High-level view combining advisor, technician, and escalation performance.

---

## 📁 Sample Row Data (Google Sheets)

The dashboard fetches its data from Google Sheets with fields like:

| Ticket_Id | Cust_Id | Ticket_Created_Time | Status          | Module | Mechanic_Name     | MaintenanceCost | Rating | Cluster Name | Hub_Name           |
|-----------|---------|----------------------|------------------|--------|--------------------|------------------|--------|---------------|---------------------|
| 768666    | 661661  | 2024-06-01 23:56:39  | TC Under SLA     | Rental | Joginder - Mundka | 86               | -      | Delhi, NCR    | Mundka (West Delhi) |

Additional fields include:
- Ticket Type (Mechanic/Self)
- Remarks by Advisor & Technician
- SLA Calculation (Closed within/above SLA)
- Time Taken for resolution
- Work Hours & Days
- Ratings & User Comments

---

## 📌 Key Visuals and Scorecards

The dashboard includes essential **scorecards**, **charts**, and **filters** for performance tracking:

### 🔍 Filters (Available on all pages):
- **Date Range Selector**
- **Cluster, Hub, Advisor Name, Technician Name**

### 📈 Scorecards and Metrics:
- **Total Tickets**
  - Segregated into `Mechanic Required` and `Self-Resolved` complaints.
- **Average Tickets per Day**
- **Ticket Ratings** (User feedback)
- **TAT Metrics (Turnaround Time)**
  - Average TAT
  - Tickets Closed Within SLA / Above SLA
- **Work Days** per Advisor/Technician

These visuals are rendered via:
- Scorecards with dynamic color indicators
- Charts (bar/line) for comparisons
- Tables for drill-down
- Interactivity with filters

---

## 📷 Screenshots (Included)

The following dashboard screenshots are included in this repo:

- `Advisor's Productivity Dashboard`
- `Technician's Productivity Dashboard`
- `Hub Summary Dashboard`
- `Sunmobility Dashboard`
- `Escalation Dashboard`
- `Overall Summary`

---

## 📌 Purpose

This dashboard helps stakeholders:
- Monitor complaint resolution performance
- Identify improvement areas for advisors and technicians
- Compare hub-wise service efficiency
- Track escalations and ensure SLA compliance
- Gain real-time insights via dynamic filters

---

## 👨‍💻 Tech Stack

- **Google Looker Studio** (Visualization)
- **Google Sheets** (Data Source)
- **GitHub** (Documentation & Sharing)

---

## 📬 Feedback & Suggestions

Feel free to create an issue or pull request for suggestions or enhancements.

---

> Built with 💡 to bring clarity to electric vehicle complaint handling and improve operational performance.
