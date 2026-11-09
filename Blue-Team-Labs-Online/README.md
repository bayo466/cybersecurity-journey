# Network Analysis and Ransomware Investigation

## Overview

This project documents my learning experience during a defensive cybersecurity investigation involving network traffic analysis and ransomware identification.

The exercise focused on examining packet-capture data, investigating HTTP and DNS communications, using file hashes for threat-intelligence research, and understanding ransomware file recovery.

**Platform:** Blue Team Labs Online (BTLO)  
**Investigation:** Network Analysis – Ransomware  
**Environment:** Kali Linux running in VirtualBox on Windows 11  
**Tools:** Wireshark, Linux terminal, MalwareBazaar, and ESET TeslaCrypt Decryptor

## Investigation Objectives

- Understand and examine PCAPNG network captures.
- Identify relevant network communications.
- Investigate HTTP requests and transferred files.
- Understand MD5 and SHA256 file hashes.
- Use threat-intelligence sources for malware identification.
- Examine DNS queries and understand their significance.
- Learn about ransomware recovery and evidence verification.

## Investigation Workflow

1. **Evidence preparation:** Organised the investigation environment and examined the supplied file structure.
2. **Packet analysis:** Used Wireshark to inspect network traffic and identify relevant protocols.
3. **HTTP investigation:** Examined HTTP requests and learned how transferred objects can be exported from packet captures.
4. **Hash analysis:** Calculated file hashes and used hash-based threat intelligence to research a suspicious executable.
5. **DNS investigation:** Applied Wireshark display filters to examine DNS queries.
6. **Recovery concepts:** Studied the use of a specialised decryptor and the importance of verifying recovered files.

## Skills Practised

- Network traffic analysis
- Wireshark display filters
- HTTP and DNS investigation
- Linux command-line operations
- File hashing and integrity identification
- Threat-intelligence research
- Evidence handling and documentation

## Key Lessons

- A DNS query does not automatically prove that a connection succeeded or that a domain is malicious.
- A file downloaded over HTTP is not necessarily proof that it was executed.
- Hash-based threat intelligence can help identify suspicious files.
- Investigation findings should distinguish observed evidence from assumptions.
- Recovery tools should be used only when appropriate for the identified ransomware family.

## Limitations

The investigation was based on a limited packet capture. Network traffic alone cannot establish every stage of an infection, including whether a downloaded executable was actually executed.

## Disclaimer

This repository documents my learning and investigative methodology. It does not redistribute BTLO challenge files, malware samples, challenge flags, or restricted challenge materials.

## Author

Electronics and Computer Engineering student | Cybersecurity learner
