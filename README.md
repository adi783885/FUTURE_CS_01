🛡️ **Web Application Security Assessment**

👤** Auditor Profile**

    Name: Adithyan.V  

Role: Cybersecurity Researcher  

Track: Cyber Security (CS)  

Tool Used: OWASP ZAP (Zed Attack Proxy)  

🎯 **Target Analysis**

    URL: https://juice-shop.herokuapp.com

Type: Intentionally Vulnerable Web Application    

🔍 **Methodology**

    ZAP Setup: Configured a proxy to monitor data traffic between the browser and the website.  

Site Mapping: Explored the application to identify all interactive pages and buttons.  

Scanning: Conducted automated active and passive scans to detect common security flaws.  

Review: Analyzed 122 total alerts to verify and triage real-world security risks.  

🚨 **Risk Summary**

**Severity	  Count	Key   Vulnerabilities Identified**
🔴 Medium	     2	      Session ID in URL Rewrite, Cross-Domain Misconfiguration  
🟡 Low	       7	      Missing Security Headers (CSP, HSTS, X-Frame-Options)  
🔵 Info	       3	      Server Version Leaks, Private IP Disclosure   

✅ **Conclusion**

This task helped in understanding real-world web vulnerabilities and how automated tools like OWASP ZAP assist in identifying security issues. Implementing secure cookie attributes and hardening server-side security headers will significantly improve the application's overall security posture.
