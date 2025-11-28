# ARP-Spoofing-Detection-Lab


Objective
Simulate an ARP Spoofing MITM attack and detect malicious ARP traffic using Wireshark.

Skills Gained
• Network security fundamentals
• Layer 2 attack simulation
• Traffic capture & analysis
• Indicators of compromise (IOC) detection
• Mitigation strategies for ARP poisoning

Tools Used
Kali Linux, Ettercap or arpspoof, Wireshark

Repository Structure

/
├─ Report.md
├─ Evidence/
│   ├─ screenshots/
│   ├─ pcap-files/
├─ Tools/
│   └─ scripts-used/
└─ Findings/
    ├─ vulnerabilities.md
    ├─ mitigations.md


Execution Summary (short)
ARP poisoning was used to redirect traffic through the attacker machine. Wireshark confirmed abnormal ARP replies indicating MITM conditions. Preventive controls documented in Report.md.

Full Report
See Report.md
(More screenshots coming after additional tests)
