# SIEM Log Analysis & Incident Investigation

## Objective
Analyze security event logs in a SIEM environment to identify suspicious activity, validate alerts, and determine appropriate response actions.

## Scenario
A SIEM alert was generated indicating multiple failed login attempts followed by a successful authentication from a single source. The activity occurred outside normal business hours and originated from an unfamiliar IP address.

## Data Sources Reviewed
- Authentication logs
- Failed and successful login events
- Source IP address data
- Timestamp and user account context

## Analysis Performed
- Reviewed failed login patterns for brute-force indicators
- Correlated successful login following failures
- Evaluated login timing against normal user behavior
- Checked IP address reputation and geolocation
- Assessed risk of credential compromise

## Findings
- Multiple failed login attempts preceded a successful login
- Login occurred outside standard working hours
- Source IP was not previously associated with the user
- Activity matched common credential-stuffing behavior

## Indicators of Compromise (IOCs)
- Unusual source IP address
- Abnormal login time
- Excessive failed authentication attempts
- Successful login after repeated failures

## Response Actions
- Flagged user account for monitoring
- Recommended password reset and MFA verification
- Documented findings for escalation
- Advised blocking suspicious IP if repeated behavior continues

## What This Demonstrates
- SIEM alert triage
- Log correlation and analysis
- Risk-based incident assessment
- SOC-style documentation
- Clear escalation reasoning

## Tools & Techniques
- SIEM log review
- Authentication event analysis
- Pattern recognition
- Incident documentation
