Status

In progress - initial hypothetical risk register created.

Overview

This portfolio project demonstrates a structured cybersecurity risk assessment for Northstar Client Services, a fictional 40-person business that stores client contact records and uses Microsoft 365, Windows laptops, shared files, and cloud backups.

The objective is to identify security risks, prioritize them based on potential likelihood and business impact, recommend practical controls, and map those controls to the NIST Cybersecurity Framework (CSF) 2.0.

All company details, weaknesses, scores, and risk scenarios are invented for education. They are not results of an actual audit or penetration test.

Scope

Employee identities and Microsoft 365 accounts

Windows endpoints and software patching

Shared file permissions and client data

Backup and restoration procedures

Employee phishing awareness

Tools and references

Microsoft Excel: risk register and scoring

NIST CSF 2.0: security outcome mapping

GitHub: project documentation and version history

Primary reference: NIST Cybersecurity Framework 2.0 (CSWP 29).

Assessment method

Identify assets, potential threat events, and assumed control gaps.

Write each risk as an event and business consequence.

Assign a likelihood score from 1 (rare) to 5 (very likely).

Assign a business impact score from 1 (negligible) to 5 (severe).

Calculate the illustrative inherent risk score = likelihood × impact.

Classify scores: Low (1–4), Moderate (5–9), High (10–16), Critical (17–25).

Propose treatment, accountable owner, control improvements, and verification evidence.

The 1–5 scoring rubric and its thresholds are project-specific learning assumptions, not a scoring formula mandated by NIST. Current controls have not been verified; residual risk will be considered later after the proposed controls are evaluated.

Work completed

Defined the fictional company and scope

Selected NIST CSF 2.0 as the reference framework

Created a risk register with five example scenarios

Scored the first risk as a worked example

Assess and justify the remaining risk scores

Prioritize remediation and estimate residual risks

Draft a one-page management report

Publish documentation and screenshots to GitHub

Initial worked example

GRC-001 — Missing MFA: If employee cloud accounts are protected only by passwords, an attacker who obtains a password could gain unauthorized access to client files. The example assumes likelihood 4 and impact 5, producing an inherent score of 20 (Critical). The proposed treatment is to enable MFA, prioritize administrative accounts, and verify the policy with account-enrollment and sign-in evidence. This example maps primarily to PR.AA-03.

These estimates are hypotheses, not observed findings. A real analyst would request identity settings, access reports, and sign-in evidence before confirming the gap or score.

Next step

Review GRC-002 — Untested backups. Choose a likelihood (1–5) and impact (1–5), explain the reasoning, and document which evidence would confirm the concern. Repeat for the remaining risks.

Portfolio integrity

This is a simulated case study. The README and résumé should describe it accurately as a hypothetical GRC risk assessment, not a production audit for a real company.
