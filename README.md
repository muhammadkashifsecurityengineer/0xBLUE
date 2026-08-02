<div align="center">

# 0xBLUE 🔵
### SOC Analyst Arsenal

**A curated, browser-importable bookmark collection for SOC Analysis, Incident Response, DFIR, Threat Hunting & Threat Intelligence.**

![Links](https://img.shields.io/badge/links-474-0A84FF?style=for-the-badge&logo=bookstack&logoColor=white)
![Categories](https://img.shields.io/badge/categories-61-1E90FF?style=for-the-badge&logo=bookmeter&logoColor=white)
![License](https://img.shields.io/badge/license-CC0%201.0-lightgrey?style=for-the-badge)
![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen?style=for-the-badge&logo=github)
![Maintained](https://img.shields.io/badge/maintained-yes-success?style=for-the-badge)

**Author:** [Muhammad Kashif](https://github.com/muhammadkashifsecurityengineer) · CNSP · Penetration Tester · Bug Bounty Hunter

</div>

---

## Table of Contents 📖

- [Why This Exists 🚀](#why-this-exists-)
- [Import Instructions 📥](#import-instructions-)
- [What's Inside 🗂️](#whats-inside-️)
- [Full Category Index 🧭](#full-category-index-)
- [Scope & Maintenance 🛠️](#scope--maintenance-️)
- [License 📜](#license-)

---

## Why This Exists 🚀

> Most "awesome list" repos for security are plain Markdown — which means copying and pasting links **one at a time**.

**0xBLUE ships differently.** It's a standard Netscape bookmark file (`bookmarks.html`), so it imports directly into Chrome, Firefox, Edge, or Brave as a **ready-made bookmark folder structure** — no manual copy-pasting, in addition to being fully browsable right here on GitHub.

```
   474 links   →   61 categories   →   1 file   →   1 import   →   done
```

---

## Import Instructions 📥

<table>
<tr>
<td width="50%" valign="top">

### Chrome / Edge / Brave 🌐
1. Open Bookmark Manager
   `Ctrl+Shift+O` (Windows/Linux) or `Cmd+Shift+O` (Mac)
2. Click the **⋮** three-dot menu
3. Select **Import Bookmarks**
4. Choose `bookmarks.html` from this repo

</td>
<td width="50%" valign="top">

### Firefox 🦊
1. Open the **Library**
   `Ctrl+Shift+O` (Windows/Linux) or `Cmd+Shift+O` (Mac)
2. **Import and Backup → Import Bookmarks from HTML**
3. Select `bookmarks.html`

</td>
</tr>
</table>

---

## What's Inside 🗂️

The `Tools` section alone is organized into **4 logical groups**, so the folder structure that lands in your browser is clean, not a flat dump of 400+ links:

| Group | Covers |
|---|---|
| 🖥️ **Endpoint Security & DFIR** | Sysinternals, Sysmon, Windows Events, memory & disk forensics, DFIR triage tooling |
| 🌐 **Network Security & Forensics** | DNS, packet capture, IDS/IPS, ransomware & C2 tracking, threat intel platforms |
| 🕵️ **OSINT & Reconnaissance** | Fingerprinting, breach/leak checking, certificate transparency, WHOIS, malware analysis |
| 🛡️ **Web & Vulnerability Scanning** | CMS scanning, URL/phishing analysis, vulnerability management, website recon |

Plus **13 standalone top-level categories** covering attack technique references, event log documentation, IR frameworks, training paths, and community resources (blogs, newsletters, podcasts, Twitter/X lists).

---

## Full Category Index 🧭

<details>
<summary><strong>📚 Reference, Learning & Community</strong> (13 categories) — click to expand</summary>

| Category | Focus |
|---|---|
| 🎯 Attack Reference Material | AD/Kerberos attack techniques (Kerberoasting, DCSync, Golden/Silver Ticket, ADCS abuse, Zerologon, Golden SAML) |
| ✍️ Blogs | Ongoing threat research and DFIR write-ups |
| 📘 Books | Long-form published material on SOC operations and network security monitoring |
| 📋 Event Log References | Vendor log field/event ID docs — Windows, Sysmon, cloud, firewalls, proxies, WAFs, identity providers, SaaS (M365, Google Workspace, Slack, GitHub, Salesforce) |
| 📰 Good Reads | Short-form reading on SOC analyst practice and alert fatigue |
| 🧩 Incident Response Frameworks & Detection Concepts | NIST/CISA IR guidance, Pyramid of Pain, MITRE ATT&CK Navigator, CAR, Engage, Diamond Model |
| 💬 Interview Questions | SOC analyst interview preparation |
| 📬 Newsletters | Weekly curated security roundups |
| 🎧 Podcasts | Ongoing security and DFIR audio content |
| 📖 Resources & Reference Material | MITRE ATT&CK, D3FEND, CAPEC, Sigma, Atomic Red Team, OWASP, NIST CSF, CIS Benchmarks, STIX/TAXII |
| 🧪 Sample Datasets & Practice Environments | Splunk BOTS v1–v3, OTRF/Mordor, DetectionLab, Malware-Traffic-Analysis.net, Security Onion PCAPs |
| 🎓 Training & Certifications | GIAC, SANS, OffSec, TCM, Security Blue Team |
| 🐦 Twitter/X | Accounts tracking malware, threat intel, and breaking security news |

</details>

<details>
<summary><strong>🖥️ Tools → Endpoint Security & DFIR</strong> — click to expand</summary>

| Category | Focus |
|---|---|
| 🩸 Active Directory Security Auditing | Attack-path mapping and AD hardening (BloodHound CE, PingCastle, ADRecon) |
| 🐳 Container and Kubernetes Security | Image/cluster scanning + runtime threat detection (Trivy, kube-bench, kube-hunter, Falco) |
| 🍯 Honeypots and Deception | Attacker-facing decoys (T-Pot, Cowrie, Dionaea, OpenCanary, HoneyDB) |
| 🦠 Malware Analysis and Reverse Engineering | Static/dynamic toolchains (REMnux, FLARE-VM, Ghidra, CAPA, YARA) |
| 🧰 Misc Tools | Sysinternals, JWT decoding, PCAP analysis |
| 📦 Sandboxes | Detonation platforms (CAPEv2, Cuckoo Sandbox, MetaDefender) |
| 🔐 Secrets and Supply Chain Security | TruffleHog, Gitleaks, detect-secrets, Syft, Grype |
| 🗄️ SIEM and Log Management (Self-Hosted) | Wazuh, Graylog, Elastic Security |
| ⚙️ Sysmon Configuration | Community Sysmon config templates for high-fidelity event logging |
| 🕰️ Threat Hunting and DFIR | Velociraptor, KAPE, Volatility 3, Chainsaw, Hayabusa, Plaso, Timesketch, RegRipper, osquery, LimaCharlie, FTK Imager, Sleuth Kit |

</details>

<details>
<summary><strong>🌐 Tools → Network Security & Forensics</strong> — click to expand</summary>

| Category | Focus |
|---|---|
| 🌐 DNS | DNS history and lookup tools |
| 🔎 Detection Engineering and Rule Repositories | Sigma, Elastic, and Splunk detection content |
| 🔄 Detection Rule Conversion | Cross-SIEM detection rule translation (Uncoder AI, Snorpy) |
| 📡 Network Forensics | Wireshark, NetworkMiner, Arkime, tcpdump, Zeek, Snort, Suricata |
| 🛰️ Network Scanning | Passive and active reconnaissance utilities |
| ⚔️ Purple Team and Adversary Emulation | MITRE Caldera, Stratus Red Team, Infection Monkey |
| 📊 Query Language and SIEM Cheat Sheets | SPL, KQL, Elasticsearch Query DSL references |
| 💰 Ransomware and C2 Tracking | Ransomware leak site and C2 infrastructure trackers |
| 🎼 SOAR and Case Management | Cortex, Shuffle |
| 🔒 SSL/TLS | Certificate and TLS configuration testing |
| 🧠 Threat Intelligence Platforms | MISP, OpenCTI, Malpedia, EDR Telemetry, threatfeeds.io |
| 🗺️ Threat Modeling | OWASP Threat Dragon |

</details>

<details>
<summary><strong>🕵️ Tools → OSINT & Reconnaissance</strong> — click to expand</summary>

| Category | Focus |
|---|---|
| 🔢 ASN | Autonomous system number lookups |
| 💧 Breach and Leak Checking | Credential exposure and leak-database lookups |
| 📱 Browser and Mobile Forensics | Hindsight, ALEAPP, iLEAPP |
| 🧩 Browser Extension | Browser extension inspection |
| 📜 Certificate | Certificate transparency and lookup |
| ☁️ Cloud Security Posture | Prowler, ScoutSuite (AWS/Azure/GCP auditing) |
| 📧 Emails | Header and DMARC/SPF/DKIM analysis |
| 🧾 EXE Lookup | Windows binary reputation lookup |
| 👆 Fingerprinting | Internet-wide asset and exposure search engines |
| #️⃣ Hash | Hash calculation, cracking, NSRL lookup |
| 🚩 IOC Lookups | IP, domain, URL, and hash reputation services |
| 🏷️ MAC | MAC address vendor lookup |
| 🧭 Multifunctional LookUp Services | General-purpose recon and lookup platforms (CentralOps, IPinfo.io) |
| 🔍 OSINT | theHarvester, SpiderFoot, Maltego, Amass, Recon-ng, Sherlock |
| 🎣 Phishing Analysis | PhishTool, ThePhish, Gophish, Phish Report, OpenPhish |
| 🔌 USB and PCI | Device and vendor ID lookup |
| 🖱️ User Agent | User agent string parsing |
| 🏛️ WHOIS and Domain Registration Lookup | Domain ownership and registration records |

</details>

<details>
<summary><strong>🛡️ Tools → Web & Vulnerability Scanning</strong> — click to expand</summary>

| Category | Focus |
|---|---|
| 🧱 CMS Scan | WordPress, Joomla, Drupal security scanning |
| 🧪 Data Manipulation Online Tools | CyberChef, regex, formatting, diff utilities, jq |
| 🔗 URL | URL scanning and phishing detection (Wannabrowser, Unshorten.it) |
| 🐞 Vulnerability Management | Nuclei, Greenbone/OpenVAS, Exploit-DB, Vulners, NVD |
| 🕸️ Website Scan | Link extraction and web technology fingerprinting |

</details>

---

## Scope & Maintenance 🛠️

- ✅ Every link is verified reachable and current as of the last update. Dead or superseded tools (e.g. the original `dnSpy` or `CRXcavator`) are swapped for their actively maintained successors — never left as dead links.
- 🆓 The collection favors **free and community-accessible resources** over vendor-gated platforms, so it stays usable without enterprise licensing.
- 🔤 Categories are sorted alphabetically, and links within each category are sorted alphabetically — new pull requests should slot into the correct position rather than being appended.
- 🤝 **Pull requests are welcome.** When proposing an addition, note which category it belongs in and confirm the resource is still actively maintained.

---

## License 📜

<div align="center">

This is a link collection, not original software or written content.
Released under **CC0 1.0** — fork it, reorganize it, build on it, no attribution required.

**⭐ If this saved you time hunting down references, consider starring the repo.**

</div>
