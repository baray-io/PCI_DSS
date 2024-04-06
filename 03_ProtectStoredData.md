# Summary of Requirement #3: Protect Stored Data

Requirement #3, known as "Protect Stored Data", focuses on safeguarding data at rest, such as in databases or files. This involves not only encryption but also other methods like masking, as well as robust key management practices.

## Sub-Requirements:

1. **Limiting Storage and Retention:** Implement policies to restrict the storage and retention of card data to essential requirements, including both digital and physical mediums, and ensure proper disposal methods.

2. **Avoiding Storage of Sensitive Authentication Data (SAD):** Prohibit the storage of sensitive authentication data like CVV numbers or PINs, emphasizing the need for real-time usage without retention.

3. **Masking Stored Personal Account Numbers (PANs):** Mask the PANs to show only the first 6 and last 4 digits, reducing exposure while allowing for identification.

4. **Rendering PANs Unreadable in Communication Channels:** Encrypt or mask PANs in all communication channels to prevent interception and unauthorized access.

5. **Procedures for Key Protection:** Establish protocols for safeguarding encryption keys, including access control, backups, and minimizing access points.

6. **Procedures for Key Management:** Define processes for managing encryption keys throughout their lifecycle, including storage, rotation, and replacement.

7. **Documenting and Enforcing Policies:** Formalize policies and procedures for all aspects of data protection, ensuring awareness and compliance among employees.

Each sub-requirement underscores the importance of comprehensive measures to protect stored data, encompassing not only encryption but also careful management of encryption keys and adherence to established policies and procedures.
