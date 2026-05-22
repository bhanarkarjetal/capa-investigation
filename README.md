# CAPA Investigation Report

A hypothetical CAPA (Corrective and Preventive Action) investigation built on a real FDA recall pattern. The project demonstrates how a complete CAPA report is structured and what each section typically includes.

## About this project

The report investigates a confirmed nonconformity in a sterile venting inline filter used with infusion pumps. It is set in a fictional medical device company (MedFluss GmbH), but the failure pattern, the nonconformity type, and the regulatory pathway are based on actual FDA infusion pump recall data.

The aim is to show how a CAPA report is put together from start to finish: how the problem is described, how the investigation is run, how the root cause is identified using structured methods, how corrective and preventive actions are designed, and how the work is verified and closed. 

The report follows ISO 13485 and EU MDR conventions throughout.

## The scenario in brief

Customers report fluid leakage from the air vent of an inline filter on a high-volume infusion set. The investigation traces the issue to a tiny embedded particle on a sonotrode horn used during ultrasonic welding. The particle creates micro-punctures in the hydrophobic membrane. The existing inspection tools miss the defect because the particle is too small to see with the naked eye, and routine cleaning cannot remove it once embedded. The root cause turns out to be an inspection interval that was set at product launch and never refreshed as production volume grew. The report covers everything that follows: containment, field action, investigation, root cause analysis, corrective and preventive actions, revalidation, and closure.

## What the report includes

- CAPA identification and source of detection
- Risk assessment summary
- Containment and field action (FSCA, FSN, regulatory notifications)
- Quality investigation and root cause analysis (Five Whys)
- Corrective actions and preventive actions
- Verification, validation, and IQ/OQ/PQ revalidation
- Effectiveness check with 90-day surveillance
- Documentation update and formal closure

## Standards applied

- ISO 13485:2016
- ISO 14971 (Risk Management)
- EU MDR 2017/745

## Repository structure
```
capa-investigation/
├── README.md
└── capa-report/
    └── CAPA-MF-1529-MFG-air-vent-leakage.md
```

## Disclaimer

The company, personnel, lot numbers, internal procedures, and supporting records in this report are entirely fictional. The scenario draws on publicly available FDA recall data for infusion pump components but does not reproduce any real company event, patient case, or regulatory action.

## Author

Jetal Bhanarkar