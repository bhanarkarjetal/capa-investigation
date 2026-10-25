# CAPA Report: CAPA-MF-1529

## 1. CAPA Identification

| Field | Details |
|---|---|
| CAPA ID | CAPA-MF-1529 |
| Date Opened | 12.02.2024 |
| Date Closed | 07.02.2025 |
| Status | Closed |
| Severity | Major |
| Department (Owning)| Manufacturing |
| CAPA Owner | Carlos Rivera, Manufacturing Manager |
| CAPA Coordinator | Thomas Becker, Quality Engineer |
| Closed By | Julia Braun, Quality Assurance Specialist |
| Device Affected | MedFluss Infusion Set with Sterile Venting Inline Filter |
| Product Code | MF-INF-SVIF-200 |
| Affected Lot Range | MF-2023-F036 to MF-2023-F071 (36 lots, ~360,000 units) |
| Detection Source | Post-Market Surveillance - Customer Complaints |
| Linked Complaint Records | CC-2024-0034, CC-2024-0043, CC-2024-0059, CC-2024-0079, CC-2024-0094 |
| Regulatory Standards | ISO 14971, EU MDR, ISO 13485:2016 (Clause 7.5.6, Clause 8.5.2, Clause 8.5.3) |

---

## 2. Problem Statement / Nonconformity Description

MedFluss GmbH received multiple complaints from customers between January and February 2024, reporting fluid leakage from the air vents of MedFluss Infusion Set with Sterile Venting Inline Filter (*Product Number: MF-INF-SVIF-200*).

The air vent in the inline filter is a critical safety component in the IV administration set. It is positioned in the tubing between the infusion pump outlet and the patient's cannula. The air vent uses a hydrophobic membrane to allow trapped air to escape while blocking fluid passage, preventing both therapy interruption and contamination risk.

The products associated with the complaints were traced to lots MF-2023-F036 to MF-2023-F071 (36 lots, ~360,000 units) distributed primarily within the EU and partially to the US market. Five formal complaints (*CC-2024-0034, CC-2024-0043, CC-2024-0059, CC-2024-0079, CC-2024-0094*) were received within a 21-day window from multiple independent hospital networks.

**Observed events reported by customers:**
- Visible fluid droplets on the outer surface of the air vent during infusion
- Loss of medication volume, patient receives less than the prescribed dose
- Wetted external surface of the filter housing, raising contamination concern
- Therapy interruption due to mid-infusion set replacement 

**Failure characteristics confirmed during initial review:**

- Leakage observed across all infusion types (saline, lipid emulsion, parenteral solutions), confirming not dependent on fluid type
- Leakage traced to a specific lot within a defined production window
- Standard end-of-line visual inspection records for the affected lots show no rejections at production
- The release-time bubble-point test record, performed on an AQL sample (5 units per 10,000 units), did not detect the defect
- Failures were detected only during retest of retained samples from the affected lot, which was performed as a part of the complaint investigation (05.02.2024)

**Nonconformity declaration:**

The sterile venting inline filter membrane on lots MF-2023-F036 to MF-2023-F071 fails to maintain the barrier integrity under normal clinical operating conditions. The defect compromises the filter's intended function of permitting controlled air venting and preventing fluid passage and microbial ingress.

This constitutes a nonconformity against:
1. MedFluss product specification PS-INF-SVIF-200 - Air vent leak-tightness requirement
2. ISO 13485:2016 Clause 7.5.6 - Validated Production process failed to consistently produce devices meeting design output conditions
3. ISO 11607-1 - Sterile barrier integrity requirement for terminally sterilised medical devices
4. MDR Annex I (General Safety and Performance Requirements) - Device failed to perform as intended without compromising patient safety

Severity Classified: **Major**. Potential for patient harm (under-dosing, contamination risk) with no confirmed serious injury or death at the time of CAPA opening.

---

## 3. Detection

**Source of Detection:** Post-market surveillance - Customer complaint handling system.

**Detection Timeline**

| Date | Event |
|---|---|
| 22.01.2024 | First complaint (CC-2024-0034) received from Klinikum ABC, Germany, regarding visible fluid droplets over the air vent of the inline filter during a propofol infusion. |
| 25.01.2024 | Second complaint (CC-2024-0043) from Universitätsklinikum XYZ, Austria, reporting fluid leakage from air vent housing with a saline infusion. |
| 29.01.2024 | Third complaint (CC-2024-0059) received from Klinikum LMN, Germany. Trend threshold reached under SOP-QA-007 (3 complaints from independent sites within 30 days referencing the same product family). Mia Lehmann, RA Associate, escalated to QA for nonconformity review. |
| 01.02.2024 | Fourth complaint (CC-2024-0079) from Memorial Hospital Texas (US distribution). Cross-market spread confirmed. |
| 05.02.2024 | Targeted re-test of retained samples from suspect lots initiated under QA Investigation Record QI-2024-019. Bubble-point failures confirmed on multiple units across lots MF-2023-F036 to MF-2023-F071. |
| 08.02.2024 | Fifth complaint (CC-2024-0094) received from Klinikum Austria. |
| 12.02.2024 | Nonconformity confirmed. CAPA-MF-1529 was opened by Thomas Becker (Quality Engineer) following management review approval.|

**Reporting Parties**

- External: Independent site across the EU and the US
- Internal: Mia Lehmann, RA Associate (escalation); Thomas Becker, Quality engineer (CAPA initiation) 

**Detection Criteria Triggered**
- Independent-site complaints crossing complaint-threshold under SOP-QA-007
- Common product family and overlapping lot range across complaints
- Bubble-point failure on retained samples from the affected lot confirming nonconformity

---

## 4. Risk Assessment

A formal risk assessment of the nonconformity was performed under ISO 14971 by the Risk Management department and documented in the Risk Management File (RMF-INF-SVIF-200: Rev 5 updated on 28.02.2024 in response to CAPA-MF-1529).

The Assessment identified loss of sterile barrier integrity and loss of infusate volume as the principal hazards, with potential harms ranging from under-dosing to bloodstream infection. The risk level was determined to be unacceptable, triggering field action (*MF-FSCA-2024-02-003*) and full distribution recall of the affected lots.

Full hazard identification, risk evaluation, and risk control verification are maintained in the risk management file *RMF-INF-SVIF-200: Rev 5* under the ownership of the Risk Management department.

---

## 5. Immediate Correction / Containment

Containment actions executed under CAPA procedure (*SOP-QA-001*) and Field Safety Corrective Action (*SOP-RA-005*) immediately following CAPA opening on 12.02.2024.

**Containment objective**

Prevent further patient exposure to suspected units, quarantine the affected lots, isolate the source, and conduct a thorough investigation of the affected lots.

**Containment Actions**

| **#** | **Action** | **Owner**| **Status** | **Date Completed** |
|-------|------------|----------|------------|--------------------|
|1| Suspend production on Ultrasonic-weld Line UW-02 (Sonotrode SN-UW-02-117) and lock equipment out under SOP-MFG-014 | Carlos Rivera, Manufacturing Manager | Closed | 13.02.2024 |
|2| Quarantine all on-hand inventory of lots  MF-2023-F036 to MF-2023-F07 in central warehouse under restricted-access label | Carlos Rivera, Manufacturing Manager | Closed | 14.02.2024 |
|3| Issue immediate stop-shipment notice DH-2024-003 linked to MF-FSCA-2024-02-003 to all EU and US distributers | Priya Nair, Regulatory Affairs | Closed | 14.02.2024 |
|4| Initiate Field Safety Corrective Action MF-FSCA-2024-02-003, initiating voluntary recall of distributed units from the affected lot| Priya Nair, Regulator Affairs | Closed | 15.02.2024 |
|5| Open enhanced Post-Market Surveillance for daily complaint montoring of MF-INF-SVIF-200 | Sophie Richter, Clinical Affairs Associate | Closed | 16.02.2024|
|6| Issue Field Safety Notice MF-FSN-2024-003 to all customers receiving affected lots, providing return instructions and clinical advisory | Mia Lehmann, RA Associate | Closed | 15.02.2024 | 
|7| Notify Notified Body (TÜV SÜD) of FSCA initiation (reference NB-2024-004) | Priya Nair, Regulatory Affairs | Closed | 19.02.2024 |
|8| Notify BfArM under EU MDR 2017/745 Article 87 (reference BfArM-2024-Vig-076) | Priya Nair, Regulatory Affairs | Closed | 19.02.2024 |
|9| Submit FDA MDR, FDA-MDR-2024-054, for US-distributed units |Priya Nair, Regulatory Affair | Closed | 22.02.2024 | 
|10| Create EUDAMED vigilance incident entry (EUDAMED-INC-2024-0118)| Priya Nair, Regulatory Affairs| Closed | 26.02.2024 |
|11| Switch production for MF-INF-SVIF-200 to backup Ultrasonic-weld Line UW-004 with 100% in-line bubble-point test sampling on every released lot (interim control until full corrective action implemented) | Carlos Rivera, Manufacturing Manager | Closed | 20.02.2024 |
|12| Pull retained samples from all suspect lots for targeted bubble-point retest to establish defect scope and prevalence| Thomas Becker, Quality Engineer | Closed | 19.02.2024 |

**Initial Containment Confirmation (01.03.2024)**
- 100% stop-shipment status confirmed at all EU and US distributors
- Production switchover to UW-04 producing conforming output (verified via 100% in-libe bubble-point test on every released lot)
- No new complaints received on lots produced after 20.02.2024 switchover
- Daily complaint surveillance confirmed no expansion of the trend to other lots

**Containment Effectiveness Review (15.04.2024)**

- Recall return rate of 80% within 60 days
- No further complaints received on affected lots in the surveillance window
- 100% recall of units from affected lots from distributors
- Containment confirmed effective. CAPA progresses under interim control pending full corrective action.

---

## 6. Investigation summary

**Investigation Record:** QI-2024-019 opened on 12.02.2024 under SOP-QA-001

**Investigation Team**

|**Role**| **Name** | 
|---|---|
| Investigation Lead| Thomas Becker, Quality Engineer |
| Process Owner | Carlos Rivera, Manufacturing Manager
| Process Engineering | Losa Hartmann, Production Engineer (Process investigation)|
| Quality Assurance | Sarah Müller, QA Manager|
| Regulatory Affairs | Priya Nair, Regulatory Affairs Manager|
| Complaint Handling | Anna Schmidt, CA Manager|
| External Subject Matter Expert | Branson Welding Technologies - Sonotrode supplier |

**Investigation Methodology**

1. Retained-sample retesting on suspected lots
2. Suspected ultrasonic-welding sonotrode physical examination (visual, optical microscopy, scanning electron microscope)
3. Weld parameter log review (weld time, hold time, energy delivered, triggered force)
4. Vision inspection of camera position and lighting angle review
5. Operators across three shifts interview
6. Statistical analysis of complaint pattern and defect prevalence
7. Horizontal review and analysis of product family on the same Ultrasonic-welding platform

**Investigation summary**

The bubble-point and water intrusion test performed on units produced in lots MF-2023-F036 to MF-2023-F071 under controlled lab conditions showed leakage at the same location of inner edge of the ultrasonic-weld seam at the air-vent housing. The defect is a confirmed micro-puncture in the hydrophobic membrane at the inner edge of the ultrasonic-weld seam caused by an embedded thermoplastic particle at the horn contact face of sonotrode SN-UW-02-117. 

The particle was present for an unknown duration from a prior production run and caused a sub-millimeter over-pressure zone while total pressure across the horn face remained nominal. The particle has been flattened due to continuous welding and was no longer causing defects in the next lot.  

SEM imaging confirmed the particle's position and showed evidence of progressive flattening, meaning the protrusion topology was reduced compared to its original geometry. 

Retained samples pulled from the next lot MF-2023-F072 to MF-2023-F148 showed no signs of micro-puncture, and each sample passed the bubble-point and water intrusion test successfully.

Camera position and lighting angle were reviewed against defective units, confirming that the weld flash completely shadowed the micro-puncture location from overhead view. Six operators across three shifts interviewed reported no unusual sounds, vibration, alarms, or visual indication during the affected window. 
 
Three other MedFluss product families using ultrasonic-welded membrane assemblies were reviewed against the same defect criteria, passed the bubble-point test, and showed no defect on the membrane and the ultrasonic-weld seam. The defect was specific to the sonotrode SN-UW-02-117, lots window MF-2023-F036 to MF-2023-F071, and production line UW-02. There was no spread of nonconformity to other product lines on the same platform.

---

## 7. Root cause analysis

Following the conclusion of the investigation summary under Quality Investigation QI-2024-019, a structured root cause analysis was performed by the investigation team between 26.03.2024 and 29.03.2024. The analysis used the **Five Whys** methodology, validated through replication and removal trials, to produce a formally signed-off root cause statement that the corrective and preventive actions in subsequent sections were designed against.

**Root Cause Analysis initiation:** On 26.03.2024 by Thomas Becker, Quality Engineer.

### 7.1. Five Whys

**Problem Statement**:

The hydrophobic membrane of the sterile venting inline filter (Product code: MF-INF-SVIF-200) contains sub-millimeter micro-punctures at the inner edge of the ultrasonic-weld seam, causing fluid leakage and breaching of sterile barrier integrity.

| **Step** | **Question** | **Finding** |
|---|---|---|
| Why_01| Why did the membrane develop a micro-puncture? | A localized sub-millimeter over-pressure zone was developed at the inner edge of the ultrasonic-weld seam. |
|Why_02| Why was the localised sub-millimeter over-pressure zone developed?| A hardened thermoplastic particle was embedded on the sonotrode horn contact face, producing a concentrated pressure point while the total horn-face pressure stayed within specification|
|Why_03| Why was the particle present on the horn contact face and was not detected?| The Sonotrode was operated continuously for 36 days without intermediate face inspection. Debris accumulated during this window and was not detected|
|Why_04| Why did the inspection during the affected production window not detect the embedded particle?| The maintenance regime defined two tiers of inspection: monthly visual inspection with manual cleaning performed at production-floor conditions, addressing surface debris and general conditions, and quarterly thorough inspection, including optical microscopy under controlled environment, addressing microscopic failure of the horn. The monthly visual inspection and manual cleaning could not remove the embedded particle anchored in the horn surface. The quarterly inspection was scheduled after the affected production window has already concluded.|
|Why_05| Why was the quarterly inspection scheduled too late to detect the embedded particle within the affected window? | The quarterly inspection interval was established at the production launch and was based on the launch-era production. By 2023, the production volume had increased to 1.5x. The interval was scheduled on a calendar basis rather than against the accumulated cycle count.|

### 7.2. Root Cause Summary

The quarterly thorough inspection interval for sonotrode condition was established at product launch in 2021 and was sized against the launch-era production volume. It was scheduled on a calendar basis rather than against the accumulated weld cycle count. As production volume scaled 1.5x in 2023, the cycle exposure between thorough inspections increased proportionately, while the calendar-based inspection remains unchanged. Monthly visual inspection and manual cleaning were performed as per the defined specification to address surface-level contamination, but the resolution of the monthly check was not intended to detect sub-millimeter embedded particles. The combination of calendar-based schedule and an interval anchored to launch-era production condition allowed a single debris event to occur, produce defects across an entire production campaign, and reach the end of its damage cycle before the next scheduled microscopic inspection.

This constitutes an inspection regime gap under ISO 13485:2016 Clause 7.5.6 (Process Validation), in which the validated process control was not maintained against the production conditions to which they applied.

**Root cause formally accepted:** 

On 29.03.2024 by Sarah Müller (QA Manager) and Carlos Rivera (Manufacturing Manager). 

---

## 8. Corrective Actions

Corrective actions were defined to eliminate the cause of nonconformity on Ultrasonic-weld line UW-02 and to restore the welding process to a validated state. The action plan was approved at Management Review on 12.04.2024.

### Action plan

|**#**| **Action** | **Owner** | **Deadline**|**Verification**| **Status**| 
|---|---|---|---|---|---|
|CA1| Reface the Sonotrode SN-UW-02-117 to remove the embedded particle and restore the horn surface to qualified condition. Replace if refacing does not return it to specification.| Losa Hartmann, Production Engineer| 31.05.2024| Post-refacing inspection report. Weld trail of 1000 units passing bubble-point and water intrusion test.| Closed| 
|CA2| Activate the existing cycle counter on Ultrasonic-weld lines UW-02 and UW-04 and configure it to begin counting from the next production lot following sonotrode requalification. Verify the counter reading against the welder controller log.| Carlos Rivera, Manufacturing Manager| 15.06.2024| Counter activation record; report confirming counter readings match the controller log | Closed|
|CA3|Revise SOP-MFG-014 (Sonotrode Maintenance) to add a cycle-based trigger for thorough microscopic inspection and re-establish the interval against current production volume. New trigger: thorough inspection every 250,000 cycles or 6 weeks, whichever comes first.|Thomas Becker, Quality Engineer| 30.06.2024| Revised SOP release under document control.| Closed|
|CA4| Perform process revalidation (IQ/OQ/PQ) of the ultrasonic-welding process under the revised inspection regime.| Hannah Schultz, Process Validation Engineer| 30.09.2024| Approved Process Validation Report| Closed|
|CA5| Train all the maintenance and production personnel on revised SOP-MFG-014, including the cycle-based trigger and the distinction between surface and embedded particle conditions| Julia Braun, QA specialist| 15.10.2024| Training records signed; competency assessment completed| Closed |

### Implementation verification

**CA1:** Sonotrode refaced and returned to qualified conditions. Weld trial passed with zero failures across 1000 units.

**CA2:** Cycle counter reactivated on lines UW-02 and UW-04 with new  inspection regime specifications. Report log created confirming accurate counting.

**CA3:** SOP-MFG-014: Rev 4 released. Cycle-count trigger established at 250,000 cycles or 6 weeks, whichever comes first.

**CA4:** Process validation (IQ/OQ/PQ) completed and documented.

**CA5:** Training delivered to 14 personnel across three production shifts and the maintenance team. Training records documented and maintained.

All corrective actions were completed within the planned implementation window. Effectiveness of the regime is verified in Section 11.

---

## 9. Preventive Actions

A Preventive Action plan was defined to extend the lessons learned from CAPA-MF-1529 across other MedFluss production processes and to address the underlying QMS conditions that allowed the inspection interval to fall out of step with the production volume. The action plan was approved at Management Review on 02.05.2024.

### Action Plan

|**#**| **Action** | **Owner** | **Deadline**|**Verification**|**Status**| 
|---|---|---|---|---|---|
|PA1| Conduct a horizontal review of all wear-part equipment used across MedFluss production lines (sonotrodes, welding-horn, cutting tools, etc.). Reclassify any equipment currently managed under calendar-based preventive maintenance to cycle-based maintenance.| Hannah Schultz, Process Validation Engineer| 30.08.2024| Horizontal review report. Updated asset register.| Closed|
| PA2 | Establish the requirement of inspection interval for all wear parts using two parallel triggers, calendar-based and cycle-count based, in Process Validation SOP (SOP-QA-004). The inspection is performed whichever trigger occurs first to ensure every inspection and maintenance is tied to actual equipment usage. | Hanna Schultz, Process Validation Engineer | 31.10.2024 | Revised Process Validation SOP released. Existing wear-part inspection intervals reviewed and converted to dual-trigger format| Closed|
|PA3| Revise the Change Control SOP (SOP-QA-005) to require the update and review of all processes and inspection parameters, including dual-trigger inspection interval established under PA2, sampling rates, equipment service life estimates, and process control limits to remain within the newly-defined specifications.| Thomas Becker, Quality Engineer| 20.11.2024| Revised SOP-QA-005 released explicitly listing update and review of parameters requiring re-evaluation on scaling events.| Closed|

### Implementation verification

**PA1:** Horizontal review covered 17 equipment items across 6 production lines. Four additional items were reclassified as wear parts and converted to cycle-based maintenance regimes. 

**PA2:** Revised Process Validation SOP released SOP-QA-004: Rev 3 explicitly mentioning the requirement of dual-trigger inspection and maintenance intervals.

**PA3:** SOP-QA-005: Rev 6 released. Production volume scaling is now formally listed as a change control trigger requiring review and update of all process and inspection parameters.

All preventive actions were completed within the planned implementation window. Effectiveness of the preventive actions is verified jointly with corrective actions in section 11.

---

## 10. Verification and Validation Actions

### 10.1. Verification and Validation Strategy

The Verification and Validation work for CAPA-MF-1529 followed two complementary disciplines. 

**Verification:** Used to confirm that each action was implemented as specified, that all the documents needed were released, equipment was installed, training records were completed, and procedures were followed correctly.

**Validation:** Used to confirm that the implemented actions achieved the intended outcomes, that the refaced Sonotrode produced conforming welds, that the revised inspection regime detected the failure mode it was designed to catch, and the processes operated within specifications and statistical control under the new conditions.

Each V&V activity was performed by personnel independent of the action owner, in line with SOP-QA-001 (CAPA), SOP-QA-004 (Process Validation), and SOP-QA-005 (Change Control). Felix Wagner (Quality Auditor) acted as an independent reviewer for most action-level verifications, and Sarah Müller (QA Manager) signed off on SOP-level verifications. All V&V records were documented and retained under the CAPA file CAPA-MF-1529.

### 10.2. Verification of Corrective Actions

|**Action**|**Verification Method**| **Validation Method**| **Independent Reviewer**| **Date**| **Outcome**|
|-|-|-|-|-|-|
|CA1: Sonotrode refacing| Post-refacing dimensional and surface inspection of horn contact face| 1000 units weld trial with bubble-point and water intrusion testing| Felix Wagner| 26.05.2024| Zero failures across the trial population. Sonotrode returned to qualified condition.
|CA2: SOP-MFG-014 revision| Document control review of Rev 4. Cycle-count trigger definition check| Cross-reference to activated cycle-counter and SOP-QA-004 confirmed| Sarah Müller| 27.06.2024| SOP-QA-004 released under document control.|
|CA3: Cycle-counter activation| Reconciliation of cycle-count reading with welder controller log across next 5 lots| Exact agreement between counter and controller log confirmed| Felix Wagner| 13.06.2024| Counter operating accurately|
|CA4: Process revalidation.| See section 10.4| See section 10.4| Felix Wagner| 10.11.2024| See section 10.4|
|CA5: Training| Review of signed training records (14 personnel)| Post-training competency assessment| Felix Wagner|11.10.2024| All personell passed competency assessment.

### 10.3. Verification of Preventive Actions

|**Action**|**Verification Method**| **Validation Method**| **Independent Reviewer**| **Date**| **Outcome**|
|-|-|-|-|-|-|
|PA1: Horizontal review of wear-part equipment| Independent review of updated asset register and revised maintenance SOP| Reclassification of all equipment traced to CAPA-MF-1529 root cause for each reclassified item| Felix Wagner| 22.12.2024| Horizontal review report approved. Four items were reclassified and converted to a dual-trigger regime.|
|PA2: SOP-QA-004 revision| Document control review of dual-trigger re-evaluation requirement in Rev 3| Existing wear-part intervals confirmed and converted to dual-trigger structure.| Sarah Müller| 19.11.2024| SOP-QA-004 released under document control|
|PA3: SOP-QA-005 revision| Document control review of new scaling-triggered requirement in Rev 6| Parameter list and cross-reference to PA2 confirmed| Sarah Müller| 19.11.2024| SOP-QA-005 released under document control|

### 10.4. Process Revalidation Detail (CA4)

The revalidation of the ultrasonic-welding process under SOP-QA-004 covered three sequential qualification stages completed between 26.07.2024 and 27.09.2024.

**Installation Qualification (IQ):** Verified that the refaced sonotrode, the activated cycle counter on lines UW-02 and UW-04, and the supporting welder controller software were installed and configured against approved specifications. Calibration certificates were current, utility connections were correct, and software versions matched the configuration baseline.

**Operational Qualification (OQ):** Demonstrated that the Ultrasonic-welding process on the lines UW-02 and UW-04 operated within defined parameters across its full operating range. Weld energy, trigger force, weld time, and hold time were tested at low, nominal, and high settings, with alarms and interlocks confirmed. The revised inspection regime of monthly visual with manual cleaning and dual-trigger regime of 250,000 cycles or 6 weeks microscopic inspection was exercised with deliberately introducing sub-mm particle, confirming that the thorough inspection step reliably detected the failure mode at its actual scale.

**Performance Qualification (PQ):** Comprised of three consecutive production runs under the revised regime, each of 10,000 units. Weld parameters were monitored continuously and subjected to process control analysis. Post-weld integrity testing confirmed 100% in-line pressure decay plus bubble-point on the AQL sample, which recorded zero defects across all three runs. The validation report was issued on 27.09.2024 and reviewed by Felix Wagner before release.

### 10.5. Verification and Validation Sign-off

All corrective and preventive actions in this CAPA were verified for procedural completion and validated for their intended outcome. An independent review was performed for every action, with no V&V activity signed off by the original action owner. The complete V&V record is retained under CAPA-MF-1529.

**Verified and Validated:** 22.12.2024

**Independent reviewer:** Felix Wagner, Quality Auditor

**QA approval:** Sarah Müller, QA manager

---

## 11. Effectiveness check

The following criteria were defined at CAPA opening and reconfirmed at Management Review on 12.04.2024. The CAPA could only be closed when all the criteria were met within the surveillance window.

|**#**| **Criteria**| **Threshold**| **Result**| **Status**|
|---|---|---|---|---|
|EC1| No recurrence of the membrane micro-puncture defect on the revised process.| Zero confirmed cases related to the affected product| Zero confirmed cases over 90 days window.| Met|
|EC2| No complaints of air-vent leakage on MF-INF-SVIF-200 in the surveillance window.| Zero new complaints related to the affected product| Zero complaints related to air-vent leakage on MF-INF-SVIF-200. Complaint volume returned to baseline for the product family.| Met|
|EC3| Process capability maintained under the revised regime.| Cpk >= 1.33 sustained across surveillance window| Cpk values across the surveillance window ranged from 1.58 to 1.67.| Met|
|EC4| Dual-trigger inspection regime operating as designed.|First cycle-count triggered thorough inspection performed within 5% tolerance of 250,000 cycle threshold| First cycle count triggered inspection at 252,400 cycles. Sonotrode condition confirmed within specifications.|Met|
|EC5| Compliance with revised SOPs verified by internal audit.| No major audit findings against revised SOP | No major findings against revised SOPs. One minor finding on training record completeness, corrected within 7 days.|Met|
|EC6| No expansion of FSCA scope (no affected lots identified).|Affected lot range remains unchanged from MF-2023-F036 to MF-2023-F071| No additional affected lots identified. FSCA scope remained unchanged.|Met|
|EC7| Horizontal preventive actions effective across all other product lines.|No related issues identified in other reclassified equipment| No new issues identified across four reclassified equipment on other production line.|Met|

### Surveillance Period and Methods

Routine production resumed under the revised regime and SOPs on 15.10.2024, following completion of training under CA5. The effectiveness surveillance period was set to 90 days from the date, concluding on 13.01.2025. The surveillance combined six independent monitoring activities:
1. Daily complaint monitoring for MF-INF-SVIF-200 through the complaint handling system managed by Anna Schmidt, CA Manager.
2. Weekly review of production parameter logs and statistical process control charts, handled by Hanna Schultz, Process Validation Engineer.
3. Monthly review of cycle counter logs and reconciliation with welder control data, supervised by Carlos Rivera, Manufacturing Manager.
4. Internal audits of revised SOPs (SOP-MFG-014: Rev 4, SOP-QA-004: Rev 3, SOP-QA-005: Rev 6) conducted on 10.12.2024 by Felix Wagner, QA Auditor.
5. First cycle-count triggered thorough microscopic inspection of sonotrode SN-UW-02-117, performed on 12.11.2024 at an accumulated cycle of 252,400 cycles, confirming sonotrode conditions within specifications.
6. Continued Horizontal review of reclassified wear-part equipment across other production lines.

### Conclusion

All seven effectiveness criteria were met within the 90-day surveillance window. The corrective actions removed the immediate condition on Sonotrode SN-UW-02-117 and re-established the validated state of the welding process. The preventive actions confirmed the change of inspection interval of all wear-part equipment to a dual-trigger regime and require re-evaluation of all process parameters whenever new scaling in production volume occurs. The first cycle-count triggered microscopic inspection demonstrated the functioning of the dual-trigger mechanism as designed.

The root cause has been eliminated, the process has been restored to a validated state, and no recurrence of failure has been observed.

### Sign-off

|**Role**|**Name**|**Date**|
|---|---|---|
|Effectiveness verified by (independent)| Felix Wagner, Quality Auditor| 10.01.2025|
|QA approval| Sarah Müller, QA Manager| 13.01.2025|
|CAPA owner concurrence| Carlos Rivera, Manufacturing Manager| 15.01.2025|

---

## 12. Documentation update

All documents created, revised, or formally referenced under CAPA-MF-1529 were approved as per the MedFluss Document Control SOP. The full set is summarised below.

### 12.1. Documents Created

|**Document**|**Reference**|**Date**|**Owner**|
|--|--|--|--|
|CAPA Record|CAPA-MF-1529| 12.02.2024|Thomas Becker, Quality Engineer|
|Distribution Hold Notice| DH-2024-003| 14.02.2024|Priya Nair, RA Manager|
|Field Safety Corrective Action Record|MF-FSCA-2024-02-003|15.02.2024|Priya Nair, RA Manager|
|Field Safety Notice| MF-FSN-2024-003|15.02.2024 |Mia Lehmann, RA Associate|
|Quality Investigation Record| QI-2024-019|12.02.2024 |Thomas Becker, Quality Engineer|
|Process Validation Report (revalidation of UW-02)|PV-MFG-2024-018|27.09.2024| Hannah Schultz, Process Validation Engineer|

### 12.2. Documents Revised

|**Document**|**From**|**To**|**Released**|**Owner**|
|--|--|--|--|--|
|SOP-MFG-014: Sonotrode Maintenance| Rev 3|Rev 4| 21.06.2024 |Thomas Becker, Quality Engineer|
|SOP-QA-004: Process Validation |Rev 2 |Rev 3 | 14.11.2024 |Hannah Schultz, Process Validation Engineer |
|SOP-QA-005: Change Control|Rev 5 | Rev 6 | 18.11.2024 | Thomas Becker, Quality Engineer |
|RMF-INF-SVIF-200: Risk Management File |Rev 4 | Rev 5 | 28.02.2024 |Sarah Müller, QA Manager|

---

## 13. Approval and Closure

### 13.1. Closure summary

CAPA-MF-1529 was opened on 12.02.2024 in response to a confirmed nonconformity in the sterile venting inline filter of the MedFluss Infusion Pump with Sterile Inline Filter (Product Number: MF-INF-SVIF-200) containing a membrane micro-puncture caused by an embedded thermoplastic particle on sonotrode SN-UW-02-117. All containment, corrective, and preventive actions were implemented within the planned timeline. The root cause, a quarterly thorough inspection interval established as per the launch-era production volume and scheduled on a calendar-only basis, was eliminated through process revalidation, introduction of a dual-trigger inspection regime, and SOP-level changes extending the structural fix across the wider QMS 

Verification and validation activities were independently reviewed, and the effectiveness check confirmed all seven defined criteria were met within the 90-day surveillance window. All regulatory notifications and filings were completed and acknowledged.

### 13.2. Final Approval Signatures


|Role| Name|Date|
|--|--|--|
|CAPA Coordinator|Thomas Becker, Quality Engineer|03.02.2025|
|CAPA Owner|Carlos Rivera, Manufacturing Manager|04.02.2025|
|Independent V&V Reviewer|Felix Wagner, Quality Auditor|22.12.2024|
|QA Manager Approval|Sarah Müller, QA Manager |05.02.2025|
|Closed By |Julia Braun, QA Specialist|07.02.2025 |

### 13.3. Closure Statement

All actions defined under CAPA-MF-1529 have been completed, verified, validated, and confirmed effective. The nonconformity has been resolved, the root cause has been eliminated, the affected process has been restored to a validated state, and the failure prevention has been extended across the wider Quality Management System through the preventive actions. No recurrence has been observed during the surveillance window. All regulatory obligations have been discharged
CAPA-MF-1529 is hereby formally closed.

**Closure Date:** 07.02.2025

---
