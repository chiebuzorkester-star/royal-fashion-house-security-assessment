Royal Fashion House – Website Security Assessment

1. Project Overview

This project documents an authorised website security assessment of Royal Fashion House.

The assessment was conducted as part of my practical cybersecurity learning journey, focusing on website security, web application security and vulnerability assessment.

* Website: https://royalfashionh.com
* Assessment tool: OWASP ZAP
* ZAP version: 2.17.0
* Scan type: Baseline security scan
* Report date: 15 October 2026

2. Project Objectives

* Understand website security assessment methodologies.
* Practise using OWASP ZAP.
* Explore HTTP requests and response headers.
* Identify potential web application security weaknesses.
* Document security observations and recommendations.

3. Tools Used

* OWASP ZAP (Zed Attack Proxy)
* Kali Linux
* Brave web browser
* HTTP/HTTPS fundamentals

4. Assessment Methodology

The assessment involved reviewing the publicly accessible website and using OWASP ZAP Baseline Scanning to identify potential security configuration issues.

The scan was primarily passive and did not involve exploitation of vulnerabilities.

The generated report recorded 124 endpoints. All observed requests in the report used the HTTP GET method.

5. Scan Results

The OWASP ZAP report recorded 27 alerts.

Risk Level	Number of Alerts
High:	0
Medium:	9
Low:	11
Informational:	7
Total:	27

False positives recorded in the report: 0.

These are automated scanner classifications and should not be interpreted as proof that every alert represents an exploitable vulnerability.

6. Main Security Areas Identified

The reviewed alerts highlighted several areas requiring security review:

* Content Security Policy (CSP) configuration.
* Cross-Site Request Forgery (CSRF) protection.
* Clickjacking protection.
* Cross-domain security configuration.
* Subresource Integrity (SRI).

These observations indicate areas where the website’s security configuration may be improved. Further manual verification is necessary before confirming exploitability.

7. Security Recommendations

The following improvements are recommended for developer review:

1. Review and strengthen the Content Security Policy.
2. Verify CSRF protection on relevant forms.
3. Configure appropriate anti-clickjacking protections.
4. Review cross-domain resource access policies.
5. Implement Subresource Integrity where applicable.
6. Review and improve relevant HTTP security headers.
7. Conduct a follow-up assessment after remediation.

8. Learning Outcomes

This project strengthened my practical understanding of:

* Website and web application security.
* OWASP ZAP and passive scanning.
* HTTP requests and responses.
* Security headers and browser security controls.
* Vulnerability reporting and remediation recommendations.

9. Assessment Scope and Limitations

This was an authorised, exploratory assessment of the publicly accessible website.

The work did not constitute a comprehensive penetration test. It did not include a full source-code review, comprehensive authenticated testing or exploitation of vulnerabilities.

The findings represent observations recorded at the time of scanning and may change as the website is updated.

10. Conclusion

The OWASP ZAP baseline scan identified 27 alerts across Medium, Low and Informational risk categories, with no High-risk alerts reported.

The assessment highlighted several security configuration areas that warrant developer review and possible improvement.

This project provided practical experience in website security assessment, automated scanning, security observations and technical documentation.

⸻

Author: Chiebuzor Kester

Focus Areas: Cybersecurity | Website Security | Ethical Hacking



































































