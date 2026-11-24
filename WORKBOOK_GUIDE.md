# Workbook Guide — Skyline Residency, Tower A

## 1. Purpose

`Excel/Skyline_Residency_HighRise_Planning_CostControl_Monitoring.xlsx` is a linked Excel model for an illustrative high-rise residential construction planning and project-controls case study. It demonstrates how project information, quantity take-off, BOQ, schedule, planned value, progress/cost monitoring, procurement, quality, safety and risks can be organized in one workbook.

**Important:** The building and all quantities, rates, budget values, progress, actual costs, test results, safety records and risk scores are assumed academic inputs. They are not live project data, an approved estimate or construction instructions. See `PROJECT_BASIS_AND_LIMITATIONS.md` and the project report before interpreting the outputs.

## 2. Workbook structure

The workbook contains 14 worksheets:

| Worksheet | Purpose | Typical use |
|---|---|---|
| `Project_Info` | Main project parameters, configuration and reporting assumptions | Review scenario inputs and status date first |
| `Dashboard` | Summary KPIs and monitoring view | Start here for a high-level view of the scenario |
| `QTO` | Quantity take-off inputs and calculations | Review assumed element quantities and units |
| `BOQ` | Work-package cost estimate | Review item descriptions, units, quantities, rates and amounts |
| `Schedule` | WBS, durations, logic, dates and critical-path/Gantt information | Review activity sequence, dependencies and milestones |
| `PV_Cashflow` | Time-phased planned value / cash-flow baseline | Review monthly planned expenditure and cumulative PV |
| `Budget_vs_Actual` | Cost-head budget, earned value and actual cost comparison | Identify cost-head variances and forecast pressure |
| `EVM` | Earned Value Management calculations | Review PV, EV, AC, SV, CV, SPI, CPI, EAC, ETC, VAC and TCPI |
| `Material_Plan` | Material requirement and procurement planning | Review quantities, lead times, inspection and storage controls |
| `Steel_Recon` | Theoretical-versus-issued steel reconciliation | Review floor/element-wise variance and tolerance assumptions |
| `RA_Bills` | Contractor running-account bill tracking | Review bill quantities, deductions, retention and payment status fields |
| `Quality_Log` | Quality inspection and test register | Review inspection stages, acceptance references and records |
| `Safety_Log` | Safety observations and indicators | Review illustrative safety monitoring fields |
| `Risk_Register` | Project risk assessment and response register | Review probability, impact, score, mitigation and ownership |

## 3. Suggested review sequence

1. Open `Project_Info` and confirm the assumed tower configuration and status date.
2. Open `Dashboard` to understand the model's headline indicators.
3. Review `QTO` and `BOQ` to understand the quantities and cost build-up.
4. Review `Schedule` and `PV_Cashflow` for sequencing, dependencies, baseline dates and planned expenditure.
5. Review `EVM` and `Budget_vs_Actual` for the Month 17 performance scenario.
6. Review `Material_Plan`, `Steel_Recon`, `RA_Bills`, `Quality_Log` and `Safety_Log` for execution-control registers.
7. Finish with `Risk_Register` to review the illustrative risks and mitigation ownership.

## 4. Input and formula discipline

- Save a separate working copy before changing any assumptions.
- Identify designated input cells and formula cells before editing. The model uses a visual distinction between inputs and calculations; do not overwrite formula cells.
- Change one assumption at a time and check the downstream effects on BOQ totals, schedule dates, PV, EVM and dashboard outputs.
- Keep units consistent (for example, m³, m², MT, days, weeks, ₹ and ₹ crore).
- Enter progress as a percentage using the format expected by the relevant input cell.
- Keep the reporting cut-off date consistent across the progress, cost and EVM sheets.
- Recalculate the workbook in Excel after edits and review the affected sheets before relying on an output.
- Record the source of every replacement quantity, rate, progress value or cost (drawing number/revision, measurement sheet, quotation, bill, test record or site report).

## 5. Key project-control concepts represented

- **BOQ:** Work-item quantities multiplied by corresponding rates, organized by work package.
- **WBS and CPM:** Activities are organized with predecessor logic to plan sequence, identify critical activities and present a Gantt baseline.
- **Planned Value (PV):** Budgeted value of work scheduled by the status date.
- **Earned Value (EV):** Budgeted value of work actually completed by the status date.
- **Actual Cost (AC):** Scenario expenditure incurred by the status date.
- **Schedule Performance Index (SPI):** EV divided by PV.
- **Cost Performance Index (CPI):** EV divided by AC.
- **Estimate at Completion (EAC):** Forecast total cost under the stated forecasting assumption.
- **Estimate to Complete (ETC):** Forecast remaining cost.
- **Variance at Completion (VAC):** BAC minus EAC.
- **To-Complete Performance Index (TCPI):** Required future cost efficiency under the selected target budget.

Always state the formula/forecasting assumption being used when explaining an EAC or TCPI value. Different forecast assumptions can produce different results.

## 6. Reporting cut-off and illustrative scenario

The report uses a monitoring status date of **31 October 2026 (Month 17)**. Its Month 17 scenario reports PV of ₹43.09 crore, EV of ₹40.92 crore and AC of ₹42.93 crore. It reports SPI of approximately 0.950 and CPI of approximately 0.953, with a CPI-based EAC of ₹95.31 crore. These are illustrative case-study values, not actual site accounts or verified physical progress.

## 7. Validation and limitations

The workbook contains 14 worksheets. A static inspection found 3,619 formula cells and no cached Excel error values in the distributed workbook at the time of review. This is not a guarantee that every possible user edit will preserve formula validity; recalculate and review the model after changing inputs.

The case study does not replace approved project drawings, detailed measurement, tender documentation, current market quotations, contract administration, structural or MEP design, statutory compliance review, inspection/test plans or professional engineering judgment. Do not use its values for procurement, construction, certification or payment approval.
