# TryHackMe: Cybersecurity 101 Path - My Learnings & Takeaways

---

## Overview

This repository serves as a detailed summary of my key learnings and practical takeaways from completing the **TryHackMe (THM) "Cybersecurity 101" path**. This extensive foundational path marked my dedicated entry into the cybersecurity domain, equipping me with essential basic knowledge across a wide range of topics and providing valuable hands-on exposure.

While I've gained a solid initial understanding across these areas, I recognize the need to develop a deeper and more robust comprehension of these concepts as I continue my journey.

---

## Detailed Learnings & Practical Takeaways

The "Cybersecurity 101" path provided a comprehensive introduction to various facets of cybersecurity. Here's a breakdown of what I specifically learned, module by module, and my key takeaways:

### SECTION 1: Start Your Cyber Security Journey

* **Offensive Security Intro:**
    * **Learned:** The basics of offensive security, ethical hacking, and why it's crucial for defense.
    * **My Takeaway:** I was immediately drawn to the proactive nature of offensive security – the idea of thinking like an attacker to build stronger defenses resonated strongly with my goal of strengthening internet security.
* **Defensive Security Intro:**
    * **Learned:** Fundamental concepts of defensive security, threat detection, and prevention.
    * **My Takeaway:** Understanding the defender's mindset is just as crucial as the attacker's. It showed me the critical need for robust systems to counter threats identified on the offensive side.
* **Search Skills:**
    * **Learned:** Techniques for effective online research, OSINT principles, and using search engines for security purposes.
    * **My Takeaway:** These skills are surprisingly powerful and foundational for any cybersecurity role, whether it's for initial reconnaissance in offensive operations or quick threat intelligence in defensive tasks.

---

### SECTION 2: Linux Fundamentals

* **Linux Fundamentals Part 1, 2, & 3:**
    * **Learned:** Core Linux commands, file system navigation, user management, permissions, process management, and basic scripting concepts.
    * **My Takeaway:** Getting comfortable with the Linux command line was a significant step. It's clear that proficiency in Linux is absolutely critical for almost any cybersecurity role, especially offensive operations.

---

### SECTION 3: Windows and AD Fundamentals

* **Windows Fundamentals 1, 2, & 3:**
    * **Learned:** Windows command line, PowerShell basics, user accounts, services, and core system functionalities.
    * **My Takeaway:** While different from Linux, understanding Windows is equally vital, given its prevalence in enterprise environments. PowerShell, in particular, seems like a powerful tool for automation and system interaction.
* **Active Directory Basics:**
    * **Learned:** The fundamental structure and function of Active Directory, its components (users, groups, OUs), and its importance in enterprise networks.
    * **My Takeaway:** I realized that Active Directory is a massive target for attackers due to its central role in managing user access and resources. Understanding its structure is key to finding vulnerabilities within an enterprise.

---

### SECTION 4: Command Line

* **Windows Command Line & Windows PowerShell:**
    * **Learned:** Deeper dives into `cmd` and PowerShell for administrative tasks and system information gathering.
    * **My Takeaway:** My command-line proficiency significantly improved. PowerShell offers incredible flexibility and automation capabilities that `cmd` simply doesn't, making it a powerful tool for system interaction.
* **Linux Shells:**
    * **Learned:** Further exploration of the Linux command line, common shell commands, and basic shell scripting.
    * **My Takeaway:** I gained more confidence navigating and manipulating Linux systems. The flexibility of basic shell scripting is invaluable for automating small tasks during engagements.

---

### SECTION 5: Networking

* **Networking Concepts, Essentials, & Core Protocols:**
    * **Learned:** Comprehensive understanding of networking models (OSI, TCP/IP), various network devices, IP addressing, routing, and fundamental protocols (HTTP, DNS, FTP, SSH).
    * **My Takeaway:** This section profoundly deepened my understanding of how data actually travels across networks. It transformed networking from an abstract concept into a tangible system, which is crucial for identifying where vulnerabilities might lie.
* **Networking Secure Protocols:**
    * **Learned:** Principles of secure communication protocols like HTTPS, SSH, and VPNs.
    * **My Takeaway:** My primary takeaway is the critical importance of secure protocols in ensuring data confidentiality and integrity. Without them, sensitive information would be trivially exposed, highlighting the need for their correct implementation.
* **Wireshark: The Basics & Tcpdump: The Basics:**
    * **Learned:** How to capture and analyze network traffic using packet sniffers like Wireshark and Tcpdump.
    * **My Takeaway:** Network traffic analysis is incredibly useful. It's like seeing the "conversation" happening on the network, which is invaluable for both identifying suspicious activity (threat hunting) and understanding normal network behavior for reconnaissance.
* **Nmap: The Basics:**
    * **Learned:** Fundamental usage of Nmap for network scanning, host discovery, and port enumeration.
    * **My Takeaway:** Nmap completely changed my perspective on network reconnaissance; it's the "eyes and ears" for understanding a target's network landscape. My favorite basic Nmap scan type is the **SYN scan (`-sS`)** for its speed and stealth.

---

### SECTION 6: Cryptography

* **Cryptography Basics, Public Key Cryptography Basics, & Hashing Basics:**
    * **Learned:** Core concepts of encryption, decryption, symmetric vs. asymmetric cryptography, and hashing algorithms (MD5, SHA).
    * **My Takeaway:** What I found most critical is how cryptography underpins nearly all modern secure communication. Understanding the differences between symmetric, asymmetric, and hashing is foundational for grasping how data is protected in transit and at rest.
* **John the Ripper: The Basics:**
    * **Learned:** How to use John the Ripper for password cracking, understanding hash formats, and dictionary attacks.
    * **My Takeaway:** This tool was a stark demonstration of why strong, unique passwords are non-negotiable. It truly highlighted the vulnerabilities of weak or reused credentials and the importance of robust password policies.

---

### SECTION 7: Exploitation Basics

* **Moniker Link (CVE-2024-21413):**
    * **Learned:** An example of a real-world vulnerability and how it can be exploited (or how it works at a basic level).
    * **My Takeaway:** This specific CVE taught me the constant race between attackers discovering vulnerabilities and defenders patching them. It emphasized the critical importance of prompt patching and continuous vulnerability management.
* **Metasploit: Introduction, Exploitation, & Meterpreter:**
    * **Learned:** A comprehensive introduction to the Metasploit Framework, including searching for exploits, payload generation, setting up listeners, and basic post-exploitation with Meterpreter.
    * **My Takeaway:** Metasploit completely transformed my understanding of "hacking" from abstract theory to a practical, methodical process. The **Meterpreter shell** is the most powerful feature I've seen so far, offering incredible flexibility for post-exploitation activities.
* **Blue:**
    * **Learned:** A practical walk-through of exploiting the EternalBlue vulnerability (MS17-010).
    * **My Takeaway:** The most impactful lesson from exploiting EternalBlue was seeing firsthand how quickly an unpatched, widely-known vulnerability can be leveraged to gain deep system access. It underscored the severe risk of neglecting security updates.

---

### SECTION 8: Web Hacking

* **Web Application Basics:**
    * **Learned:** How web applications function, client-side vs. server-side, and the request/response cycle.
    * **My Takeaway:** I realized that web applications present an enormous and often complex attack surface. Understanding their underlying architecture is the first step to identifying vulnerabilities.
* **JavaScript Essentials:**
    * **Learned:** Basic JavaScript concepts relevant to web application security (e.g., how client-side scripts can be manipulated).
    * **My Takeaway:** Understanding JavaScript is crucial because client-side vulnerabilities are often overlooked. Knowing how JavaScript interacts with the DOM helps in identifying potential XSS or client-side manipulation flaws.
* **SQL Fundamentals:**
    * **Learned:** Basic SQL commands for database interaction and initial concepts of SQL Injection.
    * **My Takeaway:** My biggest takeaway is that improper input validation can expose entire databases. SQL Injection is a potent reminder that seemingly small coding errors can lead to devastating data breaches.
* **Burp Suite: The Basics:**
    * **Learned:** Introduction to Burp Suite for web application testing, including proxying requests and basic traffic manipulation.
    * **My Takeaway:** Burp Suite is absolutely critical for anyone interested in web hacking; it's an indispensable proxy and interception tool that allows you to truly see and manipulate web traffic.
* **OWASP Top 10 - 2021:**
    * **Learned:** The most critical web application security risks and how to identify them.
    * **My Takeaway:** I found "Broken Access Control" most interesting because it highlights how seemingly minor logic flaws in application design can lead to unauthorized access to sensitive functionalities or data.

---

### SECTION 9: Offensive Security Tooling

* **Hydra:**
    * **Learned:** Deeper dive into Hydra for various service brute-forcing and its practical applications.
    * **My Takeaway:** Using Hydra brought clear ethical considerations to mind: the immense power of automated brute-forcing necessitates strict adherence to ethical guidelines and proper authorization when used.
* **Gobuster: The Basics:**
    * **Learned:** How to use Gobuster for directory and file brute-forcing on web servers.
    * **My Takeaway:** Directory enumeration with tools like Gobuster is a fundamental part of the reconnaissance phase. It often reveals hidden directories, sensitive files, or forgotten resources that can provide critical entry points.
* **Shells Overview:**
    * **Learned:** Different types of shells (bind, reverse), how to obtain them, and their importance in post-exploitation.
    * **My Takeaway:** The key difference is that a **reverse shell** is often far more reliable in real-world scenarios, as it initiates an outbound connection, bypassing many firewall restrictions. This is crucial for maintaining access.
* **SQLMap: The Basics:**
    * **Learned:** Automated SQL injection testing using SQLMap.
    * **My Takeaway:** Automated tools like SQLMap are incredibly powerful for rapidly identifying and exploiting SQL injection vulnerabilities. While powerful, they also reinforce the need for understanding the underlying manual process.

---

### SECTION 10: Defensive Security

* **Defensive Security Intro:**
    * **Learned:** The overall landscape of defensive security, including roles, responsibilities, and methodologies.
    * **My Takeaway:** This section further shaped my understanding that defense is a constant, ongoing battle requiring layered security and proactive measures, not just reactive responses.
* **SOC Fundamentals:**
    * **Learned:** The role of a Security Operations Center (SOC), common SOC tools, and incident triage.
    * **My Takeaway:** I found the structured approach of how a SOC operates most interesting – how they monitor, detect, and respond to threats using a systematic workflow.
* **Digital Forensics Fundamentals:**
    * **Learned:** Core principles of digital forensics, evidence integrity, and the forensic process.
    * **My Takeaway:** Maintaining the **chain of custody** is absolutely critical in forensics; without it, digital evidence can be inadmissible or unreliable, potentially hindering an investigation or legal proceedings.
* **Incident Response Fundamentals:**
    * **Learned:** The stages of an incident response plan (preparation, identification, containment, eradication, recovery, lessons learned).
    * **My Takeaway:** The most important takeaway from understanding the incident response lifecycle is that preparation is key. Having a well-defined plan significantly reduces the impact and recovery time of a security incident.
* **Logs Fundamentals:**
    * **Learned:** The importance of logging, types of logs, and basic log analysis for security purposes.
    * **My Takeaway:** I now see effective logging as incredibly crucial for both defense and forensics. Logs are the "breadcrumbs" that allow defenders to trace attacker activity and forensic investigators to reconstruct events.

---

### SECTION 11: Security Solutions

* **Introduction to SIEM:**
    * **Learned:** What a Security Information and Event Management (SIEM) system is and its role in collecting and analyzing security data.
    * **My Takeaway:** SIEMs are vital for defenders to gain comprehensive visibility into their networks by aggregating logs and alerts from disparate sources, allowing for centralized monitoring and analysis.
* **Firewall Fundamentals:**
    * **Learned:** The purpose of firewalls, different types (packet filtering, stateful, WAF), and basic firewall rules.
    * **My Takeaway:** The primary function of a firewall is to act as a crucial gatekeeper, controlling network traffic based on predefined rules. These rules directly impact security by either allowing or blocking communication.
* **IDS Fundamentals:**
    * **Learned:** Introduction to Intrusion Detection Systems (IDS), how they work, and their role in identifying malicious activity.
    * **My Takeaway:** The main difference is that an **IDS (Intrusion Detection System)** primarily *alerts* on suspicious activity, acting as a "silent alarm," while an **IPS (Intrusion Prevention System)** can *actively block* or prevent that activity.
* **Vulnerability Scanner Overview:**
    * **Learned:** What vulnerability scanners are, how they work, and their importance in proactive security assessments.
    * **My Takeaway:** Automated vulnerability scanners are excellent for efficiently identifying known weaknesses across a broad scope. They complement manual penetration testing by providing a baseline and highlighting low-hanging fruit.

---

### SECTION 12: Defensive Security Tooling

* **CyberChef: The Basics:**
    * **Learned:** How to use CyberChef for various data transformations, encoding, decoding, and analysis.
    * **My Takeaway:** I find CyberChef incredibly versatile for quick, on-the-fly analysis tasks. It's like a Swiss Army knife for manipulating data formats during investigations or even reverse engineering.
* **CAPA: The Basics:**
    * **Learned:** Introduction to CAPA for identifying malware capabilities.
    * **My Takeaway:** The main advantage of CAPA is its ability to quickly provide a high-level overview of a malware sample's potential behaviors, saving significant time in initial analysis.
* **REMnux: Getting Started:**
    * **Learned:** An overview of the REMnux distribution for reverse engineering and malware analysis.
    * **My Takeaway:** Having a dedicated, pre-configured environment like REMnux is incredibly important for malware analysis, as it provides all the necessary tools without needing to set them up individually.
* **FlareVM: Arsenal of Tools:**
    * **Learned:** The extensive toolset provided by Flare-VM for malware analysis on a Windows platform.
    * **My Takeaway:** Seeing the sheer volume and specialized nature of tools in Flare-VM truly changed my perspective on the depth and complexity involved in professional malware analysis.

---

### SECTION 13: Build Your Cyber Security Career

* **Security Principles:**
    * **Learned:** Key security principles like least privilege, defense in depth, and separation of duties.
    * **My Takeaway:** I believe **"least privilege"** is the most fundamental security principle for building secure systems. Limiting access to only what's absolutely necessary drastically reduces the impact of a compromise.
* **Careers in Cyber:**
    * **Learned:** Overview of various career paths in cybersecurity, required skills, and certifications.
    * **My Takeaway:** This section solidified my focus on offensive security roles like penetration testing and red teaming, while also showing me the interconnectedness of various specializations within cybersecurity.
* **Training Impact on Teams:**
    * **Learned:** The importance of continuous learning, training, and skill development for security teams.
    * **My Takeaway:** I learned that continuous learning is not just personal growth, but a critical necessity in cybersecurity. The threat landscape evolves so rapidly that staying updated is essential for effective defense.

---

## What's Next?

Having established this comprehensive foundational understanding with "Cybersecurity 101," I am now incredibly excited to continue my journey and dive deeper into practical offensive security by actively working through the **TryHackMe Junior Penetration Tester path**. This next phase will allow me to build upon these basics, refine my skills, and explore more advanced techniques in a structured manner, always aiming to strengthen internet security through ethical vulnerability discovery.

---

