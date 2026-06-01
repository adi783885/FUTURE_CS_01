<div style="font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif; max-width: 800px; margin: 0 auto; padding: 20px; color: #24292e; background-color: #ffffff; line-height: 1.6;">
  
  <div style="background: linear-gradient(135deg, #1f2937, #111827); color: #ffffff; padding: 30px; border-radius: 8px; margin-bottom: 30px; box-shadow: 0 4px 6px -1px rgba(0,0,0,0.1);">
    <h1 style="margin: 0; font-size: 28px; font-weight: 700; letter-spacing: -0.5px; display: flex; align-items: center; gap: 10px;">
      🛡️ Web Application Security Assessment
    </h1>
    <p style="margin: 10px 0 0 0; color: #9ca3af; font-size: 16px;">Task 01: Vulnerability Identification & Posture Analysis</p>
  </div>

  <div style="display: block; margin-bottom: 25px;">
    <table style="width: 100%; border-collapse: collapse; margin-bottom: 20px;">
      <tr>
        <td style="width: 50%; vertical-align: top; padding-right: 15px;">
          <div style="background-color: #f8fafc; padding: 15px; border-left: 4px solid #3b82f6; border-radius: 0 4px 4px 0; height: 100%;">
            <h3 style="margin: 0 0 8px 0; font-size: 14px; text-transform: uppercase; letter-spacing: 0.5px; color: #64748b;">👤 Auditor Profile</h3>
            <strong style="font-size: 16px; color: #1e293b;">Adithyan.V</strong>
            <div style="font-size: 13px; color: #475569; margin-top: 2px;">Cybersecurity Researcher</div>
            <div style="font-size: 13px; color: #64748b; margin-top: 6px;"><strong>Tool:</strong> OWASP ZAP (Zed Attack Proxy)</div>
          </div>
        </td>
        <td style="width: 50%; vertical-align: top; padding-left: 15px;">
          <div style="background-color: #f8fafc; padding: 15px; border-left: 4px solid #10b981; border-radius: 0 4px 4px 0; height: 100%;">
            <h3 style="margin: 0 0 8px 0; font-size: 14px; text-transform: uppercase; letter-spacing: 0.5px; color: #64748b;">🎯 Target Analysis</h3>
            <div style="font-size: 13px; margin-bottom: 4px; color: #1e293b;"><strong>URL:</strong> <a href="[https://juice-shop.herokuapp.com](https://juice-shop.herokuapp.com)" style="color: #2563eb; text-decoration: none; word-break: break-all;">[https://juice-shop.herokuapp.com](https://juice-shop.herokuapp.com)</a></div>
            <div style="font-size: 13px; margin-bottom: 4px; color: #1e293b;"><strong>Type:</strong> Intentionally Vulnerable Web App</div>
            <div style="font-size: 13px; color: #1e293b;"><strong>Method:</strong> Proxy Interception & Automated Scanning</div>
          </div>
        </td>
      </tr>
    </table>
  </div>

  <hr style="border: 0; border-top: 1px solid #e2e8f0; margin: 25px 0;" />

  <div style="margin-bottom: 25px;">
    <h2 style="font-size: 18px; font-weight: 600; margin-top: 0; margin-bottom: 15px; color: #0f172a; display: flex; align-items: center; gap: 8px;">
      🚨 Risk Summary
    </h2>
    <p style="font-size: 14px; color: #475569; margin-top: -5px; margin-bottom: 12px;">The assessment yielded a total of <strong>122 alerts</strong> across multiple severity brackets:</p>
    
    <table style="width: 100%; border-collapse: collapse; text-align: left; font-size: 14px; box-shadow: 0 1px 3px rgba(0,0,0,0.05); border-radius: 6px; overflow: hidden;">
      <thead>
        <tr style="background-color: #f1f5f9; border-bottom: 2px solid #e2e8f0;">
          <th style="padding: 12px; font-weight: 600; color: #334155; width: 25%;">Severity</th>
          <th style="padding: 12px; font-weight: 600; color: #334155; width: 15%; text-align: center;">Count</th>
          <th style="padding: 12px; font-weight: 600; color: #334155; width: 60%;">Key Vulnerabilities discovered</th>
        </tr>
      </thead>
      <tbody>
        <tr style="border-bottom: 1px solid #edf2f7; background-color: #fffaf0;">
          <td style="padding: 12px; font-weight: 600; color: #c2410c;">🔴 Medium</td>
          <td style="padding: 12px; text-align: center; font-weight: bold; color: #c2410c;">2</td>
          <td style="padding: 12px; color: #4a5568;">Session ID in URL Rewrite, Cross-Domain Misconfiguration</td>
        </tr>
        <tr style="border-bottom: 1px solid #edf2f7; background-color: #fefce8;">
          <td style="padding: 12px; font-weight: 600; color: #a16207;">🟡 Low</td>
          <td style="padding: 12px; text-align: center; font-weight: bold; color: #a16207;">7</td>
          <td style="padding: 12px; color: #4a5568;">Missing Security Headers (CSP, HSTS, X-Frame-Options)</td>
        </tr>
        <tr style="background-color: #f0fdf4;">
          <td style="padding: 12px; font-weight: 600; color: #15803d;">🔵 Info</td>
          <td style="padding: 12px; text-align: center; font-weight: bold; color: #15803d;">3</td>
          <td style="padding: 12px; color: #4a5568;">Server Framework Leaks & Private IP Address Disclosure</td>
        </tr>
      </tbody>
    </table>
  </div>

  <div style="background-color: #f0f9ff; border: 1px solid #bae6fd; border-left: 4px solid #0284c7; padding: 12px 16px; border-radius: 4px; margin-bottom: 25px; font-size: 13.5px; color: #0369a1;">
    ℹ️ <strong>Documentation:</strong> Detailed findings, parameters, and evidence logs are structurally stored inside the <code>report/</code> folder within the <strong>Vulnerability Assessment Report.pdf</strong>.
  </div>

  <div style="background-color: #fafafa; border: 1px solid #e5e5e5; padding: 20px; border-radius: 6px;">
    <h2 style="font-size: 18px; font-weight: 600; margin-top: 0; margin-bottom: 10px; color: #0f172a; display: flex; align-items: center; gap: 8px;">
      ✅ Conclusion
    </h2>
    <p style="margin: 0; color: #334155; font-size: 14px; text-align: justify;">
      This task helped in understanding real-world web vulnerabilities and how automated tools like OWASP ZAP assist in identifying security issues. Remediation of the discovered vectors—specifically transitioning state parameters out of dynamic URLs and establishing rigid boundary controls—will robustly advance the platform's security baseline.
    </p>
  </div>

</div>
