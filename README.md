**Web Application Security Assessment**

**Auditor Profile**

    Name: Adithyan.V  

Role: Cybersecurity Researcher   

Tool Used: OWASP ZAP (Zed Attack Proxy)  

**Target Analysis**

    URL: https://juice-shop.herokuapp.com
    
Type: Intentionally Vulnerable Web Application  

**Methodology**

    ZAP Setup: Configured a proxy to monitor data traffic between the browser and the website.  

Site Mapping: Explored the application to identify all interactive pages and buttons.  

Scanning: Conducted automated active and passive scans to detect common security flaws.  

Review: Analyzed 122 total alerts to verify and triage real-world security risks.  

**Risk Summary**

🔴 Medium (2 Found): Session ID in URL Rewrite, Cross-Domain Misconfiguration.  

🟡 Low (7 Found): Missing Security Headers including CSP, HSTS, and X-Frame-Options.  

🔵 Informational (3 Found): Server Version Leaks and Private IP Disclosure.  

**Key Findings**

Detailed vulnerability analysis and technical evidence will be found in the report folder.  

**Conclusion**

This task helped in understanding real-world web vulnerabilities and how automated tools like OWASP ZAP assist in identifying security issues. Implementing secure cookie attributes and hardening server-side security headers will significantly improve the application's overall security posture.
