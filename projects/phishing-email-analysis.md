---
layout: default
title: Phishing Email Analysis
---

# Phishing Email Analysis & Incident Report

## Objective
Analyze a suspicious email to identify indicators of compromise (IOCs),
assess risk, and recommend appropriate response actions.

## Scenario
A user reported an email claiming urgent account verification was required.
The message included a hyperlink directing the user to log in immediately.

## Analysis Performed
- Reviewed sender address and display name
- Evaluated email body language for social engineering
- Inspected embedded links for domain spoofing
- Assessed likelihood of credential harvesting

## Indicators of Compromise (IOCs)
- Lookalike domain used in sender address
- Urgent language designed to induce panic
- Mismatched hyperlink destination
- Generic greeting and poor formatting

## Risk Assessment
**Severity:** High  
**Threat Type:** Credential harvesting / phishing  
**Impact:** Potential account compromise and lateral movement

## Recommended Response
- Do not interact with links or attachments
- Report email to SOC / security queue
- Block sender and associated domains
- Reset credentials if interaction occurred
- Educate user on phishing indicators

## What This Demonstrates
- Threat triage skills
- Clear documentation
- SOC-style reasoning
- Communication for technical and non-technical audiences

