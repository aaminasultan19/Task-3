#  Nessus Vulnerability Scan 

This project documents my hands-on experience using **Tenable Nessus Essentials** to perform a basic vulnerability scan on my local machine as part of a cybersecurity learning journey.

---

##  Objective

- Use Nessus Essentials to scan a local system.
- Identify known vulnerabilities.
- Analyze and document results.
- Compare past and current scan outcomes.

---

##  Tools Used

-  [Nessus Essentials](https://www.tenable.com/products/nessus/nessus-essentials)
-  Windows 10 Local Machine
-  Screenshots and HTML reports for documentation

---

##  Screenshots

| Step | Description | Screenshot |
|------|-------------|------------|
| 1 | Advanced Scan Template | ![](./screenshots/Screenshot%202025-05-29%20203812.png) |
| 2 | Scan Configuration | ![](./screenshots/Screenshot%202025-05-29%20213217.png) |
| 3 | Scan Running | ![](./screenshots/Screenshot%202025-05-29%20204222.png) |
| 4 | Scan Completed | ![](./screenshots/Screenshot%202025-05-29%20204511.png) |
| 5 | Report Exported | ![](./screenshots/Screenshot%202025-05-29%20213139.png) |

---

##  Scan Reports

| Date       | Result         | Notes |
|------------|----------------|-------|
| **April 2025** | ✅ Vulnerabilities found | Detected some medium-severity issues. See `basic scan_5nrsza.html`. |
| **May 2025**   | ❌ No vulnerabilities | System likely patched OR Nessus Essentials scan quota reached. See `My Local Machine_g553b0.html`. |

 Reports:
- [`basic scan_5nrsza.html`](./basic%20scan_5nrsza.html)
- [`My Local Machine_g553b0.html`](./My%20Local%20Machine_g553b0.html)

---

##  Observations & Learnings

- Running vulnerability scans regularly helps monitor system health.
- Nessus reports detail vulnerabilities with CVSS scores and plugin info.
- The Essentials license has a limited IP scan quota (16 IPs).
- Patch management or plugin expiration may influence scan results.

---

##  Next Steps

- Try authenticated scanning for deeper results.
- Use additional tools like OpenVAS or Burp Suite.
- Explore automation via Nessus CLI or API.

---

> 📌 *This project is part of my cybersecurity learning path focused on threat detection and vulnerability management.*
