# Task 3: Vulnerability Scan on PC using Nessus Essentials

## Objective
Use Nessus Essentials to scan your computer for common vulnerabilities and check for security risks.

## Tools Used
- **Scanner**: Nessus Essentials
- **Target**: `127.0.0.1` (Localhost)

## Steps Followed
1. Installed Nessus Essentials and activated it using a free code.
2. Set up a new scan with the target as the local machine (127.0.0.1).
3. Started the scan and waited for it to finish.
4. Exported the scan report as a PDF.
5. Checked the results to find important vulnerabilities.
6. Noted medium and informational issues and added suggestions to fix them.
7. Took screenshots of the scan results and plugin details.

## Scan Summary
| Severity  | Count |
|-----------|-------|
| Critical  | 0     |
| High      | 0     |
| Medium    | 2     |
| Low       | 0     |
| Info      | 39    |
| **Total** | **41** |

## Medium Severity Vulnerabilities
| Plugin ID | Name                        | Description |
|-----------|-----------------------------|-------------|
| 51192     | SSL Certificate Cannot Be Trusted | SSL certificate may be untrusted, enabling MITM attacks. |
| 57608     | SMB Signing Not Required    | SMB traffic is not signed, increasing the risk of interception. |

## Conclusion
The vulnerability scan found two medium-risk issues and several informational items. It highlighted the need to:
- Use trusted SSL certificates.
- Enable SMB signing to secure file sharing.

To keep the system safe, it's a good idea to scan it regularly and make it more secure.
