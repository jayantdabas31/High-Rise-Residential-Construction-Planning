# Excel workbook guide

The workbook contains seven worksheets.

| Worksheet | Purpose | Key fields / controls |
|---|---|---|
| Dashboard | Consolidated monitoring snapshot | BOQ total, actual cost, monitoring budget balance, weighted progress, PV, EV, SPI and CPI |
| BOQ & Cost | Starter bill of quantities and cost estimate | Work package, item description, unit, illustrative quantity, assumed rate and calculated amount |
| Progress & Cost | Sample monthly progress and cost review | WBS activity, planned/actual progress, budget, actual cost, status, action note, PV and EV helper columns |
| Schedule | Level-1 construction programme | Activity, duration, start/finish week, predecessor and milestone/control point |
| Material Plan | Indicative procurement planning | Material, planning requirement, lead time, inspection/acceptance, storage and planning notes |
| QA-QC Checklist | Example quality inspection hold points | Work item, inspection/test, stage, acceptance reference, record and responsible role |
| Risk Register | Example project risk log | Risk, impact, likelihood, severity, score, mitigation and owner |

## Updating the workbook

1. Duplicate the workbook before editing so the original example remains available.
2. Replace illustrative assumptions with a clearly defined academic scenario or verified project inputs.
3. Use the same data date for planned progress, actual progress and actual cost.
4. Use an agreed quantity- or budget-weighted progress method rather than an unweighted average when reporting overall progress.
5. Keep the BOQ total and control budget reconciled; investigate the displayed difference before drawing conclusions.
6. Add commitments, certified bills, retention, taxes, escalation and remaining-work forecasts when appropriate to the actual project brief.
7. Record sources and drawing references for each quantity and rate.
8. Confirm that all schedule logic, resource calendars, floor cycles, procurement lead times and milestone dates match the scenario.

## EVM formulas used in the dashboard

- Planned Value (PV) = Σ(Budget × Planned %).
- Earned Value (EV) = Σ(Budget × Actual %).
- Actual Cost (AC) = Σ(Actual cost).
- Schedule Performance Index (SPI) = EV / PV.
- Cost Performance Index (CPI) = EV / AC.

All values in the supplied file are illustrative and intended for demonstration, not live project reporting.
