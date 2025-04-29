# MWPCCC Simulation — Data Documentation

This document provides an overview of the datasets used to build the MWPCCC nonprofit childcare financial and operational simulation.  
Each file is categorized as a Dimension or Fact.

---

## Dimension Tables
| Filename | Description |
|:---|:---|
| `DIM_Children.csv` | Basic child information including Center, RateType, and Funding sources |
| `DIM_Classrooms.csv` | Classroom metadata including ratios and maximum capacities |
| `DIM_Centers.csv` | Center details and operational timelines |
| `DIM_Teachers.csv` | Staff/teacher records including start dates and roles |
| `DIM_SubsidyRules.csv` | Rules for applying subsidies, including limits and contribution types |
| `DIM_Wages.csv` | Wage table by year, role, and educational tier |
| `DIM_RateRules.csv` | Defines tuition structure by Center, Room, and Schedule |
| `DIM_RateValues.csv` | Defines tuition amounts over time, including special discounts |
| `DIM_CorporateDonors.csv` | Specific information about Corporate Donors, including contact info and area of focus |
| `DIM_FeesAndCharges.csv` | Defines fees and charges over time |
| `DIM_Fundraisers.csv` | Fundraiser details, including profitability |
| `DIM_HolidaysAndClosures.csv` | Defines days the centers were closed for business |
| `DIM_IndividualDonors.csv` | Precise information about individual donors and student family connections |
| `DIM_LicensingRules.csv` | Defines the licensing rules governing classroom capacity and matriculation |
| `DIM_MasterDonorList.csv` | Broad details regarding all donors |

---

## Fact Tables
| Filename | Description |
|:---|:---|
| `FACT_EnrollmentHistory.csv` | Tracks children's movements across classrooms and tuition rate changes |
| `FACT_Attendance.csv` | Daily child attendance records with absence types and reasons |
| `FACT_Invoices.csv` | Tuition billing amounts, subsidy calculations, and family obligations |
| `FACT_TuitionPayments.csv` | Tuition payment history by family or agency payer |
| `FACT_Hiring.csv` | Teacher hiring events, promotions, and departures |
| `FACT_TeacherAttendance.csv` | Daily teacher clock-in/clock-out times and shift details |
| `FACT_Payroll.csv` | Monthly gross pay, benefits, taxes, and net pay per staff |
| `FACT_FTE_Summary.csv` | Child Full-Time Enrollment (FTE) totals by center and classroom |
| `FACT_FTE_Staffing_Needs.csv` | Calculated staffing needs based on enrollment and ratios |
| `FACT_FixedExpenses.csv` | Fixed operating costs from 1997 to 2025 |
| `FACT_Payments.csv` | Situational costs from 1997 to 2025 |
| `FACT_Liabilities.csv` | Loans and fines from 1997 to 2025 |
| `FACT_OtherRevenue.csv` | Currently only donation revenue, but in future will include grants and merchandise revenue |
| `FACT_Waitlist.csv` | Details children currently on the waitlist |

---

# Notes
- All data are invented but modeled to be realistic for nonprofit childcare operations.
- Timeline covers Founding Era (1997–2005), Growth Era (2006–2015), and Post-COVID Era (2016–2025).
- Data is designed for dashboarding, financial modeling, and future scenario planning.

---
