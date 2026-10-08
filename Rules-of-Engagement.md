# Rules of Engagement (RoE)
## Authorized Ethical Hacking Practice Lab

**Document status:** Beginner Practice Lab  
**Purpose:** Controlled security testing and learning

### 1. Authorization
I will perform security testing only against systems that I own/control or for which I have explicit written authorization.

For this exercise, the authorized target is the intentionally vulnerable application deployed as part of my local practice lab.

### 2. Authorized Target
- OWASP Juice Shop or DVWA deployed locally.
- Only the specific local instance configured for this exercise.
- No production or third-party systems.

### 3. Allowed Techniques
The following activities are permitted within the authorized lab:
- Service and application discovery against the local target.
- Basic vulnerability identification.
- Manual web application security testing.
- Benign proof-of-concept testing that does not target external systems.
- Documentation of findings.

### 4. Prohibited Activities
The following are prohibited:
- Testing public websites without permission.
- Scanning or attacking third-party IP addresses.
- Credential attacks against real accounts.
- Phishing or social engineering of real people.
- Malware deployment.
- Persistence on real systems.
- Data exfiltration from unauthorized systems.
- Denial-of-service testing against real services.
- Any activity that crosses outside the defined lab scope.

### 5. Data Handling
Only synthetic/test data belonging to the lab may be used. No personal, confidential, or third-party data should be collected.

### 6. Network Boundaries
The vulnerable target must remain in the intended local/isolated lab environment. It must not be intentionally exposed to the public Internet.

### 7. Stop Conditions
Testing must stop immediately when:
1. The target is outside the approved scope.
2. Unexpected external traffic or a third-party system is identified.
3. The lab becomes accessible from an unintended network.
4. Testing could impact anything outside the lab.
5. The authorized owner/instructor requests that testing stop.

### 8. Incident Handling
If unintended access or impact occurs:
- Stop the test.
- Disconnect/isolate the lab if necessary.
- Record what happened.
- Do not continue investigating the unintended target.
- Notify the appropriate instructor/lab owner.

### 9. Time and Environment
Testing is limited to the designated practice session and local lab environment.

### 10. Acceptance
By using this lab, I agree to follow the scope and restrictions above and to avoid unauthorized security testing.
