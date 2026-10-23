# Software-Security

## 1. Briefly summarize your client, Artemis Financial, and its software requirements.
Artemis Financial is a consulting company that creates personalized financial plans. They wanted to modernize and secure their RESTful web API against external threats.

## 2. What did you do well? Why is it important to code securely? What value does software security add?
I combined manual code review with automated static testing to catch both code flaws and known library vulnerabilities. Secure coding protects customer data, prevents legal and financial damage, and builds trust.

## 3. Which part of the vulnerability assessment was challenging or helpful?
The manual review was challenging because it required thinking like an attacker. The dependency-check report was most helpful because it quickly surfaced known CVEs with recommended fixes.

## 4. How did you increase layers of security? What would you use in the future?
I added HTTPS/TLS, input validation, a SHA-256 checksum, and updated dependencies. In the future, I would use the OWASP Top 10, CVSS scores, and static and dynamic scanners to prioritize fixes.

## 5. How did you make certain the code was functional and secure after refactoring?
I rebuilt and tested the endpoints after each change, then re-ran dependency-check and compared it to the original report to confirm no new vulnerabilities appeared.

## 6. What resources, tools, or practices might be helpful in the future?
The Maven dependency-check plug-in, the NIST NVD, the OWASP Top 10, input validation, up-to-date dependencies, and a documented mitigation plan.

## What might you show future employers
The vulnerability assessment report and the before-and-after dependency-check results, which show I can find, fix, and communicate security risks.
