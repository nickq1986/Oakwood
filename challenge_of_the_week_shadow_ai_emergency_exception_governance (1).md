# 🛠️ Challenge of the Week: Shadow AI & Emergency Exception Governance

You are in your second month at **Oakwood Care Group**, a fictional mid-sized British social care provider operating 35 residential and nursing care homes across the UK. Oakwood manages sensitive adult social care records, staff rosters, and personal health data (regulated under UK GDPR, Data Protection Act 2018, and Care Quality Commission [CQC] standards). 

This week’s scenario tests your ability to navigate governance, risk, and compliance (GRC) when strict security controls clash with urgent operational deadlines.

---

## How it works

1. **Do the work.** Everything you need is in this document. No lab required.
2. **Submit by Saturday, 11:59 PM GMT** as a reply in that challenge's thread, using the submission format at the bottom.
3. **Review two other submissions** by Sunday, scoring them against the rubric with one sentence of feedback each.
4. **Compare against my model answer**, posted on Sunday Evening.

### How every challenge is scored (1–5 each)
* **Accuracy:** Did you address the real regulatory, data protection, and operational risks?
* **Reasoning:** Did you explain *why* your approach balances data protection with service continuity?
* **Communication:** Could a busy manager understand your solution in 60 seconds?

> *Oakwood Care Group, its homes, domains, and systems are fictional and used for training only.*

---

## 🎟️ Ticket from your manager

> "We’ve got a major issue on our hands. InfoSec just caught the Quality & Compliance team using a personal, free-tier ChatGPT account on a personal laptop to summarize draft CQC inspection reports and care plan auditing templates. 
> 
> Our approved corporate AI tool, `Oakwood-Assist`, keeps hitting token limits and crashing on long documents. The care home manager knew they were using personal accounts because the deadline for the CQC response hasn't moved, and a late filing risks an official warning letter. Security wants to issue an immediate 'stop work' order. If we do that, we miss the deadline. 
> 
> I need an action plan for tomorrow morning that gives us a workable alternative, defines who can approve an emergency exception, and sets a strict review schedule—'just stop' leaves half the business problem unsolved."

---

## 📋 The Scenario Details

* **The Problem:** The enterprise-approved tool (`Oakwood-Assist`) cannot handle large document uploads due to token processing limits.
* **The Violation:** Staff used a personal account to upload unredacted draft care plan reviews containing resident names, care notes, and local authority details (posing a UK GDPR / Special Category Data exposure risk).
* **The Discovery:** Information Security discovered the traffic log during a routine network audit halfway through the CQC filing window.
* **Current Policy State:** The current Information Governance policy states: *"The use of unapproved software or personal accounts for company business is strictly prohibited."* It contains no fast-track emergency exception pathway when core tools fail.

---

## 🎯 Your Deliverables

1. **Immediate Triage & Containment Plan (Tomorrow Morning):**
   * Outline the exact 9:00 AM steps for Information Governance and operations to contain the data risk while keeping the CQC filing on track.
2. **Risk & Impact Assessment:**
   * Compare the UK GDPR data exposure risk against the regulatory risk of a missed CQC filing, explaining which takes priority and why.
3. **Policy Exception & Governance Framework:**
   * Draft the core requirements for a new policy mechanism, specifying:
     * A **Workable Alternative Pathway** when corporate tools fail.
     * An **Approval Authority Matrix** (who can sign off emergency exceptions).
     * A **Review Cadence** for expiring temporary approvals.
4. **Message to the Care Home Regional Manager:**
   * A short email (150 words maximum) explaining what needs to happen next, written in plain, non-punitive language.

---

### 🌟 Bonus Point
Explain why a simple "stop using it" order fails operationally in a care setting, and what compensatory control you can put in place tomorrow morning to salvage the work already generated.

---

## 📮 Submission Format

Please structure your submission as follows:

```text
1. Immediate Triage & Containment Plan
[Your answer]

2. Risk & Impact Assessment
[Your answer]

3. Policy Exception & Governance Framework
- Alternative Pathway:
- Approval Authority Matrix:
- Review Cadence:

4. Message to Regional Manager
[Your 150-word email]

Bonus Point (Optional)
[Your answer]
```