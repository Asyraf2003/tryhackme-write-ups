# 🔍 TryHackMe - Search Skill

🗂️ Path: Pre-Security > Introduction to Cyber Security  
📅 Completed: July 14, 2025  

---

## 🎯 Room Objectives

This room focuses on sharpening your ability to find reliable information online by:

- Evaluating the credibility of information sources  
- Using advanced search engine operators efficiently  
- Exploring specialized search engines for cybersecurity intelligence  
- Understanding how to read and use technical documentation  
- Leveraging social media and news outlets as threat intelligence sources  

---

## 🧠 Key Concepts Learned

- **Source Evaluation**: Know the author and credibility of the information.
- **Evidence & Reasoning**: Confirm claims with logical, fact-based evidence.
- **Bias & Objectivity**: Distinguish between fact and opinion.
- **Corroboration**: Always cross-check with independent, reliable sources.

---

## 🔧 Search Operators & Tips

| Operator       | Function                                                             |
|----------------|----------------------------------------------------------------------|
| `""`           | Search for an **exact phrase** (`"admin login"`).                    |
| `site:`        | Limit search to a **specific website** (`site:gov.id`).              |
| `-`            | **Exclude** a term (`login -facebook`).                              |
| `filetype:`    | Search specific **document types** (`filetype:pdf security guide`).  |

---

## 🔎 Specialized Search Engines

### 🖥️ Shodan
- Search engine for internet-connected devices (IoT, webcams, routers).
- Reveals open ports, service banners, and device vulnerabilities.

### 🌐 Censys
- Security-focused search engine for exposed hosts, certificates, and services.
- Great for SSL/TLS fingerprinting and metadata analysis.

### 🧪 VirusTotal
- Scans files and URLs with multiple antivirus engines.
- Shows detection ratios, file behavior, and threat intelligence relationships.

### 🔐 Have I Been Pwned
- Check if your email/username was leaked in a **data breach**.
- Helps identify exposed credentials and compromised accounts.

---

## 🧨 Vulnerabilities & Exploits

### 🧾 CVE (Common Vulnerabilities and Exposures)
- Global registry for publicly disclosed cybersecurity vulnerabilities.
- Format: `CVE-YYYY-NNNNN`
- Example search: https://nvd.nist.gov

### 💣 Exploit Database (Exploit-DB)
- Archive of public **exploits** and **proof-of-concepts** (PoC).
- Maintained by Offensive Security.
- Useful for mapping CVEs to actual working exploit code.

---

## 📚 Technical Documentation Sources

### 🐧 Linux Manual Pages
- Built-in command documentation (`man ls`, `man passwd`).
- Useful for syntax, parameters, and command behavior.

### 🪟 Microsoft Docs
- Documentation for Windows internals, PowerShell, CMD, etc.
- https://learn.microsoft.com

### 📦 Product Documentation
- Vendor manuals: Cisco, Apache, MySQL, Fortinet, etc.
- Covers default configs, update procedures, and hardening guidelines.

---

## 🧩 Interesting Question

> **Q:** Why should cybersecurity professionals learn how to use advanced search techniques?  
> **A:** Because the web is full of hidden data — misconfigured services, outdated systems, and leaked credentials. Advanced search helps you collect actionable intelligence and uncover risks that attackers often exploit first.

---

## 💬 Personal Reflection

> "This room completely changed how I think about search engines. I used to Google for quick answers — now I can find leaked documents, exposed devices, and breached data like a pro. It gave me real-world recon skills that I’m excited to apply in red teaming and threat hunting."

---

## 🔗 Additional Resources

- 🧭 [TryHackMe - Search Skill Room](https://tryhackme.com/room/searchskills)
- 📁 [Notion Write-Up](https://www.notion.so/TryHackMe-Search-Skill-232140182520806aa688d0958898f116?source=copy_link)

---

🛡️ Happy Hunting!

