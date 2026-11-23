# Shreyashree Dasgupta — Cybersecurity Portfolio

Welcome to my professional cybersecurity portfolio for **WQE7001 Cyber Security**, showcasing my technical skills, hands-on security labs, and learning progression toward a career in Governance, Risk, and Compliance (GRC).

---

## 1. About Me

My name is Shreyashree Dasgupta, and I am currently pursuing a Master of Cyber Security at Universiti Malaya, building upon my undergraduate background with a B.Tech in Information Technology. My interest in cybersecurity stems from seeing how rapidly evolving digital infrastructures require not just strong technical controls, but structured governance, risk management, and compliance frameworks to remain resilient. Through my graduate coursework in WQE7001 Cyber Security and hands-on technical labs, I am strengthening my ability to bridge the gap between technical security findings and organizational risk decisions. Having previously worked with enterprise platforms and earned credentials such as ServiceNow Certified System Administrator, I enjoy analyzing how systems operate, identifying configuration weaknesses, and translating technical vulnerabilities into clear remediation priorities. This portfolio documents my practical progress in network reconnaissance, packet analysis, and secure configuration management as I prepare for a specialized career in Governance, Risk, and Compliance (GRC).

---

## 2. Technical Skills

* **Network Reconnaissance & Service Enumeration (Nmap):** *Working knowledge* — Demonstrated in [Project 1: Network Service Enumeration and Vulnerability Analysis with Nmap](projects/nmap-service-scan/)
* **Network Packet Inspection & Traffic Analysis (Wireshark):** *Working knowledge* — Demonstrated in [Project 2: Network Packet Inspection and Unencrypted HTTP Traffic Analysis with Wireshark](projects/wireshark-traffic-analysis/)
* **Security Risk Assessment & Remediation Mapping:** *Working knowledge* — Demonstrated across both [Nmap Vulnerability Analysis](projects/nmap-service-scan/) and [Wireshark HTTP Analysis](projects/wireshark-traffic-analysis/)
* **Enterprise Platform Administration & Service Management (ServiceNow):** *Confident*
* **Version Control & Technical Documentation (Git & GitHub):** *Working knowledge* — Demonstrated through branching, pull requests, and structured documentation in this repository
* **Linux Command Line & Virtual Lab Environments:** *Working knowledge*

---

## 3. Certifications and Training

* **WQE7001 Cyber Security (Graduate Coursework & Hands-On Labs)** — *Universiti Malaya, In Progress (Target completion: January 2027)*
* **TryHackMe Practical Security Labs (*Nmap*, *Wireshark: The Basics*)** — *Completed (November 2026)*
* **ServiceNow Certified System Administrator (CSA)** — *ServiceNow (Issued April 2024)*
* **Microsoft Certified: Azure AI Fundamentals (AI-900)** — *Microsoft (Issued 2025)*
* **Introduction to Data Science** — *Cisco Networking Academy (Issued July 2024)*
* **ISC2 Certified in Cybersecurity (CC)** — *Planned (Target completion: April 2027)*

---

## 4. Projects

1. **[Project 1: Network Service Enumeration and Vulnerability Analysis with Nmap](projects/nmap-service-scan/)**
   Conducted authorized port scanning, service version detection, and Nmap Scripting Engine (NSE) enumeration against an isolated Windows Server target (`WIN-SCAN`), uncovering exposed services (Anonymous FTP, HTTP TRACE, and RDP) and formulating prioritized hardening controls.
2. **[Project 2: Network Packet Inspection and Unencrypted HTTP Traffic Analysis with Wireshark](projects/wireshark-traffic-analysis/)**
   Analyzed captured network traffic (`http1.pcapng`) using protocol hierarchy statistics, display filters, and TCP/HTTP stream reconstruction to demonstrate cleartext metadata exposure and recommend TLS enforcement.

---

## 5. Learning Journey

Progressing through WQE7001 Cyber Security has shifted how I approach systems from an operational IT perspective to a security-first, risk-based mindset. Two practical lab areas that stood out in my learning were active network service enumeration using Nmap and passive network packet inspection using Wireshark. In my Nmap enumeration lab, scanning an isolated Windows Server target demonstrated how quickly an attacker can map open ports, identify running software versions, and uncover high-risk misconfigurations such as anonymous FTP authentication, exposed Remote Desktop Protocol (RDP) endpoints, and enabled HTTP TRACE methods. Learning how to translate those technical outputs into prioritized remediation steps—like enforcing Network Level Authentication and replacing plaintext FTP with SFTP—directly connects technical scanning with governance and risk control validation. Complementing this, my Wireshark traffic analysis lab reinforced the importance of transport-layer confidentiality. By filtering HTTP packets and reconstructing cleartext TCP streams, I observed firsthand how unencrypted web traffic exposes request URLs, host headers, user-agent strings, and server banners to anyone monitoring the network path.

One specific technical error I encountered during my Nmap lab occurred when my initial service scan failed and returned the message "Host seems down" despite the target virtual machine running properly. At first, I assumed the target IP address was unreachable or still booting. After checking the network configuration and understanding how Nmap performs host discovery, I realized the target's host firewall was dropping default ICMP ping probes. I resolved the issue by adding the `-Pn` flag to skip ping discovery and treat the host as online, which successfully revealed five open TCP ports and enabled full service enumeration. Troubleshooting this taught me never to rely on a single default probe when validating network exposure or auditing firewall rules.

Despite steady progress, one area I still find challenging is interpreting complex, multi-protocol packet captures containing encrypted TLS handshakes, fragmented traffic, and high-volume background noise. While isolating cleartext HTTP streams in a small capture is straightforward, distinguishing subtle anomalous behavior from legitimate enterprise traffic in larger captures requires deeper protocol fluency, familiarity with normal baseline patterns, and sustained analytical practice.

To strengthen both my technical assessment skills and my governance readiness, I have set a concrete improvement goal: by April 2027, I aim to complete the ISC2 Certified in Cybersecurity (CC) certification alongside ten structured defensive security, compliance, and risk-assessment labs on TryHackMe. I will measure this goal by passing the official ISC2 CC exam, adding the verified Credly badge to this portfolio, and publishing two additional risk-focused hardening and audit write-ups in my GitHub repository.

---

## 6. Career Objective

My primary career objective is to secure a Governance, Risk, and Compliance (GRC) Analyst role where I can combine my B.Tech in Information Technology, enterprise platform experience, and Master of Cyber Security training from Universiti Malaya to help organizations manage cyber risk and maintain regulatory compliance. I am particularly interested in conducting security control assessments, mapping technical vulnerabilities to frameworks such as ISO/IEC 27001 and NIST CSF, and supporting audit readiness. To achieve this goal over the next twelve months, I am focusing on three concrete steps: first, completing my Master of Cyber Security coursework with a strong emphasis on risk management and security governance; second, earning my ISC2 Certified in Cybersecurity (CC) credential by April 2027 to validate my foundational governance and security knowledge; and third, expanding this GitHub portfolio with structured security audit and compliance-mapping case studies.

---

## 7. Contact Information

* **Email:** [dgshreyashree@gmail.com]
* **GitHub:** [://github.com](https://://github.com)
* **LinkedIn:** [linkedin.com/in/shreyashree-dasgupta-7026b01b4](https://www.linkedin.com/in/shreyashree-dasgupta-7026b01b4/)
