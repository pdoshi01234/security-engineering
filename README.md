\# Security \& Vulnerability Management Practice Portfolio



\## Overview



This repository contains hands-on security analysis exercises completed as part of my security engineering and vulnerability management practice.



The exercises focus on investigating security alerts, reviewing available evidence, assessing whether activity is expected or suspicious, validating remediation or resolution, and documenting the final decision.



All scenarios and data in this repository are synthetic and are used for learning and portfolio purposes.



\## Skills Practiced



\* Security alert investigation

\* Evidence-based analysis

\* Severity assessment

\* False-positive and true-positive analysis

\* Security remediation verification

\* Vulnerability scanner activity investigation

\* Change-management validation

\* Security documentation and handovers



\## Investigation Approach



For each case, I followed a structured investigation process:



1\. Understand the alert

2\. Define a reasonable hypothesis

3\. Review the available evidence

4\. Determine whether the activity is expected or suspicious

5\. Assess the security impact

6\. Validate the resolution or remediation

7\. Document the final decision and supporting evidence



\## Portfolio Cases



\### CLD-0201 — Repeated Failed Sign-ins



Investigation of repeated failed authentication attempts involving a newly created privileged account.



The investigation focused on reviewing sign-in activity and available helpdesk information to determine whether the activity represented a security concern or a legitimate new-user issue.



\[View the investigation](verdicts/CLD-0201.md)



\### CLD-0202 — PUA Detection and Remediation



Investigation of a potentially unwanted application detected on an endpoint.



The investigation focused on confirming the detection, verifying quarantine, and checking whether the unwanted software returned during follow-up scanning.



\[View the investigation](verdicts/CLD-0202.md)



\### CLD-0203 — Guest Account Sign-in Investigation



Investigation of an unusual guest-account sign-in outside normal working hours.



The analysis compared the activity against previous successful sign-ins and reviewed available IP, location, device, and browser information.



\[View the investigation](verdicts/CLD-0203.md)



\### CLD-0204 — Vulnerability Scanner Activity Outside Normal Schedule



Investigation of vulnerability-scanner activity occurring outside the scanner's normal schedule.



The investigation included reviewing the approved change record and comparing the observed scanning behavior with expected vulnerability-scanner activity.



\[View the investigation](verdicts/CLD-0204.md)



\## Documentation



The `handovers.md` file contains the security handover documenting the findings and items requiring follow-up.



\## Professional Focus



My professional background is in vulnerability management and Linux platform security, including CVE analysis, vulnerability remediation, patch validation, remediation tracking, and security work across Linux, Yocto/OpenEmbedded, and Kubernetes environments.



This portfolio represents additional hands-on practice in security investigation, analysis, remediation verification, and security documentation.



\## Disclaimer



All data in this portfolio is synthetic and is used for learning and portfolio purposes only. No real customer, company, or production security data is represented.



