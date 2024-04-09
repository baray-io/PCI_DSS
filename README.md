# PCI DSS General Patterns and the 12 Requirements Overview

PCI DSS stands for payment card industry data security standard. Belows are some briefing about the standard.

## General Patterns:

- **Documentation and Enforcement**: Across all requirements, there's a consistent emphasis on documenting policies and procedures related to information security and enforcing them effectively.

- **Change Management Processes**: Any changes, whether to systems, configurations, or applications, must follow a defined process to ensure security is maintained.

- **Common Sense Definitions**: Many requirements emphasize the importance of defining parameters and practices that make logical sense for security, even if there aren't strict, universal values to adhere to.

- **Strong Physical and Logical Security**: Both physical and logical security measures are crucial, including strong authentication, encryption, access controls, and monitoring.

## Recap of the 12 Requirements:

1. **[Firewall Configuration](01_Firewall.md)**: Setting up firewalls to restrict unknown traffic, with proper change management and documentation.
2. **[Default Account Removal](02_NoDefault.md)**: Changing or disabling default accounts and configurations to minimize vulnerabilities.
3. **[Stored Data Protection](03_ProtectStoredData.md)**: Limiting and securing stored cardholder data with encryption and proper key management.
4. **[Transmitted Data Protection](04_ProtectTransmittedData.md)**: Ensuring secure transmission of cardholder data through encryption and best practices.
5. **[Malware Prevention](05_PreventMalware.md)**: Implementing antivirus software and regular updates to prevent malware.
6. **[Secure Development](06_DevelopSecurely.md)**: Patching vulnerabilities in both developed and off-the-shelf software, with secure development practices.
7. **[Need-to-Know Access](07_NeedToKnowAccess.md)**: Restricting access to data based on roles and permissions, following the Principle of Least Privilege.
8. **[Identifying Access](08_IdentifyAccess.md)**: Implementing strong authentication measures to verify user identities before granting access.
9. **[Physical Access Restriction](09_RestrictPhysicalAccess.md)**: Controlling physical access to systems and data through entry controls, visitor management, and secure media handling.
10. **[Network Monitoring](10_MonitorNetwork.md)**: Logging and monitoring network activities to detect and respond to security incidents.
11. **[Regular Testing](11_TestRegularly.md)**: Conducting vulnerability scanning, penetration testing, and intrusion detection to identify and address vulnerabilities.
12. **[Information Security Policy](12_InformationSecurityPolicy.md)**: Establishing comprehensive information security policies covering areas such as risk assessment, employee training, incident response, and vendor management.

## Key Takeaways:

- Each requirement serves a specific aspect of information security, from network protection to secure development practices.
- The requirements collectively address the need for a holistic approach to security, encompassing both technical and procedural measures.
- Documentation, enforcement, and regular review are essential for maintaining compliance and effectively managing security risks.

Overall, the 12 Requirements provide a structured framework for organizations to establish and maintain robust security practices, ensuring the protection of sensitive data and systems against evolving threats.
