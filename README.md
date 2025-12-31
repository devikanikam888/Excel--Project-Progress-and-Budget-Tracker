# Project Management Dashboard & Gantt Chart (Excel)

## Quick Overview
- End-to-end project tracking file built in Excel
- Designed to give a **one-glance understanding** of project status
- Fully automated using basic Excel formulas and validations
- Future-proofed so updates to raw data automatically reflect everywhere

---

## Project Purpose
- Centralise task tracking, timelines, and KPIs in one file
- Reduce manual updates and repetitive formatting
- Make project progress easy to understand for any stakeholder
- Enable fast updates without breaking formulas or visuals

---

## Key Features at a Glance
- Automated task tracking
- Dynamic dashboard with KPIs
- Interactive Gantt chart
- Data validation for controlled inputs
- Clean and intuitive user interface
- Scalable structure for future projects

---

## File Structure
- **Tasks Sheet**
  - All task-level inputs
  - Single source of truth for the entire file
- **Dashboard Sheet**
  - Visual summary of project health
  - KPI indicators and charts
- **Gantt Chart Sheet**
  - Timeline-based task visualisation
  - Auto-updates based on task dates

---

## Automation & Future-Proofing
- Changes made only in input cells
- No need to touch formulas once set
- Tables expand automatically with new entries
- Dashboard and Gantt chart update in real time
- Consistent structure prevents accidental errors

---

## Dashboard Design & Logic
- Built to summarise the project in one view
- KPI shapes used for quick status checks
- KPI values calculated automatically
- Bar charts used for clear visual comparison

### Functions & Tools Used
- `COUNTIF` for task status calculations
- `AND` function for conditional logic
- Data Validation to:
  - Control task status inputs
  - Speed up updates
  - Maintain data consistency
- Structured references to support scalability

### Dashboard Walkthrough Video
<!-- Replace the src link with your actual video file or GitHub-hosted link -->
<video src="dashboard-demo.mp4" controls width="100%"></video>

---

## Gantt Chart Design & Logic
- Visual timeline representation of tasks
- Fully driven by task start and end dates
- No manual bar adjustments required

### Functions & Tools Used
- `IF` function to control bar visibility
- Conditional formatting to:
  - Create dynamic task bars
  - Reflect real-time date changes
- Clean layout to avoid visual clutter

### Gantt Chart Walkthrough Video
<!-- Replace the src link with your actual video file or GitHub-hosted link -->
<video src="gantt-chart-demo.mp4" controls width="100%"></video>

---

## Analysis & Insights
- *(Section intentionally left blank for future additions)*

---

## How to Use the File
- Update tasks only in the designated input areas
- Use dropdowns for task status and categories
- Avoid editing formula cells
- Add new tasks below existing ones — visuals update automatically

---

## Tools & Skills Demonstrated
- Excel automation using basic formulas
- Dashboard design principles
- Gantt chart logic without VBA
- Data validation for usability
- UI-focused spreadsheet design
- Practical project management thinking

---

## Future Improvements
- Add risk and dependency tracking
- Include milestone indicators
- Enhance KPI logic with weighted metrics
- Extend dashboard for multi-project tracking
