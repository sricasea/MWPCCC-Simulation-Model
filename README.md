# MWPCCC Nonprofit Childcare Simulation Model

## Overview
This project is a full historical and operational simulation of the Mt. Washington Preschool and Child Care Center (MWPCCC), a small nonprofit childcare organization in Los Angeles. 

The simulation was built with invented but realistic data in collaboration with ChatGPT, using real-world operational structures and financial challenges as its inspiration.  
It is designed as the foundation for developing a comprehensive Power BI dashboard for the organization.

---

## Background
MWPCCC, like many childcare providers across Los Angeles, has faced increasing financial pressures in the wake of the Covid-19 pandemic, including decreased enrollment, rising inflation, and teacher shortages. While I cannot do anything about these large-scale societal shifts, MWPCCC's reaction to them is limited by the information available to its governing bodies, i.e. the Executive Director and the volunteer Board.
In particular, two major pain points were identified:

1. **The board struggles to fully understand the operational and financial needs of the business**, limiting their ability to provide strategic support.
2. **Board members expressed concerns that financial data had not been fully disclosed**, hindering collaborative oversight and decision-making.

This project addresses both pain points by laying the groundwork for profound data visibility:  
a dynamic, detailed model of MWPCCC’s historical operations and finances that can eventually support future planning, scenario modeling, and transparent board engagement.

---

## Project Structure
The simulation covers:

- **Enrollment and Tuition**: Children enrollment, tuition rates, subsidies, invoices, payments.
- **Staffing and Payroll**: Teacher hiring, attendance, FTE tracking, gross pay, taxes, benefits.
- **Center Operations**: Fixed expenses, event-based payments, liabilities, maintenance.
- **Historical Layers**: 
  - Founding Era (1997–2005)
  - Growth Era (2006–2015)
  - Post-COVID Era (2016–2025)

---

## Key Files and Folders
| Folder/File | Purpose |
|:---|:---|
| `data/DIM_*.csv` | Dimension tables (Children, Teachers, Classrooms, Subsidies, etc.) |
| `data/FACT_*.csv` | Fact tables (Invoices, Attendance, Payroll, Payments, etc.) |
| `data/historical_expenses/` | Invented historical expenses and liabilities |
| `notebooks/` | (Future) Analysis, Power BI integration |
| `visuals/` | (Future) Dashboard screenshots, sample reports |
| `README_data.md` | Detailed data dictionary (future enhancement) |

---

## Future Enhancements
- Model PTO accruals and usage
- Model overtime and irregular shifts
- Integrate real-world payment processors (Tuition Express)
- Layer in real audited financial data
- Build full Power BI dashboards from this simulation

---

## About
This project was built as part of Geneva Burleigh’s transition into data analysis and strategic nonprofit operations,  
blending operational knowledge with a commitment to real, transparent, collaborative leadership.

