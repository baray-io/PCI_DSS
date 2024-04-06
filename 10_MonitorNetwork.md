# Summary of Requirement #10: Monitor Networks

Requirement #10, often referred to as "Monitor Networks," primarily focuses on logging activities within the Card Data Environment (CDE) to track and identify potential security breaches. It emphasizes the importance of maintaining detailed audit trails and promptly detecting and responding to suspicious activities. The requirement comprises nine sub-requirements, each addressing specific aspects of logging and monitoring practices.

## Sub-Requirements:

1. **Implement Audit Trails:** Establish a logging solution to track and monitor all access to network resources and Cardholder Data (CHD).

2. **Log Specific Events:** Log specific events including admin actions, card data access, changes to logging policies, and user account modifications.

3. **Log Specific Data:** Include specific data points in each log entry such as user ID, event type, timestamp, status (success/failure), origination, and affected resource.

4. **Synchronize Clocks:** Ensure all logging mechanisms synchronize their timing using a single mechanism to facilitate accurate reconciliation of logs.

5. **Prevent Alteration of Audit Trails:** Implement File Integrity Monitoring (FIM) solutions and backup logs promptly to prevent tampering or alteration.

6. **Review Logs Frequently:** Regularly review logs, especially critical ones, to detect and respond to security incidents promptly.

7. **Retain Logs:** Retain logs for at least one year, with the last three months readily accessible for review and analysis.

8. **Detect and Report Failures Timely (for Service Providers):** Promptly detect and report failures in critical systems, including intrusion detection, firewalls, and access control mechanisms, especially for service providers.

9. **Document and Enforce Policies and Procedures:** Document all logging retention policies, access control policies, and procedures related to logging and monitoring, and ensure their enforcement by employees.

Each sub-requirement emphasizes the need for comprehensive logging practices, timely review of logs, and proactive response to security incidents. It underscores the critical role of logging in identifying and mitigating potential threats to the security of Cardholder Data.
